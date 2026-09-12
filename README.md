# InstaKeys

A lightweight Chrome extension that adds keyboard navigation and like/comment
shortcuts to Instagram's web feed, so you can browse posts without the mouse.

## Features

- **Arrow keys (↑ / ↓)** — move to the next / previous post.
- **X** — like or unlike the post currently centered on screen.
- **C** — open the comment field; **Enter** submits, **Esc** closes it.
- On-screen onboarding overlay the first time it runs, explaining the controls.
- Requests **no permissions** and runs only on `instagram.com`.

## Tech

- Chrome Extension (Manifest V3), vanilla JavaScript content script.
- Popup UI styled with Bootstrap.

## Install (from source)

1. Clone or download this repository.
2. Open `chrome://extensions` in Chrome.
3. Enable **Developer mode** (top right).
4. Click **Load unpacked** and select the project folder.
5. Open [instagram.com](https://www.instagram.com/) and use the keyboard shortcuts above.

## Project structure

```
InstaKeys/
├── manifest.json   # extension manifest (MV3)
├── content.js      # keyboard navigation injected into Instagram
├── popup.html      # toolbar popup
├── script.js       # popup share button logic
└── icons/          # extension icons
```
