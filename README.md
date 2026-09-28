# Pop the Balloons

## What it does

**Pop the Balloons** is a simple two-player reflex game. Player 1 enters their name and gets one 60-second turn. Then Player 2 enters their name and gets one turn. The game compares their real scores and clearly announces the champion.

The balloons speed up every 10 seconds. A balloon escape, a click on the empty sky, or time running out ends that player’s turn immediately.

## How to run it

1. Download or clone this folder.
2. Double-click `index.html` in a modern browser.
3. Player 1 enters a name and starts. After that turn, Player 2 enters a name and plays.

No installation, account, server, internet connection, external library, or downloaded audio file is needed.

## How to play

- Pop balloons by clicking them.
- Do **not** click the empty sky.
- Use `Tab` to focus a balloon, then `Enter` or `Space` to pop it with a keyboard.
- The clean game screen shows only the active player, their score, the timer, and **Pause**.
- Pause keeps the current score, timer, and balloon progress. Choose **Resume** to continue.

## Champion and privacy

At the end of Player 2’s turn, the results screen shows both real scores and:

`⭐ Champion: player name — score`

If both players earn the same score, they are shown as co-champions. The browser keeps only the all-time high score and its actual player name in local storage on this device. No names or scores are sent anywhere.

## Sound

After a player starts a turn, the game uses Web Audio API to create soft background music and balloon-pop effects. The music pauses with the game and stops between turns and after the final result. If a browser blocks audio, the game still works normally.

Built with Claude Code during the KKU Claude Code hackathon.

Started on 2026-09-27
