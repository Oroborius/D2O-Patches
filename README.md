# D2O QoL Patch

Client quality-of-life patches for vanilla Diablo II: Lord of Destruction 1.14d.

[Download v0.3.0](https://github.com/Oroborius/D2O-Patches/releases/download/v0.3.0/D2O-QoL-Patch-v0.3.0.zip)

Install by copying version.dll next to Game.exe in your vanilla Diablo II: Lord of Destruction 1.14d folder.

Uninstall by deleting version.dll.

Open D2O QoL in the bottom-right of the main menu. Use the checkboxes to turn patches on or off. The game saves your choices in D2O-QoL.ini right away. Most options take effect at once, for the next game you enter; options marked (restart) are used the next time you start the game.

The game checks for updates when the main menu opens (again after 15 minutes if you return to it). Clear the Auto-check updates checkbox to stop automatic checks. The Check updates button looks right now (once a minute at most). When an update is available the button becomes Update: click it to download a signed release. The game verifies the GitHub download and applies it the next time you start the game.

Get D2GL appears while D2GL is not installed. After you agree, it downloads the official D2GL v1.3.3 release (Bayaraa, GPL-3.0, https://github.com/bayaraa/d2gl), checks its SHA-256, and unpacks it next to Game.exe. Replaced files are kept as *.before-d2gl and the D2GL license is saved as D2GL-LICENSE.md. Restart the game to use it. Your choices carry over. New patches start on, and removed patches are dropped from the settings.

## Included features

- Auto-attack hostile players (hacked only) — Hold the selected skill on the nearest hostile player when the server allows it for your hacked character.
- Chat emoji — Show item, rune and skill icons and coloured badges in game chat when players type emoji codes.
- Lower CPU use — Reduces CPU use when the game is idle.
- Prevent stat bar crashes — Prevents a crash when a stat bar displays an unusually large value.
- Use D2GL renderer — Clear Use D2GL renderer and restart to use the stock windowed renderer when D2GL is installed.
- Disable Battle.net button — Disables the Battle.net entry on the main menu.
- Faster TCP/IP joins — Shortens the loading wait when joining a TCP/IP game.
- Prevent long item tooltip crashes — Prevents crashes when displaying unusually long item tooltips.
- Show high life and mana values — Displays accurate life and mana values above the usual limit in a compact vertical fraction.
- Reveal maps on private servers — Shows the automap when a compatible private server requests it.
- Mouse lock (Ctrl+L) — Press Ctrl+L to lock or release the mouse cursor inside the game window.
- Run multiple game windows — Allows more than one game window to run at once.
- Never overwrite my character save — Keeps your local character save unchanged during TCP/IP and single-player games.
- Life/mana % on orbs — Shows your life and mana as a percentage in gold text on the life and mana orbs.
- Long names over players — Shows full player names on compatible servers and, with the party patch, supports optional Discord account linking.
- Party list: scroll through every player — Adds scrolling to the party screen for larger groups.
- Prevent crashes in larger parties — Keeps the party screen stable when a host sends more than eight player records.
- Skip logos and intro — Skips the startup videos and opens the main menu.
