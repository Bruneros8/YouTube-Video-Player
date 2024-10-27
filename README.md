# YouTube Video Player

This project is a simple HTML page that embeds a YouTube video with autoplay, mute, and loop functionality. The video plays without controls and is optimized for a responsive layout.

## Features
- **Autoplay**: The video starts playing as soon as the page loads.
- **Muted**: The video is muted by default.
- **Looped Playback**: The video repeats automatically.
- **No Controls**: Video player controls are hidden.
- **Responsive**: Video scales to fit different screen sizes.

## Usage
To view the project:
1. Download or clone the repository.
2. Open the `index.html` file in a web browser to see the video player in action.

## Changing the Embedded Video
To embed a different YouTube video, replace the video ID in the `src` URL within `index.html`:
```html
src="https://www.youtube.com/embed/YOUR_VIDEO_ID?controls=0&loop=1&playlist=YOUR_VIDEO_ID&mute=1&autoplay=1"
