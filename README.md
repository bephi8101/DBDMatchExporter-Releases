# Dead by Daylight Match Exporter

**Your Dead by Daylight match history – stored locally, preserved over time, and analyzed in detail.**

**DBD Match Exporter** is a free browser extension for Opera and other Chromium-based browsers.

The extension allows you to capture your personal match history from the official Dead by Daylight statistics website, store it locally, and explore detailed statistics about your matches.

All collected data is stored directly in your browser. No additional account or external server is required.

## Important: Match History Limitations

The official Dead by Daylight statistics website provides access to a limited match history:

- **Up to 30 recent matches**
- **Matches from approximately the last 90 days**

The DBD Match Exporter can only capture match data that is currently available through the official statistics website.

**It cannot retrieve older matches that are no longer available on the website.**

### Why Use DBD Match Exporter?

Unlike the limited history available on the official website, the extension allows you to build your own long-term match archive.

- Previously captured matches remain stored locally.
- Older matches are not automatically deleted.
- Your collection can grow beyond 30 matches.
- You can analyze your performance across longer periods.
- Regular updates help preserve matches before they disappear from the official website.

**Recommendation:** Update your match history regularly to avoid missing matches.

The extension cannot recover matches that were never captured and are no longer available from the official website.

## Features

### Match History
- Capture and store your Survivor and Killer matches locally
- Build a long-term archive beyond the official 30-match limit
- Preserve previously recorded matches
- Browse, search, and filter your match history
- View individual matches in the Match Explorer

### Detailed Statistics
- Survivor and Killer statistics
- Most frequently used perks
- Perk combinations and trends
- Character usage statistics
- Personal match performance analysis

### Anonymous Opponent Statistics
- Optionally collect selected match information about other players
- Analyze frequently used perks and characters
- No player names or personal player identifiers stored in the anonymized data
- Disabled by default and only enabled with your consent

### Backup and Restore
- Create complete local backups
- Verify and restore existing backups
- Preserve existing data when restoring backups
- Export and import match collections using JSON

### Privacy
- All data is stored locally in your browser
- No external database or cloud storage required
- No additional registration
- No automatic deletion of older matches
- Full control over your stored data

## Installation

Download the latest version from the **Releases** section of this repository.

1. Download the ZIP file for manual installation.
2. Extract the archive to a permanent folder.
3. Open your browser's extension management page.
4. Enable **Developer Mode**.
5. Select **Load unpacked** and choose the folder containing `manifest.json`.
6. Follow the built-in setup guide.

## How to Capture Your Matches

To successfully capture your match history, follow these steps in the correct order:

1. Open the [official Dead by Daylight statistics website](https://stats.deadbydaylight.com/) and sign in.
2. Do **not** open your match history yet.
3. Open the extension popup and click **Update Matches**.
4. Wait until the extension displays **Ready to Capture**.
5. Only then open your match history on the statistics website.

**Important:** Opening your match history before the extension is ready may prevent matches from being captured.

### Keep Your History Up to Date

Because the official website only provides a limited number of recent matches, updating regularly is essential.

For example:

- You play 20 matches and update the extension: those matches can be saved.
- You play another 20 matches and update again: the newly available matches can be added.
- Your local collection can now contain 40 matches, even though the official website only shows up to 30 at a time.

This example assumes all 40 matches were successfully captured across the two updates.

**The more regularly you update, the more complete your personal match archive can become.**

## Data Safety

Your match history is stored locally in your browser.

To protect your collection, we strongly recommend creating regular full backups and keeping them in a safe location.

Uninstalling the extension, clearing browser data, or switching browser profiles may result in data loss if you do not have a backup.

## Disclaimer

This is an independent fan-made project and is not affiliated with, endorsed by, or officially connected to Behaviour Interactive or Dead by Daylight.

The extension is provided free of charge.

This repository is used to distribute installation packages, release notes, and updates. The original development source code is not publicly available.
