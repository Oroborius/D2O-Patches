## v0.2.4 — 2026-11-27

Added the ability for the patch to fetch external resources (such as d2gl downloads)

## v0.2.3 — 2026-11-27

- Added chat-emoji — Show item, rune and skill icons and coloured badges in game chat when players type emoji codes.
- Changed overhead-long-names — Shows full player names on compatible servers and, with the party patch, supports optional Discord account linking.

Emojis and fixed supporter names not rendering right in QoL patches.

## v0.2.2 — 2026-11-27

- Added d2gl-renderer — Clear Use D2GL renderer and restart to use the stock windowed renderer when D2GL is installed.
- Added mouse-lock — Press Ctrl+L to lock or release the mouse cursor inside the game window.
- Added no-character-save — Keeps your local character save unchanged during TCP/IP and single-player games.

D2GL support, will add a downloader later but you can load it up now if you want.
Mouse lock via Ctrl+L
And a toggleable "make your characters not save" button. In QoL patches.

Also makes QoL Patch text less wide, version stored inside.

## v0.2.1 — 2026-11-27

- Changed item-tooltip-overflow-fix — Prevents crashes when displaying unusually long item tooltips.

Fixes the hover crash entirely :)

## v0.2.0 — 2026-11-27

- Changed life-globe-true-values — Displays accurate life and mana values above the usual limit.
- Changed overhead-long-names — Shows full player names on compatible servers and, with the party patch, supports optional Discord account linking.

Fixes a crash. Also makes some server checks for authenticity purposes.

## v0.1.0 — 2026-11-27

- Added auto-target-hold — Hold the selected skill on the nearest hostile player when the server allows it for your hacked character.
- Added cpu-fix — Reduces CPU use when the game is idle.
- Added crash-guard-panel-bars — Prevents a crash when a stat bar displays an unusually large value.
- Added disable-bnet — Disables the Battle.net entry on the main menu.
- Added hyper-join — Shortens the loading wait when joining a TCP/IP game.
- Added item-tooltip-overflow-fix — Prevents crashes when displaying unusually long item tooltips.
- Added life-globe-true-values — Displays accurate life and mana values above the usual limit.
- Added map-reveal — Shows the automap when a compatible private server requests it.
- Added multi-instance — Allows more than one game window to run at once.
- Added overhead-long-names — Shows full player names on compatible servers and, with the party patch, supports optional Discord account linking.
- Added party-list-scroll — Adds scrolling to the party screen for larger groups.
- Added party-list-unlimited — Keeps the party screen stable when a host sends more than eight player records.
- Added skip-intro — Skips the startup videos and opens the main menu.

First public release of the D2O QoL patch.

- New D2O QoL button on the main menu (bottom right): tick or untick any patch,
  and get future updates in one click. Updates are signed and apply on the next start.
  You can turn update checks off in the same panel.
- Auto-target (G / Shift+G) works for hacked characters only.
- Includes the item tooltip crash fix, true life/mana on the globes, long names,
  party list scrolling, the 8+ player party crash fix and more. See README.txt for the full list.

Install: put version.dll next to Game.exe in a vanilla 1.14d folder.
Uninstall: delete version.dll.
Older test builds of the patch that include auto-target are no longer allowed on the server. Please update.

