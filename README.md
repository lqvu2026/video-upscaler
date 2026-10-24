# Video Upscaler

A simple web app that enlarges a video to a higher resolution (720p up to 4K) right in your browser. Nothing is uploaded; everything runs on your device.

## Features

- Upscale to 720p, 1080p, 1440p or 2160p (4K), keeping the original aspect ratio
- Adjustable sharpening to keep the enlarged picture crisp
- Quality setting to balance file size and detail
- Keeps the original audio
- Preview the result, then download or share it

## How to use

1. Open the page and choose a video.
2. Pick the output resolution, sharpening and quality.
3. Tap **Upscale video** and keep the tab open until it reaches 100%.
4. Download or share the finished file.

## Notes

- The video is re-encoded while it plays, so processing takes about as long as the clip itself. Keep the tab open and in front.
- Upscaling makes the picture larger and smoother, but it can't add real detail that wasn't in the original.
- Output is MP4 on Safari and WebM on Chrome and other browsers.
- Needs a modern browser with WebGL and MediaRecorder support.

## Files

- `index.html` - the whole app (HTML, CSS and JavaScript in one file)
- `video-upscaler-icon.png` - 180x180 Home Screen icon (add your own)

## Hosting on GitHub Pages

1. Put `index.html`, `README.md` and the icon in the repo root.
2. Commit and push.
3. In the repo, go to Settings > Pages and publish from the main branch.
4. To add it to an iPhone Home Screen, open the page in Safari and choose Add to Home Screen. If the icon doesn't update, delete the old shortcut, quit Safari, reload and add it again.
