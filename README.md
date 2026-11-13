# Rotator Cuff Shoulder Model

An installable 3D model of the left shoulder showing the rotator cuff tendons, where tears happen and where they hurt.

A teaching aid, not a diagnostic tool.

## Files
- `index.html` - the whole app (page, styles and code)
- `layers.js` - skin, muscle and bone shapes for the Skin and Muscles layers (see Credits)
- `three.min.js` - the 3D library (three.js r128), bundled so the app works offline
- `manifest.json` - app name, icons and colours for "Add to Home Screen"
- `sw.js` - service worker that saves the files for offline use. Bump `CACHE` when files change.
- `icon-*.png`, `apple-touch-icon.png` - app icons

## Credits and licence
The skin, muscle and bone shapes in `layers.js` are adapted (cropped, simplified, repositioned) from
BodyParts3D, (c) The Database Center for Life Science, licensed under
[CC Attribution-Share Alike 2.1 Japan](https://creativecommons.org/licenses/by-sa/2.1/jp/deed.en).
`layers.js` is shared under the same licence.
