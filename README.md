# AriaNg Native (Linux Port)

## Introduction
This is an **unofficial Linux port** of [AriaNg Native](https://github.com/mayswind/AriaNg-Native) - a desktop application built by [Electron](https://github.com/electron/electron), with all features of [AriaNg](https://github.com/mayswind/AriaNg).

**Original repository:** [https://github.com/mayswind/AriaNg-Native](https://github.com/mayswind/AriaNg-Native)

AriaNg Native allows you to run AriaNg on Linux without any browser, and provides many additional desktop-specific features that the web version of [AriaNg](https://github.com/mayswind/AriaNg) cannot implement.

## Extra features
1. More user-friendly interface
    * Create new task by dragging-and-dropping file or url
    * Show torrent file information and choose download file before creating task
    * Play sound after download finished
2. Command line arguments, supporting creating new task by opening file
3. File associations for .torrent/.metalink file
4. Taskbar tray, supporting minimizing to tray
5. Local file system operating support
6. Executing custom command on startup
7. Checking for updates on startup

## Introduction of AriaNg
Please visit [https://github.com/mayswind/AriaNg](https://github.com/mayswind/AriaNg) for more information.

## Command Line

```
Usage: AriaNg_Native-Linux-x86_64.appimage [file] [options]

Commands:
  new [file]  Create new download task from exist torrent/metalink file [default]

Options:
  --version, -v      Show version number                               [boolean]
  --help, -h                                                           [boolean]
  --development, -d  Enable Debug Mode                                 [boolean]
  --minimal, -m      Hide the main window at startup                   [boolean]
```

## Installation
#### Prebuilt release
Latest Release: [https://github.com/marsianna4ka/AriaNg-Native-Linux/releases](https://github.com/marsianna4ka/AriaNg-Native-Linux/releases)

Available builds:
- `AriaNg_Native-Linux-x86_64.appimage`
- `AriaNg_Native-Linux-arm64.appimage`

#### Building from source
Make sure you have [Node.js](https://nodejs.org/) and [NPM](https://www.npmjs.com/) installed. Then download the source code, and follow these steps.

    $ npm install
    $ npm run publish:linux

The builds will be placed in the dist directory.

## License
[MIT](https://github.com/marsianna4ka/AriaNg-Native-Linux/blob/master/LICENSE)
