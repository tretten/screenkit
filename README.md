<h1 align="center">ScreenKit</h1>

<p align="center">
  <img src="logo.png" width="128" alt="ScreenKit icon">
</p>

<p align="center">
A menu-bar screen capture tool for macOS 14 (Sonoma) and later. Press a hotkey, drag to select an area or click a window, and the shot lands in your clipboard and in a local library for cropping, annotating, or turning into a video.
<br>
<a href="https://brandkit.pro/screenkit">brandkit.pro/screenkit</a>
</p>

<p align="center">
  <a href="https://github.com/tretten/screenkit/releases/latest/download/ScreenKit.dmg">
    <img src="download-macos.svg" width="260" alt="Download for macOS">
  </a>
</p>

## Features

- Area and window capture, with a magnifier that follows the cursor while you select.
- A built-in measurement ruler: arrow keys measure the gap between edges under the cursor, Shift measures the outer bounds, and a click stamps the measurement onto the capture.
- Every capture copies to the clipboard automatically and is also saved to a local library.
- Library editor: crop, arrows, shapes, numbered steps, and a magnifier annotation that draws an enlarged detail beside the original.
- Video recording of any selected area, with pause and resume from the menu bar, a live recording timer, and trimming in the built-in editor.
- Optional cursor effects for recordings: click rings (a distinct color for right-click, staggered rings on double or triple clicks), a press-and-hold ring, a fading drag trail, and an auto zoom that eases in on clicks.
- Color picker: `C` copies the hex value of the pixel under the crosshair, `⇧C` also opens it on brandkit.pro/color.
- OCR: select an area to recognize the text in it and copy it to the clipboard without saving an image.
- Automatic JPEG/PNG format detection based on how photographic a capture looks; the clipboard copy always stays lossless PNG.
- Captures can clean themselves up automatically after 1, 7, 15, or 30 days, or be kept forever.
- Configurable hotkey and menu bar icon.

## Privacy

Runs entirely on your Mac. No network calls of its own: the only connection is Sparkle's daily update check to our update server. Text recognition runs on-device through Apple's Vision framework. The only permission it asks for is Screen Recording.

## Install

Download the latest DMG from [Releases](https://github.com/tretten/screenkit/releases), drag ScreenKit to Applications, and grant Screen Recording when prompted (System Settings → Privacy & Security → Screen & System Audio Recording). Builds are signed and notarized, and the app checks for updates daily, installing the next time you quit.

---

This repository holds only signed release builds (DMG/ZIP) for the auto-update feed. It does not contain source code.
