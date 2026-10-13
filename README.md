Foldwake Ferry

Open index.html locally or serve it as a static page. It is the only runtime file. No dependencies, assets, network calls, tracking, storage, secrets, or build steps.

HOW TO PLAY
Nori, an original paper newt, steers a folded boat down a 60-second river. Collect at least 8 paper stars to win. Three reed bumps sink the boat.
- Tap or drag the river. Hold Left/Right buttons, arrows, or A/D.
- Pause/resume, retry, and mute/unmute are included.
- Leaving or hiding the page pauses the game.
- Music begins after the Launch gesture.

DIFFICULTY
First reed spawns at 10 seconds; waves are 7 seconds apart until 25 seconds, then 3.5 seconds apart. Each wave has one narrow reed in one of three widely spaced lanes, not a wall. Reeds are visible for roughly 6 seconds before boat contact. Steering is continuous. A normal hit gives 2 seconds of recovery grace. This is a mechanic available to every player, not a test override.

STYLE AND PROVENANCE
Descriptive PaperCraft #1 direction: layered cut-paper banks/water, folded boat/newt, paper stars/reeds, shadows, fibre texture, soft palette, and stepped bob animation. All art is drawn in Canvas from code. No image provider or external asset. Original synthesized 16-note triangle melody, bass, and pickup/bump tones. No music samples. Title and character were newly coined; no trademark or legal-clearance search was performed.
No peer failed prototype was reused. No GitHub, deployment, posting, account, or Lens+ change was made. Peer owns deployment and device acceptance. This web HTML is not automatically a Snapchat Lens.

FINAL SUSTAINED PLAYTESTS
Real wall clock, normal UI inputs, ordinary random spawns. No fixtures, seeded spawns, state writes, invulnerability override, or test hooks.

Fixed-pattern ordinary-input runs, without obstacle-position telemetry or avoidance decisions:
- Centre cruise: tap centre every 2.5s. 36.5821 game seconds / 37.761 wall seconds. Loss, 5 stars, 3 bumps, 15 inputs.
- Slow sweep: tap x105/180/255/180 every 2.5s. 40.0735 game seconds / 40.232 wall seconds. Loss, 6 stars, 3 bumps, 16 inputs.
Both observed runs survived 30+ seconds. No guarantee for every human or every random run.

Additional assisted normal-input runs:
- 390x844: 60.0075 game seconds / 60.151 wall seconds. Win, 16 stars, 0 bumps, 166 taps.
- 320x640: 60.0066 game seconds / 60.211 wall seconds. Win, 14 stars, 1 bump, 107 taps.
- 1280x900: 60.0143 game seconds / 60.122 wall seconds. Win, 18 stars, 2 bumps, 166 taps.
These runs read object-position telemetry without writing state, then delivered normal pointer taps every 350/550ms. They show playability, not novice human performance. Full timestamped inputs, results, and test code are included.

FUNCTIONAL AND VISUAL QA
Start, retry, pause/resume, keyboard, held buttons, mute/unmute passed at all three sizes. No JS page errors or horizontal overflow. Actual ready, 32-second gameplay, and result screenshots are included. Pixels were inspected at 390, 320, and desktop sizes, including the loss screen. At 320 the Sound on label wraps, but controls and score fit.
No physical phone or Safari test. Pointer handlers were exercised by ordinary browser inputs in mobile-sized viewports; real-device touch remains unverified.
WebAudio Context ran, nonzero signal peak was 0.017699, and muted peak was 0. Music was not human-listened. Physical phone audio and browser autoplay behavior remain unverified.

The README, screenshots, JSON logs, and test scripts are supporting QA, not runtime dependencies. Test scripts contain local environment paths and need adjustment elsewhere.
