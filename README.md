# ChakChoka - شكشوكة 🍳

A lightweight Windows tray app that fixes text typed with the wrong keyboard layout.
Typed Arabic while your keyboard was on French (AZERTY), or the opposite?
Select the text, press a hotkey, and it gets converted in place.

## Features

- Converts AZERTY ↔ Arabic in any app: select the text, press the hotkey, done
- Handles mixed Arabic/Latin text, converting each character separately
- Global hotkey, selectable from the tray menu (default: `Ctrl + Alt + D`)
- Optional middle-click conversion
- Small animated popup next to the cursor while converting (it never steals focus)
- Restores your previous clipboard content after conversion
- Run at Windows startup, pause/resume from the tray
- Interface in English, Français and العربية
- Single instance, no installer needed

## Usage

1. Run `ChakChoka.exe`. It lives in the system tray near the clock.
2. Select the text you typed with the wrong layout.
3. Press `Ctrl + Alt + D` (or middle-click if enabled).

Right-click the tray icon to change the hotkey, language, startup behavior, or pause the app.

## Build

Requires Windows and the .NET SDK.

    dotnet build -c Release

The tray icon `chakchoka.ico` is embedded as a resource.

## Author

Developed by Bilal Ben Jmaa
