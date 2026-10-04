# Paneless privacy policy

_Last updated: 3 October 2026_

Paneless is a screenshot and screen-recording tool. It is designed so that your information never leaves your computer.

## What Paneless collects
Nothing. Paneless has no accounts, no analytics, no advertising, no crash reporting to anyone and no tracking of any kind.

## Network use
Paneless does not connect to the internet. It does not upload, sync or share your screenshots, videos, galleries or anything else.

## What Paneless stores on your computer
- The screenshots, videos and galleries you create, in `Pictures\Paneless` and `Videos\Paneless` (or the matching OneDrive folders if Windows has redirected them). You can open and delete these like any other files.
- A small settings file and a log file in `%LOCALAPPDATA%\Paneless`. The log lists technical events (for example which video encoder was used) and file names. It does not contain the contents of your screen or any text you copy. If Paneless crashes, the details go into this log (and a technical crash dump into the `Crashpad` folder beside it); they stay on your computer. "Copy diagnostics" in the tray menu puts recent log lines on your clipboard only when you choose it, so you can paste them into a bug report yourself.

## Your screen and keyboard
- Paneless captures your screen only when you ask it to, with a shortcut or the tray menu.
- Shortcuts that use the Windows key (only if you choose one in Settings) use a keyboard hook. It is installed only while such a shortcut is set, and removed when you change it back. It watches for the key combinations you chose and Esc only. It does not record, store or send what you type.
- While a screen recording is running, and only if "Show clicks and shortcuts in videos" is on (it is by default; turn it off in Settings), Paneless watches mouse clicks and key presses so it can draw them into the video. It shows a key only when Ctrl, Alt or Win is held, or for Enter, Tab, Esc, Delete and F1–F24. Ordinary typing, including passwords, is never shown, recorded or kept. The hooks are removed when the recording stops.
- "Copy text" reads the words in the area you select with the text recognition built into Windows, on your computer. The picture is deleted straight away and only the text is placed on your clipboard.
- Paneless places the captures you make on your clipboard. It does not read or keep what you have copied from other programs.

## Children
Paneless collects no personal information from anyone, including children.

## Changes
If this policy changes, the new version will be published here with a new date.

## Contact
Questions or concerns about privacy? Open an issue at https://github.com/joshhebb/paneless/issues and it will be answered there.
