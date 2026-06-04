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

## Arguments (optional)

The **Arguments** field lets you pass command-line parameters to an executable when you open it. Leave it blank for URLs and regular files — it only applies to programs you want to launch with specific options.

| Name | Target | Args |
|------|--------|------|
| Chrome Incognito | `C:\Program Files\Google\Chrome\Application\chrome.exe` | `--incognito` |
| Notepad with file | `C:\Windows\notepad.exe` | `C:\notes\todo.txt` |
| Python script | `C:\Python\python.exe` | `C:\scripts\myscript.py` |

## Limitations

The web version cannot open local file paths directly — this is a browser security restriction. Local paths are copied to your clipboard instead so you can paste them into Explorer.

## Desktop App

A full Windows desktop version is available that can open local files and folders directly.

[⬇ Download LinkDock Desktop v1.0](https://github.com/LouHoe/LinkDock/releases/download/v1.0/LinkDock-Desktop.zip)

No installation needed — just unzip and run.

## Deployment

Hosted on [GitHub Pages](https://louhoe.github.io/LinkDock).
