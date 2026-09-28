# Pop the Balloons

## What it does

**Pop the Balloons** is a cheerful two-player browser game. Pop 20 face balloons before the 60-second timer ends. The balloons move faster every 10 seconds, so the last part of the round is extra zippy.

A balloon escaping or clicking the empty sky is a mistake: the same player immediately starts again from **0 points** with a fresh **60 seconds**.

## Who it is for

Anyone who wants a short, friendly reflex game—especially two players taking turns to beat the local high score.

## Features

- Sky-blue `#87CEEB` scene with animated CSS clouds and colorful balloon faces.
- Web Audio API pop sound on every successful pop (after a player action enables sound).
- Encouragement at 15 seconds (**Good job!**) and 30 seconds (**Great!**), plus **Congratulations!** for popping 20 balloons.
- A side **Pause game** button that keeps the exact score, timer, and balloon progress until resumed.
- A top leaderboard showing the active player, score, time, speed level, and `⭐` high-score holder.
- Player names and the high score stay in this browser's `localStorage` only; nothing is uploaded anywhere.
- Built-in made-up example data and a **Load example** button.
- Keyboard play: use `Tab` to focus the balloon, then press `Enter` or `Space` to pop it.

## How to run it

1. Download or clone this folder.
2. Double-click `index.html` to open it in a modern browser.
3. Type a player name and choose **Start game**.

No installation, account, server, internet connection, or external library is needed.

## How two players compete

1. Player one types a name and starts a turn.
2. When they finish, replace the name in the same box with player two’s name.
3. Choose **Next player** for a brand-new 60-second turn.
4. The `⭐` high score and player name update if somebody beats it.

## Demo speed / skip

For a fast one-minute demonstration, start a turn then choose **Demo speed / skip 15s**. Each click skips 15 seconds without adding points, so speed changes and motivational messages appear quickly. It does not create a win—the player still needs to pop 20 balloons.

## Try it with the sample data

`sample-data/data.js` contains only made-up names and a starter score. Choose **Load example** at any time to restore that sample high score in the current browser.

To clear your saved high score completely, clear the browser’s local storage/site data for this local page.

Built with Claude Code during the KKU Claude Code hackathon.

Started on 2026-09-27
