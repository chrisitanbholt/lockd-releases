# lockd – Privacy Policy

Last updated: 11 November 2026

lockd is a free desktop companion app for the game Deadlock. It shows public match statistics in an overlay. lockd has no accounts and no servers of its own, and it does not sell, share or collect your personal data.

## What lockd reads on your PC

- **Deadlock's console log** (`console.log`, written by the game when it is started with `-condebug`). lockd reads the match ID, your own in-game name and your Steam account ID from it. This stays on your PC.
- **The top of your screen, at the start of a match.** A few pictures of Deadlock's top bar are taken to recognise which heroes are in the match. When you spawn in a match, a picture of your own item panel (the bottom left corner) is taken to see which items you have. The pictures are only kept in memory while they are being checked. They are never saved or sent anywhere.
- **Steam's local settings for Deadlock.** To make the game write its console log, lockd adds `-condebug` to Deadlock's launch options in Steam's local configuration file. It keeps a backup and leaves your other options as they are. lockd never reads or changes the game's memory or files, and it never sends input to the game.

## What lockd sends over the internet

- **deadlock-api.com** (a public statistics service for Deadlock): lockd asks it for match and player statistics. These requests contain the Steam account IDs and match IDs it is looking up, including your own. The answers are public match data. deadlock-api.com's own terms and privacy policy apply to these requests.
- **Valve's match broadcast** (through deadlock-api.com's relay): for the match you are in, lockd reads the players' names, Steam IDs, teams and heroes – the same information the in-game scoreboard shows. It also reads your own items and abilities for the Build tab.
- **Updates:** the version from lockd.gg checks GitHub (github.com/chrisitanbholt/lockd-releases) for new versions. The Microsoft Store version is updated by the Store.

## What lockd keeps on your PC

Your settings and a diagnostic log (`lockd.log`) are stored in the app's own folder on your PC. They are not sent anywhere. Uninstalling the Microsoft Store version removes them; for the version from lockd.gg you can delete the folder `%APPDATA%\lockd` after uninstalling.

## Children

lockd is not directed at children under 13 and does not knowingly collect information from them.

## Changes and contact

If this policy changes, the new version is published here with a new date. Questions: open an issue at https://github.com/chrisitanbholt/lockd-releases/issues.
