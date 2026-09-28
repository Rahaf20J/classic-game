# Pop the Balloons

## What it does

**Pop the Balloons** is a responsive two-player reflex game. Player 1 enters a name and plays one 60-second round, then Player 2 does the same. The player with the higher real score is the champion.

There is **no score target**. A player can keep popping beyond 20 balloons. A turn ends only when:

- the 60-second timer runs out;
- a balloon escapes; or
- the player clicks the open sky instead of a balloon.

Balloons begin with a fast 3-second rise time and become noticeably faster every five seconds. The fun, progressive challenge builds toward a 1.6-second late-round pace.

## How to run it

1. Download or clone this folder.
2. Double-click `index.html` in a modern browser.
3. Player 1 enters a name and starts. When their turn ends, Player 2 enters a name and plays.

No installation, account, server, internet connection, external library, or downloaded media is needed.

## How to play

- Tap or click balloons to pop them.
- Do **not** tap/click the open sky.
- On a keyboard, use `Tab` to focus the balloon, then press `Enter` or `Space` to pop it.
- The uncluttered game view shows the active player, score, timer, and one **Pause** button.
- **Pause** freezes the timer, balloon, and ambient music. Choose **Resume** to continue.
- The layout adapts to phones, tablets, desktops, and phone landscape mode with touch-friendly controls.

## Encouragement and sound

During a turn, temporary floating messages such as **Good job!**, **Great!**, and **Final stretch!** appear at timed milestones, play a soft chime, then fade away.

After a player starts, the game generates gentle ambient Web Audio music and a pop sound for each balloon. Audio pauses between turns and when the game is paused. If a browser blocks Web Audio, gameplay still works normally.

## Champion and privacy

After both turns, the results screen lists the two actual scores and shows:

`⭐ Champion: player name — score`

Equal scores produce co-champions. The browser stores only the highest completed score and its actual player name in local storage on this device. No player information leaves the browser.

Built with Claude Code during the KKU Claude Code hackathon.

Started on 2026-09-27
