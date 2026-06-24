# Cluster Map Status

Cluster Map Status by Stewart's IT Consulting is a multi-game server status tool that checks BattleMetrics and FiveM/Cfx.re server data, then posts clean status embeds to Discord using webhooks.

## What it does

- Tracks BattleMetrics servers.
- Tracks FiveM / Cfx.re servers.
- Tracks FiveM Direct IP:port servers.
- Supports multiple webhook profiles.
- Each profile can have its own webhook, server list, CSV log, message ID file, and embed settings.
- Posts Discord status embeds.
- Updates the same Discord message instead of spamming.
- Supports profile templates.
- Supports custom emoji/icon dropdowns.
- Supports custom Discord emoji formatting.
- Supports Live Preview to Discord.
- Supports app-side preview.
- Includes a Dashboard page.
- Includes countdown timer support.
- Includes Project Progress Summary page.
- Includes Help / Feedback and Donate pages.
- Includes an Updates page for checking GitHub releases.
- Includes a Data / History Folder setting to preserve logs after updates.

## Download

Use the latest release:

https://github.com/tstewa146-maker/ClusterMapStatus/releases/latest

## Update Checker

The app checks this file for updates:

https://raw.githubusercontent.com/tstewa146-maker/ClusterMapStatus/main/update.json

## Latest Version

Current release target: V4.4.6.3

## V4.4.6.3 Hotfix

Fixed:

- Dashboard crash caused by non-profile text values in settings.
- Dashboard now ignores bad/non-profile entries.
- Dashboard only loads real profile dictionaries.
- Server list and cached status loops are safer.

Includes:

- V4.4.6 Data / History Folder update.
- V4.4.6.1 dashboard border color fix.
- V4.4.6.2 dashboard profile startup fix.

## Recent Major Features

### V4.0

- Multi-webhook profiles.
- Each profile has its own webhook settings and server list.
- Separate CSV logs and message ID files per profile.

### V4.1

- Profile templates.
- Fetch Info from BattleMetrics.
- Test Selected Server.
- Embed color customization.
- Server notes.
- Offline / online / population alerts.
- Uptime tracking.
- Live Preview page.

### V4.2

- FiveM / Cfx.re support.
- Source types:
  - BattleMetrics
  - FiveM Cfx.re
  - FiveM Direct
- FiveM Cfx.re accepts a join code or cfx.re/join URL.
- FiveM Direct accepts host/IP:port.

### V4.3

- Custom emoji/icon dropdowns.
- Custom Discord emoji helper.
- Right-click copy/paste.
- Pinned Save Profile Settings button.

### V4.4

- Updates page.
- Check for Updates button.
- GitHub update.json support.
- Version comparison.
- Release notes display.
- Download/release link opening.

### V4.4.5

- Dashboard page.
- Stat cards.
- Compact live preview.
- Countdown timer.
- Project Progress Summary page.

### V4.4.6

- Data / History Folder setting.
- Default folder: `Documents/Cluster Map Status Data`.
- Logs and Discord message ID files can stay outside the EXE folder.
- Helps keep past logs after updates.

## Install

1. Download the latest EXE package ZIP from Releases.
2. Extract the ZIP.
3. Double-click `Cluster Map Status.exe`.
4. Keep `settings.json`, `logs`, and `message_ids` with the EXE.
5. Use the Data / History Folder setting if you want logs stored outside the EXE folder.

## Notes

- Do not delete `settings.json` unless you want to reset saved settings.
- Do not delete the `message_ids` folder unless you want Discord posts to be recreated instead of edited.
- Windows may warn about unsigned EXE files. This is normal for small custom apps unless they are code-signed.
