# HastaLuego – Pixel Art Sailing Game

**HastaLuego** is a mini web game written in pure HTML, CSS, and JavaScript. It was created as a fun farewell interactive message. In the game, you steer a pixel-art sailboat to its destination while avoiding obstacles and following maritime buoy rules.

## Concept and Gameplay
You control a small sailboat using the **arrow keys** (left/right). The goal is to reach the finish (marked by a yellow flag) without crashing or navigating incorrectly. The game starts with an instruction screen (press **Space** to start). Once started, a background music track in the spirit of *“Hasta Luego”* by Hugues Aufray will play in a loop.

**Obstacles:** There are 12 obstacles (rocks and buoys) you must navigate:
- **Rocks:** Brown pixelated rocks appear in the water. Avoid colliding with them or you’ll crash.
- **Red buoys (port side):** Red square buoys float on the left side. You must keep these to your left (i.e., pass to their right side). If you try to pass on the left side of a red buoy, you’ll get a warning and the game will reset.
- **Green buoys (starboard side):** Green triangular buoys float on the right side. You must keep these to your right (pass to their left). Going to the right of a green buoy triggers a warning and reset.

If you hit a rock or take a wrong turn around a buoy, a humorous message will pop up and the game restarts shortly after, allowing you to try again quickly.

Make it past all obstacles and you’ll reach the **yellow flag** – your destination. The game will congratulate you and display a special message (in French) which doubles as an invitation to the creator’s farewell party (the “pot de départ”).

## Controls
- **Left/Right Arrows:** Steer the boat left or right.
- **Space bar:** Start the game from the title screen. After a game over, pressing Space can also restart the game immediately. (On the final screen, Space can be used to replay the game if desired.)

**Note:** The boat stays in the bottom portion of the screen; use the arrows to position it such that you avoid rocks and pass buoys on the correct side.

## Assets and Visuals
All graphics are done in retro **pixel art** style:
- **Boat:** A pixel art sailboat sprite.
- **Rocks and Buoys:** Pixel art obstacles (brown rock, red buoy, green buoy) drawn at low resolution to match the 8-bit aesthetic.
- **Flag:** A pixel art yellow flag marking the finish.
- **Background:** A tiled pixel ocean background with a wave pattern. The background scrolls slowly to simulate moving water.
- **Font:** Pixelated font (Press Start 2P) is used for all on-screen text to reinforce the retro feel.

All image assets are embedded directly in the HTML as Base64 data URIs for portability. They were either created specifically for this game or sourced from free assets and then pixelized. The text panels are styled with CSS (semi-transparent navy background and white pixel font text).

## Music
The game features background music that automatically starts when you begin playing. The track is a royalty-free piece chosen to evoke a similar vibe to *“Hasta Luego”*:
- **Music:** *“Sardana” by Kevin MacLeod* – an upbeat Spanish guitar instrumental (licensed under Creative Commons Attribution 3.0):contentReference[oaicite:25]{index=25}.  
  **Source:** <http://incompetech.com/music/royalty-free/mp3-royaltyfree/Sardana.mp3>  

This music is included via an `<audio>` element with `loop` enabled, so it will play continuously. (If you prefer a different tune, you can replace the audio source with any other loopable, rights-free track.)

## How to Run
Simply open the `index.html` file in a modern web browser. All code and assets are included in that single file, so no external downloads are required (aside from the music file if it’s linked externally – ensure you have an internet connection or use a local file path for the music). 

**Controls Reminder:** Click on the game area (if not already focused) and press Space to start. Use arrow keys to move. The game is best experienced on a desktop browser due to the keyboard controls.

Enjoy navigating the pixel seas, and **bon voyage**! 🚢🌊  
