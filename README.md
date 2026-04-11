# ◈ Global War Room

> *"Once a Trader — Always a Trader."*

A classified trader discipline system. Not a dashboard. Not a journal. A war room — built for those who've seen the exit and refuse to go back.

**Live → [farman024.github.io/Global-War-Room](https://farman024.github.io/Global-War-Room/)**

---

## What Is This

The Global War Room is a daily check-in system for serious traders. It enforces discipline before you touch the terminal, tracks your streak in real-time alongside other traders worldwide, and reminds you why you started.

The math is simple:

```
9 HOURS OF LABOR  →  $25
10 MINUTES ON GOLD  →  $100

THE MATH DOESN'T LIE.
```

---

## Features

### ⚡ Elite Trader Gate
- Entry protocol that runs before you access the war room
- Forces acknowledgment of the 3-win streak trap
- Greed detection — access denied if the wrong choice is made
- The 5 Laws of the War Room — must be acknowledged daily

### 🔥 War Room Streak
- Personal discipline streak counter
- Total visits tracked
- Best streak on record
- Show up every day. That's the only law.

### 🌍 Traders Locked In — Live Count
- Real-time global check-in counter powered by Supabase
- See how many traders are locked in today worldwide
- [LOCK IN] button — marks your presence in the war room

### ◈ Session Sentinel
- Live London + New York session tracker
- Shows open/closed status based on UTC time
- Highlights the London × NY overlap — prime hunting window

### ◈ Freedom Math
- Enter your 9-to-5 daily wage
- Enter your gold lot size
- Calculates pips needed + estimated minutes in market
- Generates a **Freedom Receipt** — screenshot and share

### ◈ Freedom Receipt
- Official receipt showing profit vs 9-to-5 equivalent
- Time reclaimed displayed
- Built to be screenshotted and shared

### ◈ For The Severed
- A message to send to traders still stuck in the 9-to-5
- Reintegration protocol — wake up your network

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML + CSS + JavaScript |
| Database | Supabase (live lock-in counter) |
| Deployment | GitHub Pages |
| Audio | Web Audio API |
| Real-time | Supabase realtime subscriptions |

---

## Supabase Integration

The live lock-in counter is powered by Supabase. Each time a trader hits [LOCK IN], the count updates globally in real-time across all users.

```js
// Lock-in counter reads/writes to Supabase
// Table: war_room_checkins
// Column: date, count
```

---

## Data Tracked Locally

```json
{
  "streak": 7,
  "totalVisits": 23,
  "bestStreak": 12,
  "lastCheckIn": "2026-04-11"
}
```

---

## The 5 Laws of the War Room

Classified. Open the war room to find out.

---

## Roadmap

- [ ] Auth — personal accounts per trader
- [ ] Leaderboard — top streaks globally
- [ ] Trade session alerts (push notifications)
- [ ] Weekly discipline report
- [ ] Mobile PWA install

---

## Built By

**Farman J** — AI Generalist · Builder · Trader

> Building tools that reflect values, not just function.

- 🌐 [Portfolio](https://farman024.github.io/Farman-J)
- 🐦 [@Farman__24__](https://twitter.com/Farman__24__)

---

*Part of the **Falcon's Hunt** ecosystem — 11 live projects built from a smartphone.*
