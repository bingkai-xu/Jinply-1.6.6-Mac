# Jinply (简批) 1.6.6 · macOS (Universal: Apple Silicon M1–M4 & Intel)

## Installation

1. Double-click the zip to extract it and get `简批.app`
2. Drag `简批.app` into **Applications**
3. Double-click `简批` in Applications to launch

## "Cannot verify developer" on first launch

This app is not signed with an Apple Developer certificate, so the first launch will be blocked:

- Right-click `简批` → **Open** → click **Open** again in the dialog; or
- On macOS 15+: double-click once first, then go to **System Settings → Privacy & Security** and click **Open Anyway** at the bottom of the page.

You only need to do this once. If macOS says the app "is damaged and can't be opened", run this in Terminal:

```bash
xattr -cr /Applications/简批.app
```

## Interface

If Chrome / Edge / Brave is installed, Jinply opens in a standalone app window (no address bar); otherwise it opens in Safari. Closing the window quits the app (in a Chrome / Edge app window, press ⌘Q).

## Login

One-click login is available on the login page. Accounts: `admin` / `caiwu` / `zhuguan` / `laoban` / `yg01` — password is `123456` for all of them.

## Data

`~/Library/Application Support/JianPi/App/` — uninstalling the app does NOT delete your data.

## Logs

`~/Library/Application Support/JianPi/App/logs/JianPi.log`

## System requirements

macOS 11 or later.
