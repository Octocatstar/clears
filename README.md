# Clears

**Your brain knows the quest. Starting it is the boss fight.**

Clears is a gamified daily-living app for ADHD and other neurodivergent minds that freeze on cooking, cleaning, self-care, and life admin. Everyday tasks become small missions. You earn XP, keep streaks, and pick a soundtrack that lifts you up or calms you down so you can actually begin. Finish a quest, and progress turns into gift cards. Not badges. Real loot.

Less guilt. More clears. Play the day you already have to live.

This is a front-end product demo, not a medical device and not treatment for ADHD.

## Open the demo

1. Download or clone this repo.
2. Open `index.html` in a browser.
3. Optional: enable GitHub Pages on `main` / root, then share the live link.

Progress saves in your browser with `localStorage`.

## Why this shape

Ordinary to-do lists assume that knowing a task is enough to start it. For many ADHD brains, **starting** is the boss fight. Clears is built around that gap:

- One visible next action, not a wall of chores
- Tiny first steps that count as progress
- “Done enough” clears, so partial work still drops loot
- No overdue shame, no red punishment for a paused streak
- Mood and energy filters so the map matches the day you actually have
- Boost or calm audio so the environment helps you launch
- Gift-card loot so the reward is tangible, not another badge

## Product map

| Screen | What it does |
| --- | --- |
| Today | Mood, energy, streak, and a short quest board |
| Focus | One quest, one first step, a gentle timer, start/clear/pause |
| Sound | Boost or calm soundtrack, plus Spotify / Apple Music connect (demo) |
| Loot | XP and coins redeemable for AU gift cards |
| Guide | Freeze help, design principles, and a no-guilt reset |

## Design system

- Soft pastel pink and lavender, cream surfaces, large tap targets
- Fraunces for titles, Nunito for UI text
- Game language that stays human: quest, clear, loot, freeze, biome
- Australian loot set for a Sydney daily-living context: Woolworths, Coles, Kmart, Uber Eats, Spotify, Mecca

## Local demo limits

- Soundtrack is generated in the browser. Spotify and Apple Music are connection UI only.
- Gift-card redemption is simulated. No payment or partner APIs are wired yet.
- There is no account, cloud sync, or live AI backend in this version.

## Suggested next build

- Real Spotify / Apple Music session playback
- Cloud save and optional body-doubling rooms
- Partner gift-card API with proper KYC and fraud limits
- React Native or Flutter shell for App Store / Play
- Subscription for Plus soundtrack packs, without gating the core start tools

## License

MIT. Built as a concept demo for Clears.
