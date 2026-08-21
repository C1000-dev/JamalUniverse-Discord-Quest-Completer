<div align="center">

<img src="https://img.shields.io/badge/Jamal_Universe-Discord_Quest_Completer-gold?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d0d0d&color=ffd700" alt="Jamal Universe"/>

<h1>Jamal Universe</h1>
<h3>Discord Quest Completer — Automate all your Discord Quests instantly</h3>

<p>
  <img src="https://img.shields.io/badge/Version-v3.9-ffd700?style=flat-square&labelColor=111"/>
  <img src="https://img.shields.io/badge/Platform-Discord_Desktop-5865F2?style=flat-square&logo=discord&logoColor=white&labelColor=111"/>
  <img src="https://img.shields.io/badge/Quests-VIDEO_%7C_GAME_%7C_ACTIVITY-3ba55c?style=flat-square&labelColor=111"/>
  <img src="https://img.shields.io/badge/License-MIT-888?style=flat-square&labelColor=111"/>
</p>

<p>
  <a href="https://t.me/JamalUniverse"><img src="https://img.shields.io/badge/Telegram-Join_Community-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
</p>

---

</div>

## 📋 What is Jamal Universe?

**Jamal Universe** is a lightweight browser console script that automatically completes Discord Quests for you — VIDEO, GAME, and ACTIVITY types — while you do other things. Simply paste it into Discord's DevTools console, pick your quests, and let it run.

> ⚠️ **Use at your own risk.** Automating Discord quests may violate Discord's Terms of Service. This project is for educational purposes only.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🎮 **Auto Quest Detection** | Automatically finds all available quests on your account |
| ⚡ **VIDEO / GAME / ACTIVITY** | Supports all major quest types |
| ⏸ **Pause & Resume** | Pause anytime, re-select quests, resume without losing progress |
| 📋 **Quest History** | Track every completed quest with rewards and time saved |
| ⬡ **Reward Tracking** | See total orbs, decorations and in-game rewards earned |
| 🔊 **Click Sounds** | Satisfying click feedback on every button |
| ✨ **Gold Sparkle UI** | Animated gold title with polished dark interface |
| 🕐 **Minutes Display** | Shows `6m 42s (402 / 900s)` — no more raw seconds |
| 🔄 **Sequential Mode** | Runs quests one at a time in the order you pick them |
| 📢 **Claim Rewards** | Auto-claim or manual claim button built in |
| 🔒 **Safe Shutdown** | Clean ✕ close, ⏸ pause, and `HIDE` with keyboard shortcut |

---

## 🚀 How to Use

### Step 1 — Open Discord Desktop
> Must be the **official Discord Desktop app** (not browser, not Vesktop) for GAME quests to work.

### Step 2 — Open DevTools
Press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Option+I` (Mac) to open the Developer Tools.

### Step 3 — Go to the Console tab
Click the **Console** tab at the top of the DevTools panel.

### Step 4 — Navigate to Quest Home
Go to [discord.com/quest-home](https://discord.com/quest-home) or open the Quests page inside Discord.

### Step 5 — Paste the Script
Copy the contents of [`3ptp_universe_V39.js`](./3ptp_universe_V39.js), paste it into the console, and press **Enter**.

### Step 6 — Pick Your Quests & Start
A panel will appear in the top-right corner. Select your quests and click **▶ START**.

---

## 🖥 Interface Overview

```
┌─────────────────────────────────────────────────┐
│  ✨ Jamal Universe  v3.9  📋  ⏸ PAUSE  HIDE ⚙ ✕ │
├─────────────────────────────────────────────────┤
│                                                 │
│  ● RUNNING   Genshin Impact Version 7.0         │
│              6m 42s  (402 / 900s)               │
│                                                 │
│  ○ QUEUE     EVE Online                         │
│              0s  (0 / 900s)                     │
│                                                 │
├─────────────────────────────────────────────────┤
│  Console log...                                 │
└─────────────────────────────────────────────────┘
```

- **▶ START** — Opens quest picker and begins automation
- **⏸ PAUSE** — Pauses current run, lets you re-select quests
- **📋** — Opens Quest History overlay (shows rewards + orbs + time saved)
- **HIDE** — Hides panel (`Shift + .` to show again)
- **⚙** — Settings (auto-enroll, auto-claim, sound, random delay)
- **✕** — Closes script completely

---

## ⚙️ Settings

| Option | Default | Description |
|--------|---------|-------------|
| Auto-enroll | ✅ On | Automatically enrolls in quests before running |
| Auto-claim | ❌ Off | Automatically claims rewards when done |
| Sound on completion | ❌ Off | Plays a sound when a quest finishes |
| Random delay | ❌ Off | Adds 1–30 min random gap between cycles (anti-detection) |

---

## 📋 Quest History

Press the **📋 clock icon** in the header to open your session history:

- Every completed quest with **reward name**, **time taken**, and **timestamp**
- **Totals row**: how many orbs earned, decorations, in-game rewards, and total time saved
- Stays open over the quest panel without breaking anything — close with **✕ Close**

---

## 📦 Quest Types Supported

| Type | Works on Desktop | Works on Web/Vesktop |
|------|:---:|:---:|
| 🎬 VIDEO | ✅ | ✅ |
| 🎮 GAME (PLAY_ON_DESKTOP) | ✅ | ❌ |
| 🎯 ACTIVITY | ✅ | ✅ |
| 🏆 ACHIEVEMENT | ✅ | ✅ |

> **Note:** `PLAY_ON_DESKTOP` quests require the **official Discord Desktop app**. Discord's servers enforce this at the session level — it cannot be bypassed on Vesktop or browser Discord.

---

## 🔄 Changelog

### v3.9 — Latest
- Fixed: Duplicate quest completions in history panel
- Fixed: History overlay now mounts inside body only — header fully interactive
- Fixed: Closing history restores quest cards properly
- Added: ✕ Close button inside history overlay
- Fixed: Telegram tooltip shows link instead of "Coming Soon"
- Fixed: Click sounds on all buttons including checkboxes and toggles

### v3.5–v3.8
- Quest History panel with overlay approach
- Reward type tracking (orbs / decorations / in-game)
- Totals: orbs collected, time saved
- Clock icon for history, Telegram link in header

### v3.0–v3.4
- Full rebrand to **Jamal Universe**
- Sequential quest mode (one at a time, in order)
- Gold sparkle animation on title
- Click sounds on all buttons
- Minutes-primary display: `6m 42s (402 / 900s)`
- Quest duration shown in picker
- STARTING pulse animation before first heartbeat
- Pause → re-select → resume without losing progress

### v2.x
- PLAY_ON_DESKTOP investigation (confirmed Discord server-side block)
- WebSocket IDENTIFY patching, RPC session spoofing
- `detectType()` bug fix — PLAY_ACTIVITY was routing to GAME handler
- Sealed metadata in enrollment and claim requests
- Manual 30s heartbeat fallback

### v1.x
- Initial Vesktop/Vencord support
- FetchPatch, GatewayHelper, GameRPC modules
- Basic VIDEO, ACTIVITY, GAME support

---

## 🛠 Technical Details

The script patches Discord's internal webpack modules at runtime:

- **RunningGameStore** — injects a fake running game process for GAME quests
- **QuestStore** — reads available and enrolled quests
- **FluxDispatcher** — subscribes to heartbeat success events
- **RestAPI** — sends heartbeats and video progress to Discord's API
- **Traffic queue** — rate-limited request queue with retry logic

GAME quests on Desktop work by:
1. Patching the store so Discord sees a fake game running
2. Sending manual HTTP heartbeats every 30 seconds
3. Listening for Discord's own `QUESTS_SEND_HEARTBEAT_SUCCESS` events

---

## ❓ FAQ

**Q: Does this work on Vesktop?**
> VIDEO and ACTIVITY quests work. GAME (PLAY_ON_DESKTOP) quests are blocked by Discord's server regardless of any spoofing.

**Q: Will my account get banned?**
> Unknown. Discord can detect automation. Use the Random Delay option to reduce risk. Use at your own risk.

**Q: Why do quests show "STARTING..."?**
> The script waits for the first server heartbeat before showing real progress. This prevents the fake 0→reset→real jump.

**Q: Can I run multiple quests at once?**
> The script runs quests sequentially (one at a time) to avoid conflicts.

**Q: The script said "No quests found"?**
> Navigate to [discord.com/quest-home](https://discord.com/quest-home) first, then paste the script.

---

## 📢 Community

<div align="center">
  <a href="https://t.me/JamalUniverse">
    <img src="https://img.shields.io/badge/Join_Telegram-JamalUniverse-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
</div>

---

<div align="center">
  <sub>Made with ❤️ by the Jamal Universe team &nbsp;|&nbsp; Educational purposes only</sub>
</div>
