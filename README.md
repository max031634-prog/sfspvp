# Satisfaction PVP
# Satisfaction PvP

**See your rank, your Elo, and your progress at a glance — on every multiplayer server.**

Satisfaction PvP is a client-side Fabric mod for Minecraft 1.21.11 that turns your PvP matches into clear, readable information. It works on regular multiplayer servers, Realms, and LAN worlds without requiring anything installed on the server. Singleplayer is intentionally excluded.

---

## Features

### Tier Tags
* **Yourself:** Your own nametag and tab-list entry show your sword icon, Elo league (Rookie to Satisfaction Grandmaster), tier, and tier progress.
* **Opponents:** Players with a known leaderboard entry show their Elo league and tier only (no tier percentage) to keep tags compact and avoid presenting an estimate as exact progress.
* **Custom Font Rendering:** Uses a custom 9×9 sword glyph built directly into the mod's font so it stays crisp at every GUI scale.

### Live Combat HUD
* Displays your rank, Elo, streak, and progress toward the next league.
* Shows live accuracy, combo count, CPS, and performance score during a fight.
* Compact layout that can be repositioned with the mouse and scaled from 50% to 200%.
* Automatically displays trainer progress inside the HUD while a drill is active.

### Sparring Trainer
Six guided drills with a live coach, medals, personal bests, XP levels, and a final grade:

| Drill | What it trains |
| :--- | :--- |
| **Aim** | Crosshair control and hit consistency |
| **Crit** | Jump-hit timing |
| **W-Tap** | Sprint resets |
| **Spacing** | Keeping the correct distance |
| **Trade** | Clean 1:0 trades |
| **Timing** | Clicking inside the rhythm window |

### Opponent Check
After each round, the mod builds a local report containing:
* Estimated opponent skill, expected outcome, and Elo change
* CPS, hit rate, reach, sprint usage, and DPS
* A cheat-suspicion score based on observed patterns for you to review yourself

### Global Leaderboard
* Live in-game leaderboard displaying rank, player, Elo, win/loss record, and your own position.
* Cached locally so the HUD and opponent tags keep working between refreshes.

### Match History & Profile
* **Profile tab:** Shows your current league, Elo, streak, win/loss record, rating, best score, average damage, and last ten matches.
* **Check tab:** Keeps detailed post-match reports accessible anytime.

### Languages
Ships with **English (default)**, **German**, **Russian**, **French**, **Spanish**, **Turkish**, and **Chinese**. Switch instantly via the language button in the top-right corner of the menu. Missing translations fall back to English.

---

## Installation

1. Install **Fabric Loader 0.20.1** or newer for **Minecraft 1.21.11**.
2. Place **Fabric API** (`0.141.6+1.21.11` or newer) in your `mods` folder.
3. Place `satisfactionpvp-1.10.0.jar` in your `mods` folder.
4. Start the game and open the menu with your configured keybind or `/satpvp`.

> **Note:** This mod is client-side only; servers do not need to install it. The leaderboard and opponent data require the backend configured in `config/satisfactionpvp.json`. Without a connection, the local HUD and trainer still work offline.

---

## Notes & Fair Play

* Opponent tags only appear when that player's own client has uploaded a tier or rating to the leaderboard.
* The opponent check is a statistical estimate based on locally observed combat data. It is **not** an anti-cheat and must not be used as proof of cheating.
* **No cheat features or unfair advantages:** The mod only displays information that is already visible to your client.

---

## Compatibility

* **Minecraft:** `1.21.11`
* **Mod Loader:** Fabric Loader `0.20.1+`
* **Dependencies:** [Fabric API](https://modrinth.com/mod/fabric-api) (`0.141.6+1.21.11`+)
* **Environment:** Client-side only

---

*Satisfaction PvP — know where you stand.*
