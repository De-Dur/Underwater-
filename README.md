# Underwater Caustics Camera + Video

Interactive browser-based visual effect app that transforms a live camera feed or uploaded video into a cinematic underwater scene with turquoise ocean atmosphere, moving water-surface waves, and real-time caustic light projection.

## Open the app

👉 **[Open Underwater Caustics Camera + Video](https://De-Dur.github.io/Underwater/)**

## What this project does

Underwater Caustics Camera + Video creates a real-time underwater light effect directly in the browser.

The app uses the camera or an uploaded video as the visual source, then adds layered VFX on top:

- blue-turquoise underwater atmosphere
- soft ocean-surface waves on static areas
- brighter caustic light on moving surfaces
- person / body segmentation
- face and hand tracking
- motion-sensitive light boost
- transparent moving-surface caustics
- vertical-video support with turquoise wave sides

The result is a browser-based live VFX tool for creating the feeling of submerged skin, water refraction, shimmering sunlight, and cinematic underwater light.

## Why this project is useful

This project is useful as:

- a real-time underwater VFX camera
- a mobile-friendly browser visual effect tool
- a live camera filter for artistic documentation
- a video-processing prototype directly in HTML
- a creative coding experiment with MediaPipe tracking
- a browser-based underwater atmosphere simulator
- a visual tool for AI-art references and motion experiments
- a lightweight installation / exhibition camera effect
- a social-media visual effect for reels, portraits, and performance

Instead of editing footage in post-production, the app creates a live underwater look inside the browser.

## Features

- live camera input
- uploaded video input
- iPhone and Android mobile support
- desktop browser support
- face tracking
- hand tracking
- person segmentation
- motion detection
- motion-sensitive caustic intensity
- separate background wave control
- turquoise ocean-surface background waves
- vertical video support with full-height video display
- turquoise wave-filled side areas for vertical video
- transparent moving-surface caustics
- semi-dark underwater color grading on moving bodies
- soft blue-white caustic line projection
- non-looping animated caustic movement
- smoother motion tracking with temporal accumulation
- fully transparent small menu
- one-column mobile-friendly controls
- camera switch button
- video upload button
- single-file HTML app

## Controls

Use the small transparent control panel to adjust the effect.

Main actions:

- **Start camera** — manually starts the live camera if the browser blocks autoplay
- **↺** — switches between front and back camera
- **▣** — loads a local video from your device or computer

Main sliders:

- **Light** — controls caustic intensity on moving surfaces
- **Background** — controls turquoise ocean waves on static / non-moving areas
- **Motion** — controls animation speed of caustics and background waves
- **Scale** — controls the size of the caustic pattern
- **Softness** — controls blur and softness of the light
- **Warmth** — adds warmer golden sunlight tones
- **Glow** — controls soft bloom and wet highlight feeling

## Camera mode

Camera mode uses the device camera as the source.

The app applies:

- face tracking
- hand tracking
- person segmentation
- motion detection
- underwater color grading
- caustic light projection
- turquoise atmosphere

On phones, the camera must be opened from a secure URL such as **GitHub Pages**.  
Camera access usually will not work when opening the HTML file directly from Downloads or Files.

## Uploaded video mode

Click **▣** to load a video from your device.

Uploaded video mode keeps the same visual logic as camera mode:

- tracking still runs on the video
- moving surfaces receive stronger caustics
- non-moving areas receive background ocean waves
- vertical videos keep their full height
- side areas are filled with turquoise wave atmosphere

This is useful for testing the effect on recorded portraits, dance footage, underwater-style videos, or AI-generated clips.

## Mobile use

The app is designed to work on phone screens.

Recommended mobile browsers:

- **iPhone:** Safari
- **Android:** Chrome

For best results:

1. Upload the project to GitHub Pages.
2. Open the GitHub Pages link on your phone.
3. Allow camera permission.
4. Tap **Start camera** if the camera does not start automatically.
5. Use **▣** to test uploaded videos.

If camera does not start:

- make sure the app is opened from HTTPS
- check camera permissions in the browser
- reload the page
- tap **Start camera**
- try using uploaded video mode instead

## Desktop use

Recommended desktop browsers:

- Chrome
- Edge
- Safari
- Firefox

Desktop is useful for:

- testing effects with webcam
- loading larger video files
- screen recording
- preparing visual material for social media
- debugging and adjusting parameters

## Visual concept

The visual concept is based on real underwater caustics: sunlight passes through moving water and creates bright refracted patterns on surfaces.

The project separates the image into different visual zones:

### Moving surfaces

Moving body parts, arms, hands, face, shoulders, or torso receive stronger caustic projection.

These areas stay more transparent so the original face or body remains visible, but with a semi-dark underwater color filter and glowing light lines.

### Non-moving surfaces

Static areas receive a more opaque turquoise atmosphere with blurred ocean-surface waves.

This helps the whole camera view feel submerged, while keeping the moving subject readable.

### Background sides for vertical video

When a vertical video is uploaded, the video keeps its full height.  
The empty side areas become turquoise water-wave zones instead of black bars.

## Files

- `index.html` — main interactive app file
- `README.md` — project description and usage guide
- `LICENSE` — license file

## Browser support

The app uses modern browser APIs:

- camera access through `getUserMedia`
- HTML video playback
- Canvas 2D rendering
- MediaPipe Face Mesh
- MediaPipe Hands
- MediaPipe Selfie Segmentation
- local file video loading through the browser

For best compatibility, use modern versions of Chrome, Edge, Safari, or Firefox.

Camera mode requires HTTPS on mobile devices.

## Publishing on GitHub Pages

Suggested workflow:

1. Create a new GitHub repository.
2. Add the HTML app as `index.html`.
3. Add this file as `README.md`.
4. Add an MIT `LICENSE` file.
5. Go to repository **Settings**.
6. Open **Pages**.
7. Choose the main branch as the source.
8. Wait for GitHub Pages to publish the site.
9. Open the generated HTTPS link on desktop or phone.

## Local testing

For camera testing on desktop, use a local server instead of opening the file directly.

From the project folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

For phone testing, GitHub Pages or another HTTPS host is recommended.

## Performance notes

Real-time tracking and layered effects can be heavy on older phones.

If performance becomes slow:

- reduce **Light**
- reduce **Background**
- reduce **Glow**
- reduce browser zoom / close other tabs
- use shorter uploaded videos
- test in Chrome on Android or Safari on iPhone

## Creative concept

The project explores a hybrid between:

- live camera performance
- underwater atmosphere
- cinematic VFX
- motion-sensitive light
- body-aware digital projection
- browser-based AI-era visual tools
- synthetic water environments
- real-time artistic filters

It is not a traditional static filter.  
The effect changes according to motion, body presence, camera input, and uploaded footage, creating a living underwater light system directly in the browser.

## Maintainer

Created and maintained by **Denisa Durica**.

## Contributing

This repository is primarily an art and interaction design project.  
If you adapt or extend it, please keep the original artistic credit attached.

## License

This project is licensed under the MIT License.

## Attribution

Created by **Denisa Durica**.  
Please keep credit when sharing, remixing, or adapting this project.
