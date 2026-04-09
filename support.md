# Support — Tic-Tac-Toe

**Developer:** Thia Solution LLC
**Contact:** thiasolutionsllc@gmail.com
**Platform:** iOS 17.0+
**Last Updated:** April 9, 2026

---

## Overview

Tic-Tac-Toe is a real-time online multiplayer game for two players, powered by Apple Game Center. Players are matched automatically and take turns placing X or O on a 3×3 board. The first to complete a row, column, or diagonal wins.

---

## Getting Started

### Requirements
- iPhone or iPad running iOS 17.0 or later
- An Apple ID with Game Center enabled
- An active internet connection (Wi-Fi or cellular)

### How to Sign In to Game Center
1. Open **iOS Settings**
2. Tap your name at the top → **Game Center**
3. Toggle Game Center **on** and sign in with your Apple ID
4. Return to Tic-Tac-Toe and tap **Play Online**

---

## How to Play

1. **Find a Match** — tap **Play Online** on the Home screen. The app searches automatically for an available opponent. Matchmaking takes up to 2 minutes.
2. **Take Your Turn** — when it is your turn, tap any empty cell to place your symbol (X or O). The status bar at the top shows whose turn it is and the time remaining.
3. **Turn Timer** — each player has 15, 30, or 60 seconds per turn (configurable in Settings). Missing three turns in a row forfeits the game.
4. **Winning** — three of your symbols in a row (horizontal, vertical, or diagonal) wins the game.
5. **Draw** — if all nine cells are filled with no winner, the game is a draw.
6. **Rematch** — after a game ends, either player can request a rematch. Both players must agree within 15 seconds.

---

## Frequently Asked Questions

### Why can't I find a match?
- Ensure Game Center is enabled in iOS Settings and you are signed in.
- Check your internet connection.
- If no opponent is found within 2 minutes, a timeout screen appears — tap **Try Again** to search again.
- Game Center matchmaking requires at least one other player to be searching at the same time.

### The game says "Connecting…" and nothing happens — what do I do?
- This means the match is starting and the game is assigning symbols (X or O). It resolves within a few seconds once both players are connected. If it persists, forfeit and start a new match.

### My opponent disconnected — what happens?
- The game waits up to 10 seconds silently for a quick reconnect.
- After 10 seconds, a countdown begins. If your opponent does not reconnect within 30 seconds, the game is awarded to you.
- Tap **Wait Longer** to extend the wait window if needed.

### I missed my turn — what happens?
- Missing a turn counts as one strike. Three strikes in total forfeits the game automatically.
- The turn is passed to your opponent after each missed turn.

### Can I play against a friend specifically?
- The current version uses automatic matchmaking via Game Center. Friend-specific invitations are not supported yet.

### Does the app work on iPad?
- Yes. The app supports iPhone and iPad on iOS 17.0 and later.

### Does the app work offline?
- No. An internet connection and Game Center sign-in are required for multiplayer gameplay.

### Is there a single-player or AI mode?
- Not in the current version. The app is multiplayer-only.

### How do I change the turn timer?
- Open the **gear icon** on the Home screen → **Settings** → **Gameplay** → select 15s, 30s, or 60s.

### How do I turn off sounds or haptics?
- Open **Settings** → toggle **Sound Effects** or **Haptic Feedback** off.

### How do I turn off notifications?
- Go to **iOS Settings → Notifications → Tic-Tac-Toe** and disable notifications there.
- Alternatively, deny the notification permission prompt when it appears after your first match.

### The app is not fitting my screen properly — what do I do?
- Ensure your device is running iOS 17.0 or later.
- Try force-quitting the app and reopening it: swipe up from the bottom of the screen (or double-press the Home button) and swipe the app away, then reopen it.

---

## Known Limitations

| Limitation | Detail |
|---|---|
| Multiplayer only | No single-player or offline AI mode |
| Auto-matchmaking only | Cannot invite a specific friend directly |
| Game Center required | Apple ID and Game Center sign-in are mandatory |
| Physical device required | Game Center multiplayer does not function in the iOS Simulator |

---

## App Review Notes (for Apple Reviewers)

**To test the app:**
1. Two physical iOS devices are required. Game Center does not support real multiplayer in the iOS Simulator.
2. Sign into separate Game Center sandbox accounts on each device.
3. On both devices, open the app and tap **Play Online**. Matchmaking completes within 10–15 seconds when both devices search simultaneously.
4. Once matched, gameplay, timer, forfeit, disconnect handling, and rematch can all be tested.

**Credentials / demo account:** No account credentials are required beyond a Game Center sandbox account. Game Center authentication is handled entirely by Apple.

**Settings:** Tap the **gear icon** on the Home screen to access sound, haptics, timer, privacy policy, and support options.

**Network entitlement:** The app uses Game Center relay servers exclusively. No custom backend, API keys, or server credentials are needed.

---

## Privacy

This app does not collect, store, or transmit any personal data. Multiplayer is handled entirely through Apple Game Center. For full details, see the [Privacy Policy](PRIVACY_POLICY.md).

---

## Contact & Support

For bug reports, questions, or feedback:

**Email:** thiasolutionsllc@gmail.com

Response time: within 2 business days.

---

*Tic-Tac-Toe is developed by Swathi Nagireddy. All multiplayer infrastructure is provided by Apple Game Center.*
