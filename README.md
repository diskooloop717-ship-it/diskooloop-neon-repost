# HTML Scene Recorder + WebM Loop System

**HTML-based visual scene recorder that captures animations into looping WebM assets and rebuilds them as reusable interactive HTML environments.**

This project is a lightweight local tool that records HTML canvas / visual scenes and replays them as looping `.webm` media inside a self-contained HTML environment.

It is designed for experimental visual development, live performance visuals, and Web-based generative scene workflows.

---

## ✦ Overview

This tool allows you to:

- Load a local HTML scene (canvas / DOM / WebGL)
- Record visual output into `.webm`
- Automatically loop recorded media
- Rebuild the scene into a reusable HTML file *(roadmap)*
- Use recordings as visual layers for further composition

Instead of treating visuals as static output, this system treats them as **replayable time-based assets**.

---

## ✦ Key Features

### 1. HTML Scene Recording

Captures live-rendered HTML canvas or visual animations into a `.webm` file.

→ [`html-scene-recorder/`](html-scene-recorder/)

### 2. Loop Playback Engine

Automatically plays recorded `.webm` files in seamless loops inside HTML.

→ [`html-scene-loop-player/`](html-scene-loop-player/)

### 3. Scene Rebuilder *(planned)*

Generates a self-contained HTML file that embeds or references recorded media.

### 4. Lightweight Local Workflow

No build tools required. Runs directly in the browser.

---

## ✦ Quick Start

### Record a scene

1. Open [`html-scene-recorder/index.html`](html-scene-recorder/index.html) in **Chrome**
2. Choose a local WebGL / canvas HTML file (e.g. a generative art sketch)
3. Wait until the scene appears **fullscreen**
4. Press **`R`** to start recording, **`R`** again to stop
5. A `.webm` file downloads automatically (e.g. `my-scene-recording.webm`)

### Loop playback

1. Open [`html-scene-loop-player/index.html`](html-scene-loop-player/index.html)
2. Choose the `.webm` from your Downloads folder
3. The video plays **fullscreen** with **loop ON** by default

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `L` | Toggle loop |
| `O` | Open another file |

---

## ✦ Repository Structure

```
diskooloop-neon-repost/
├── html-scene-recorder/     # Record HTML canvas → .webm
├── html-scene-loop-player/  # Fullscreen loop playback
└── README.md
```

---

## ✦ Use Cases

- Live visual performance (DJ/VJ setups)
- Generative art experiments
- WebGL / Canvas prototyping
- Visual asset creation for streaming overlays
- Loop-based motion design systems

---

## ✦ Concept

This project explores the idea that:

> **HTML scenes are not static pages, but recordable time-based visual systems.**

By capturing and replaying HTML output, scenes become reusable **visual objects** rather than single-run experiences.

---

## ✦ Tech Stack

- Vanilla JavaScript
- HTML5 Canvas / WebGL (optional)
- MediaRecorder API
- WebM video format

---

## ✦ Future Extensions

- Scene Rebuilder (embed / reference recorded media in standalone HTML)
- WebGL texture integration (video → 3D surface)
- Multi-layer loop composition
- MIDI / audio reactive control
- Real-time streaming integration (OBS / DJ setups)

---

## ✦ License

MIT License — see [LICENSE](LICENSE).

---

## Topics

`html` · `webm` · `canvas` · `visual-art` · `generative-art` · `webgl` · `mediarecorder` · `vj-tool` · `live-coding`

---

## 解説（日本語）

このリポジトリは、**ブラウザ上の HTML ビジュアル（Canvas / WebGL）を録画し、ループ再生用の WebM アセットとして使い回す**ためのローカルツールセットです。

### 2つのツール

| ツール | 役割 |
|--------|------|
| **html-scene-recorder** | HTML シーンを全画面で表示し、`R` キーで `.webm` として録画 |
| **html-scene-loop-player** | 録画した `.webm` を全画面・ループ再生 |

### なぜ分かれているか

録画（キャプチャ）と再生（ループ）は用途が異なるため、**別 HTML ファイル**として独立させています。録画ツールはそのまま完成版として維持し、ループ専用プレイヤーは別プロジェクトとして追加しています。

### 動作環境

- **Chrome 推奨**（WebM / MediaRecorder 対応）
- ビルド不要 — ファイルをダブルクリックするだけ
- データはローカルのみ（サーバー送信なし）

### GitHub 公開について

この URL を README・SNS・ポートフォリオ等に掲載して問題ありません。録画ファイル（`.webm`）本体をリポジトリに含める必要はありません。
