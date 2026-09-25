# The Cloud Court · 雲庭

A standalone, interactive Canvas 2D living scroll made from the project's reference paintings. Three textured paper puppets float in an animated sky of hand-drawn clouds, mineral greens, indigo, rose, and yellow.

## Run

Open `index.html` directly in a modern browser. No install, build step, account, or internet connection is needed.

For a local server, run from this folder:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Play

- Drag a guardian to reposition it; click or tap to awaken its element.
- Move the pointer through the sky to scatter painted sparks.
- Use the guardian buttons or keys **1**, **2**, **3** to awaken the figures.
- Change **Wind** to adjust cloud drift and puppet movement.
- **Space** pauses or resumes; **R** resets positions, wind, and effects.
- The music button enables quiet, synthesized pentatonic chimes. Sound starts off.
- The lower-right scene button enters fullscreen where supported.
- **Behind the scroll** shows the source paintings and instructions.

Reduced-motion preferences start the scene paused. All controls are keyboard accessible, and the layout adapts to touch screens.

## Files and artwork

- `index.html`: interface and reference gallery.
- `style.css`: responsive presentation.
- `scene.js`: source-coordinate silhouettes, puppet deformation, procedural clouds, particles, pointer controls, and Web Audio synthesis.
- `assets/`: unchanged copies of `5691.JPG`, `5689.JPG`, and `5696 2.JPG` from the parent `reference-images` folder.

The renderer clips the images in memory and bends overlapping image strips to create movement. No source files are modified. Character names and elemental gestures are artistic interpretations, not historical identifications. Keep the assets together with the other files when moving this folder. Reuse of the source artwork remains subject to the rights of its owner.
