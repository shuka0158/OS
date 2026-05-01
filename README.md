# TEMP-OS

A fully functional desktop operating system that runs entirely in the browser — built as a single `index.html` file.

## Features

### Window Manager
- Draggable, resizable windows
- Minimize, maximize, and close buttons
- Z-index focus management
- Taskbar with open window buttons

### Applications

| App | Description |
|-----|-------------|
| 📝 Text Editor | Write and save notes (persisted via localStorage) |
| 💻 Terminal | Fake Linux-like shell with filesystem, command history, Tab autocomplete |
| 📁 File Explorer | Navigate a virtual filesystem with sidebar shortcuts |
| 🎨 Drawing App | Canvas drawing with pen, eraser, fill, shapes, color palette, undo, save PNG |
| 🎮 Game Center | Snake, Tic-Tac-Toe, Memory Cards, Breakout |
| ✅ To-Do List | Add, complete, and filter tasks (persisted via localStorage) |
| ⏰ Alarm Clock | Live clock, alarm setter, and stopwatch |
| 🖼️ Image Viewer | Open local files or URLs, zoom, rotate |
| 🌐 Browser | Embedded browser with bookmarks, DuckDuckGo search, YouTube embed support |
| ⚙️ Settings | Change username/password, system info, about |

### Terminal Commands
ls, cd, pwd, cat, echo, clear, mkdir, touch, rm, cp, mv,
env, whoami, date, uname, neofetch, history, exit



## Usage

1. Download `index.html`
2. Open it in any modern browser
3. That's it — no server, no install, no dependencies

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- Zero dependencies
- Single file (~1400 lines)
- Data persisted with `localStorage`

## Notes

- The browser app works best with sites that allow iframe embedding (e.g. Wikipedia, Hacker News, Archive.org). Major sites like Google and GitHub block embedding by design (`X-Frame-Options: DENY`) — the browser will detect this and offer to open them in a new tab instead.

## License

MIT
