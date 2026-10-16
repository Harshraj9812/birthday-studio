# Birthday Studio

A private, offline-friendly birthday video editor with cinematic photo animations, custom audio trimming, and H.264 MP4 export—all in your browser.

<img width="2331" height="1585" alt="image" src="https://github.com/user-attachments/assets/60384dd9-a596-478b-8d02-13afc5842dfd" />


## Features

- Create birthday montages from your photos and personalized wishes.
- Choose from five visual presets: Golden Hour, Midnight Bloom, Rose Glow, Classic Cinema, and Blue Hour.
- Make 15, 30, 45, or 60-second videos in vertical, horizontal, or square format.
- Add smooth cinematic movement, gentle zoom, or static photos.
- Use synthesized music or import your own audio with start/end trimming and volume control.
- Preview your video and export MP4 with H.264 video and AAC audio on supported browsers.
- Keep photos and audio on your device, with no uploads or external dependencies.

## Getting started

1. Download or clone this repository.
2. Open `index.html` in a current Chrome, Edge, or Safari browser.
3. Add photos, enter the recipient’s name, and edit the wishes (one line per scene).
4. Choose the style, video length, format, and photo movement.
5. Select a built-in tune, choose no music, or import custom audio.
6. Play the preview, then click **Export MP4 (H.264)**.

No installation, build step, or internet connection is required. Keep `favicon.svg` beside `index.html` to display the favicon.

## Custom audio and trimming

Import an audio file in the Music panel. Once it loads, custom audio is selected automatically. Set **Trim start** and **Trim end** in seconds to choose the section you want.

The selected section starts at the beginning of the video. If it is shorter than the video, the remaining video is silent; if it is longer, playback ends with the video. Audio format support depends on your browser. Try MP3, WAV, or M4A if a file cannot be decoded.

## Export requirements

MP4 export requires browser support for canvas capture and MediaRecorder with H.264 encoding (plus AAC when music is enabled). If the required format is unavailable, the editor displays a message. Try a current Chrome, Edge, or Safari browser.

Export records in real time, so a 30-second video takes about 30 seconds. Keep the tab open and active until recording finishes. The result downloads as `Happy_Birthday_Cinematic.mp4`. Clicking **Stop** during export ends and saves the recording at that point.

## Privacy

Photos and decoded audio remain in browser memory and are not uploaded. Reloading or closing the page clears your imported media and edits. Download your finished video before leaving.

## Project files

- `index.html` — editor interface, styles, animation, audio, and video export.
- `favicon.svg` — birthday cake favicon.
- `README.md` — project documentation.

## Credits

Developed by [Harsh Raj Gupta](https://harshraj.co.in/).
