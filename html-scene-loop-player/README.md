# WebM Loop Player

Fullscreen **loop playback** for `.webm` files recorded with [html-scene-recorder](../html-scene-recorder/).

Part of [HTML Scene Recorder + WebM Loop System](../README.md).

## Usage

1. Record a scene with `html-scene-recorder` → get e.g. `my-scene-recording.webm`
2. Open `index.html` in **Chrome**
3. **Choose .webm file**
4. Video plays fullscreen with **Loop: ON** (default)

## Controls

| Input | Action |
|-------|--------|
| `Space` | Play / pause |
| `L` | Toggle loop |
| `O` | Open another file |
| **Loop: ON/OFF** | Toggle seamless loop |
| **Change file** | Pick a different recording |

Loop preference is saved in the browser (`localStorage`).
