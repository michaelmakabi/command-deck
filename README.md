# Command Deck

**Master Makabi's personal task OS.** Live at [to-dos.mtip.ai](https://to-dos.mtip.ai/).

A single-file HTML/CSS/JS task dashboard with natural-language capture, voice input, smart prioritization, and persistent state — no backend, no dependencies.

## Features

- **Brain-dump capture** — type or hit the mic, the engine parses category, priority, due date, and writes a tactical call-to-action
- **Voice input** — browser-native `SpeechRecognition` (Chrome / Edge / Safari)
- **Smart prioritization** — Urgent / High / Medium / Low, color-coded with sub-3px accent bars
- **Multi-filter** — by category (Money, Loren AI, BRiX, MTIP, Personal, Tech, Sites) and status
- **Sort modes** — Priority, Due Date, Category, Status, Alphabetical
- **Persistent state** — `localStorage` keeps your progress across reloads
- **Status flow** — To Do → In Progress → Done, click-toggle per card
- **Editable preview** — every parsed task lands in an editable form before commit

## Stack

- Single-file HTML
- Inline CSS (no framework — system font stack with Inter fallback)
- Vanilla JS
- Web Speech API for voice
- `localStorage` for persistence

No build step. No backend. Open `index.html` and go.

## Design

Light theme. Red, white, and blue. Apple × Tesla × MTIP — clean whitespace, hairline borders, restrained color use. Red as the action color, navy as the trust color, white as the canvas.

## Deployment

Deployed via Lovable to `to-dos.mtip.ai`. DNS managed via GoDaddy (A record → `185.158.133.1`, TXT verification `_lovable`).

---

*Built for Master Makabi. Powered by LOREN AI.*
