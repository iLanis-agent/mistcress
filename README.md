# Mistcress 1.0 TEST
Native Android Undead mirrored-monster visibility puzzle. Android 8+ (min26), target35. Package com.gg007.mistcress. Twelve original unique boards on a compact 4x4 grid.

## Rules
Undead / Haunted Mirror Maze training puzzle. Eight monster cells and eight fixed two-sided diagonal mirrors on a 4x4 grid. Tap a monster cell to cycle blank, Ghost, Vampire, Zombie. Fill every non-mirror cell. Match the G/V/Z inventory totals and all sixteen edge clues. An edge clue follows its line of sight through mirrors until it exits. Vampires are visible only before the FIRST mirror. Ghosts are visible after ANY mirror, even after two or more reflections. Zombies are always visible. Monsters never block sight. If a path visits a visible monster twice, count both visits; inventory totals count distinct occupied cells, not visits. Tap an edge clue to highlight its full route. Numbers in parentheses are your current visible counts, not targets, and can be turned off. Twelve original uniquely solvable boards; auto-check, unlimited undo/reset, next and level selection. Saved palette and optional live sight counts. No pencil marks or timer in this training edition.

## Download and status
https://mega.co.nz/#!dQti3Jrb!DogUn5rw-rCyjt9x3Jw55-PdcipQX_d093dx0SEu3Ug
APK SHA256 e2d8297878a861c8ecb69c0513397866ab755650d7a29e12edec16f0d4b75ba7; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent vector-reflection ray coefficients versus production compass-direction tracing passed 786,432 exhaustive partial and full assignments and 12,582,912 edge sight counts across twelve boards. Each board has exactly one full-rule solution among all 6,561 complete identity assignments, with no restriction on repeated monster visits. Checks include inventory, direct/reflected visibility, persistence after multiple mirrors, repeated-visit weighting, fixed mirrors, bounds, invalid data, undo, solved lock, reset and route tracing. Portable generator reproduces all twelve original layouts with seed 480009; archived Java oracle reruns. Actual drawing-adapter monster taps, edge trace, solve/undo/replay, next, levels, menu, privacy and saved palette/live counts pass. Six inspected drawing previews are not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 179 prior studio descriptions and web registry game/mechanic records. Flood was rejected because Flood It already exists. Raycress locates hidden balls from deflected probe rays. Prismrelay rotates mirrors to route a beam through ordered relays. Mistcress keeps mirrors fixed and instead assigns three monster identities, combining direct/reflected visibility constraints with distinct-cell inventory totals. Its cell-cycling interaction, weighted ray coefficients and exhaustive identity validator differ from those games. No Undead match found in the reviewed corpus; recovered repository corpus remains partial. Known Undead / Haunted Mirror Maze adaptation, not a global invention claim. Original generated boards, code and visuals; no source puzzle layouts, code or art copied.
Rules https://thegriddle.net/haunted/ ; independent rules https://morassgames.com/games/undead/ .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/mistcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.mistcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Mistcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, live sight counts and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 180-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/n5hgy3jymxyl-mistcress-source-archive . Repository https://github.com/iLanis-agent/mistcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
