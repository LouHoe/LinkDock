# LinkDock

A lightweight personal shortcut launcher for URLs, files, and folders.

## Features

- Store and quickly open URLs, file paths, and applications
- Real-time search across name, target, and tags
- Drag & drop URLs directly onto the list
- Import / Export as JSON
- No login, no server — everything lives in your browser
- Compatible with the LinkDock desktop app (Windows/WinForms) — export from desktop, import to web

## Usage

Just open the app and start adding shortcuts. Your data is saved automatically in your browser's local storage.

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | Add |
| `Ctrl+E` | Edit selected |
| `Ctrl+O` | Open selected |
| `Ctrl+F` | Focus search |
| `Del` | Delete selected |
| `Esc` | Deselect |

## Limitations

The web version cannot open local file paths directly — this is a browser security restriction. Local paths are copied to your clipboard instead so you can paste them into Explorer.

## Deployment

Hosted on [GitHub Pages](https://louhoe.github.io/LinkDock).
