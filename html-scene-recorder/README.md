# HTML Scene Recorder

Record a local HTML canvas / WebGL scene to **`.webm`** video.

Part of [HTML Scene Recorder + WebM Loop System](../README.md).

## Usage

1. Open `index.html` in **Chrome**
2. **Choose HTML file** — scene opens **fullscreen**
3. Wait for the animation to load
4. Press **`R`** (or click **Start Recording**) to begin
5. Press **`R`** again to stop — **`.webm` downloads** automatically

## Controls

| Input | Action |
|-------|--------|
| `R` | Start / stop recording |
| **Library** | Saved recordings & settings |
| **Change file** | Load a different HTML file |

## Notes

- Works best with pages that render a `<canvas>` (WebGL, Three.js, raw canvas)
- Max recording length: **60 seconds**
- Recordings are also stored in the browser (IndexedDB) for in-app replay
- For **loop playback**, use [`html-scene-loop-player`](../html-scene-loop-player/)
