# 3D Flip Clock (Apple Design System)

An interactive single-file 3D flip clock web application designed with the Apple Design System (`apple.DESIGN.md`), featuring flat color-blocking depth, pill-shaped controls, and full support for embedding in Google Sites.

## Features

- **Real-Time Flip Clock**: High-precision millisecond-aligned second ticking with 3D top/bottom flap animations, 12-hour or 24-hour format, optional seconds, optional `AM`/`PM` indicator, Gregorian date, weekday, and Chinese lunar date.
- **Countdown Timer**: Includes quick presets (`1`, `5`, `15`, and `25` minutes) plus custom `HH:MM:SS` input and a completion chime.
- **Stopwatch**: Tracks elapsed time down to centiseconds (`.00`) with lap recording (`分圈`) and reset support.
- **Interactive 3D Controls**: Drag to rotate (`rotateX` / `rotateY`), scroll to zoom, and double-click (or use the menu) to reset the view.
- **Sound, Wake Lock & Fullscreen**: Toggle synthesized mechanical flip ticks (via Tone.js), keep the screen awake using the Screen Wake Lock API, and enter/exit fullscreen mode.
- **Customization & Persistence**: Customize font weight, digit color, card background color, and display toggles (`顯示農曆`, `顯示星期`, `顯示 AM/PM`, `24 小時制`, `顯示背景`), saved to `localStorage` and configurable via URL query parameters (`?mode=clock|timer|stopwatch&format=12|24&seconds=0|1&theme=light`).

## Usage

Open `3d_flip_clock_clockhub_clone.html` directly in any modern web browser. No build step or local server is required (CDN access is used for Tailwind CSS and Tone.js).

## Embedding on Google Sites

See `google_sites_guide.md` for step-by-step instructions on hosting the HTML file (e.g., via GitHub Pages) and embedding it into Google Sites.