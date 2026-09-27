# Running Five Nights at Winston's

This is a static browser game. It has no package dependencies or build step.

Use the **Start application** workflow to serve the repository root on port 5000 with Python's built-in HTTP server. Open the Replit web preview to play. The page downloads `assets.tar` (about 12 MB) on load, so the game may take a moment to appear. A browser with WebGL and Web Audio support is required.

To run it manually from the project root:

```sh
python3 -m http.server 5000 --bind 0.0.0.0
```