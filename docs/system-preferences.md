---
id: system-preferences
title: System Preferences
sidebar_label: System Preferences
---

## General

- Appearance: Dark

## Displays

- Scaled
- 1440 x 900
- Uncheck: Show mirroring options in the menu bar ...

## Dock

- Size: ~ 20%
- Minimize windows using: Scale effect
- Check all boxes except:
  - 🚫Animate opening applications
  - 🚫Show recent applications in Dock
- make Dock autoshow instantly -> in terminal: `defaults delete com.apple.dock autohide-delay -int 0; killall Dock`

## Keyboard

```sh
# needs to restart computer for it to take effect
defaults write -g InitialKeyRepeat -int 10
defaults write -g KeyRepeat -int 1
```

- remove all Shortcuts except:
  - Move focus to next window
  - Save picture of screen as a file
  - Copy picture of screen to the clipboard
  - Save picture of selected area as a file
  - Copy picture of selected area to the clipboard

## Trackpad

### Point & Click

- uncheck all except: Point & Click - Secondary click (use Click in bottom right corner)
- Lightest Click
- Fastest Tracking speed

### Scroll & Zoom

- remove Scroll direction: Natural

### More Gestures

- Only Swipe between full-screen apps

## Sound

- Disable: Sound Effects -> Play user interface sound effects

## Touch ID

- Unlocking your Mac
- R-Ring / L-Ring / R-Index

## Accessibility

- Disable: Display -> Shake mouse pointer to locate





## First set of Apps

- Install Alfred
- Install 1Password
- Install iTerm2
- Install VSCode

Next step: Configure iTerm2

- Docker
- Slack
- SourceTree
- VSCode
- VLC
- Postman
- Github Desktop

## Chrome

- Enable: Warn Before Quitting
- Disable: Settings -> Offer to save passwords

## Alfred

- Enable: General -> Startup -> Launch Alfred at Login
- General -> Alfred Hotkey Alt + Space
- Appearance -> use theme Alfred macOS Dark
- Appearance -> Options
  - Hide hat on Alfred Window
  - Hide menu bar icon
  - Show Alfred on: active screen
