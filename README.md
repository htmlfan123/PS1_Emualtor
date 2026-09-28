# PS1 Emulator

A simple browser-based PlayStation 1 emulator that lets you load and play PS1 game files directly in the browser using EmulatorJS.

## What it does

This project provides some code for running PS1 ROMs in a web browser. You can upload a game image, and the app loads the PSX emulator core so you can start playing without a separate backend.

## Features

- Upload a PS1 ROM from your computer
- Play games in the browser
- Uses EmulatorJS for the emulator core
- Works as a static website
- Supports several common PS1 disc and image formats

## Supported file types

The app accepts these extensions:

- .bin
- .cue
- .img
- .mdf
- .pbp
- .toc
- .cbn
- .m3u
- .ccd
- .chd

## Run the project locally

You can open the site directly in a browser, or serve it locally for a cleaner setup.

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Run a local web server

```bash
cd PS1_Emualtor
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- This project relies on the EmulatorJS CDN (`https://cdn.emulatorjs.org`).
so you need an internet connection
