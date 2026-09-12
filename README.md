<div align="center">
  <img src="logo.png" alt="InstaKeys logo" width="140" />
  <h1>InstaKeys</h1>
  <p><b>Browse Instagram's web feed without touching the mouse.</b><br/>A lightweight Chrome extension that adds keyboard scrolling and like/comment shortcuts to Instagram on the web.</p>
  <p>
    <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
    <img alt="Chrome Extension" src="https://img.shields.io/badge/Chrome_Extension-MV3-4285F4?logo=googlechrome&logoColor=white">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white">
  </p>
</div>

---

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

## License

Released under the [MIT License](LICENSE) © 2026 Olivier Lüthy. You're free to use, modify and distribute this
software, including commercially, as long as the copyright notice and license are included.

## Author

Built by **Olivier Lüthy** — [GitHub](https://github.com/olivierluethy).
