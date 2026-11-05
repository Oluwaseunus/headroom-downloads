# Release notes

## 0.5.0 · Build 9

Headroom 0.5.0, build 9, for Apple Silicon Macs running macOS 15 or later.

- A welcome guide on first launch walks through the optional permission and Open at Login, lets you try the ⌃⌥M shortcut or record your own, and, with the permission allowed, add per-app rules.
- Redesigned Settings, in a dark look that matches the welcome guide.
- Redesigned menu: choose when the menu bar hides in all apps, or, from a full-screen app, in that app.
- The shortcut now reverses what you see: a visible menu bar hides, and a hidden one comes back.
- App rules still win in full screen. Pressing the shortcut three times quickly there explains which rule is in control and where to change it.
- Shortcuts that use only ⌥ or ⌥⇧ are rejected with a clear message, since macOS 15 doesn't allow them.
- App and installer are notarized by Apple, with stapled tickets for offline verification.

Download `Headroom.dmg`, open it, and drag Headroom into Applications. Allow Device Control and Data Access (Accessibility on macOS 15 and 26) in Settings to use automatic full-screen app rules.

`SHA256SUMS.txt` contains the installer checksum.

## 0.4.0 · Build 8

Headroom 0.4.0, build 8, for Apple Silicon Macs running macOS 15 or later.

- New app icon.
- Refreshed installer window background.
- App and installer are notarized by Apple, with stapled tickets for offline verification.

Download `Headroom.dmg`, open it, and drag Headroom into Applications. Enable Accessibility access in Settings to use automatic fullscreen app rules.

`SHA256SUMS.txt` contains the installer checksum.

## 0.4.0 · Build 7

Headroom 0.4.0, build 7, for Apple Silicon Macs running macOS 15 or later.

- App and installer are notarized by Apple, with stapled tickets for offline verification.
- Includes per-app fullscreen menu bar rules, a configurable global keyboard shortcut, and native Settings.

Download `Headroom.dmg`, open it, and drag Headroom into Applications. Enable Accessibility access in Settings to use automatic fullscreen app rules.

`SHA256SUMS.txt` contains the installer checksum.

## 0.4.0 — Apple Silicon preview

Headroom 0.4.0 is an Apple Silicon preview for macOS 15 or later.

- Choose when the menu bar hides, with per-app fullscreen rules.
- Record a global keyboard shortcut to toggle menu bar visibility.
- Configure Headroom in its native Settings window, including optional Launch at Login.
- Command–Q in Settings quits Headroom; Command–W closes only Settings.

Download `Headroom.dmg`, open it, and drag Headroom into Applications.

The app, Settings companion, and DMG are Developer ID signed. This preview is not notarized, so macOS may show a security warning. Automatic fullscreen rules require Accessibility access. Live menu bar switching has been verified on macOS 27.2; compatibility with other macOS versions is still being tested.

`SHA256SUMS.txt` contains the installer checksum. Version 0.4.0, build 6.
