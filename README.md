# LightCanvas — Projection Studio

A browser-based projection visualizer for laptop + HDMI projector setups. This is an original project inspired by the general idea of projection-visual tools; it does not use Lazy Lighting branding or code.

## Features
- Animated Aurora, Nebula, Wave Rings, Spectrum, Embers and Geometry presets
- Add editable shape and text layers
- Load local images and videos
- Drag layers, resize from the corner handle, and adjust position, size, rotation, opacity and color
- Layer list, visibility, lock, duplicate, delete and bring-to-front
- Background color, grid overlay, blackout, pause/resume and fullscreen projection mode
- Download a JSON scene settings file
- Responsive interface; effects run in the browser without a separate server

## Use it
1. Open the published page in a modern desktop browser.
2. Connect the laptop to the projector with HDMI.
3. In your operating system display settings, choose **Extend** (recommended) or Duplicate.
4. Drag the browser window to the projector display.
5. Click **Project fullscreen**. Select an effect or add images/videos/text.
6. Press **Esc** to leave fullscreen.

Local media files are used by the browser and are not uploaded. The scene export currently saves layout settings; it does not bundle uploaded media files.

## Publish on GitHub Pages
A GitHub Actions workflow publishes the static site from the main branch. In GitHub, open **Settings → Pages** and ensure the source is set to **GitHub Actions**. When the workflow finishes, the expected site URL is:

https://mahajan-sanket-1997.github.io/Lightningprojection/

## Current limits
This first version supports layer positioning, scaling and rotation, but not true perspective/corner warping, multi-projector blending or a separate phone remote controller. Browser fullscreen support and HDMI display selection depend on the laptop operating system and browser.
