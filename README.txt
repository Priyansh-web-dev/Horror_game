HORROR GAME — THE DEVIL IN THE SQUARE

Run it
1. Extract this folder if you are using the ZIP.
2. Open a terminal inside the Horror game folder.
3. Run: py -m http.server 8000
   (or: python -m http.server 8000)
4. Visit http://localhost:8000 in a modern browser.

The browser must use a local server to load FBX models. Internet is required for
Three.js modules from jsDelivr.

Controls
PC controls
WASD: move · Shift: sprint · Mouse: aim · Hold left click: fire
R: reload · Esc: pause or release the mouse

Mobile controls
Play in landscape orientation. The game requests fullscreen and landscape lock when
supported; if the browser blocks it, rotate the device when prompted.
Left stick: move · Drag the right side: aim
Fire: hold to shoot · Run: hold to sprint · Reload: reload · Pause: pause the game

Firing and taking damage trigger brief camera shake.

Game
Survive five waves. Each wave takes ten UMP45 hits to clear, and the devil moves 1.17
times as fast as in the previous wave. Health and ammunition refill after each wave.
After the fifth victory, choose Surprise: wait three seconds for surprice.mp3. After
it has played for five seconds, choose “Get the real surprise” to play
Sound_Effect_1.mp3. The game says “Enjoy!” after the first surprise. The devil attacks
more gently to keep the game approachable.

Sound triggers
gunfiring.mp3 restarts on every shot. The supplied voice clips play on player damage,
devil damage, devil death, and player death. A new voice event stops the previous one.

Assets
assets/audio/character: Pugalo devil rig, animation clips, and material maps
assets/audio/character/city: medieval building, source formats, and TGA textures
assets/audio/character/UMP45: UMP45 FBX and its base-color, packed ARM, and normal textures
assets/audio: gameplay MP3 effects, surprice.mp3, Sound_Effect_1.mp3, and character assets

The Three.js code is in index.html. This is a playable prototype; it has no save system.
