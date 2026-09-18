# Clears

**Your brain knows the quest. Starting it is the boss fight.**

Clears is a gamified daily-living app for ADHD and other neurodivergent minds that freeze on cooking, cleaning, self-care, and life admin. Everyday tasks become small missions. You get XP, streaks, and a soundtrack that lifts you up or calms you down so you can actually begin. Finish a quest, and progress turns into gift cards. Not badges. Real loot.

Less guilt. More clears. Play the day you already have to live.

Open the live demo: [index.html](index.html) — or use GitHub Pages after you enable it in **Settings → Pages → Deploy from branch → main**.

## Why this exists

Ordinary to-do lists assume that knowing a task is enough to start it. For many ADHD and neurodivergent people, **starting** is the boss fight. Clears is built around launch, not shame:

- One main quest, not a wall of overdue items
- A tiny first step instead of the whole mountain
- A 2-minute begin ritual with optional body-doubling
- Boost or calm soundtrack matched to mood and biome
- Park, skip, or re-enter without a fail state
- XP and streaks for momentum, gift cards for real-world loot

This is not a treatment, diagnosis, or cure. It is a daily-living game for brains that need smaller missions, faster feedback, and a reward that shows up in the real world.

## How to run

1. Clone the repo or download `index.html`.
2. Open `index.html` in any modern browser (Chrome, Safari, Edge, Firefox).
3. Add a quest, pick a soundtrack, hit **Start the boss fight**.
4. Progress saves in this browser via `localStorage`.

No build step. No login. No install required for the demo.

```bash
git clone https://github.com/Octocatstar/clears.git
open index.html
```

## What you can play today

| Screen | What it does |
| --- | --- |
| Onboarding | Pick freeze zones, music style, and a first name |
| Today | Energy check-in, one recommended quest, 2-minute start |
| Quests | Cooking, cleaning, self-care, life admin, plus a brain dump |
| Active quest | First step, next steps, park/re-enter, soundtrack |
| Sound | Boost vs calm mixes, biome, Spotify / Apple Music connect UI |
| Loot | Exchange coins for AU gift cards (demo redemption) |
| You | Streak, XP, cloud-sync note, Free / Plus / Studio plans |

## Design principles

1. **Start smaller than the task.** The first step should be doable in under two minutes.
2. **Never punish freeze.** Parking a quest is a valid move. There is no overdue pile of shame.
3. **Limit the field of view.** Today shows one main quest and a few side quests, not everything you have ever postponed.
4. **Sound is a tool, not decoration.** Boost for launch, calm for overwhelm, mute always one tap away.
5. **Loot has to be real.** Stats exist to become gift cards, not only badges.
6. **Soft on the eyes.** Pastel pink and lavender, large tap targets, reduced-motion support.

## Product map

```
Today → pick energy → recommended quest
     → first step + soundtrack
     → 2-minute boss fight
     → clear → XP + loot coins → gift cards
```

**Free** — today view, quests, local save, starter soundtrack.  
**Plus** — cloud sync, extra loot multipliers, AI breakdowns.  
**Studio** — household co-op, richer music control, higher gift-card tiers.

In this demo, Plus/Studio are product UI only. Gift-card redemption is simulated. Spotify and Apple Music buttons are connection shells until API keys are added.

## Aesthetic

- Palette: cream `#FFF8F4`, bloom pink `#E89BB5`, lilac `#9A7BB8`, ink `#3A2F45`
- Type: [Fraunces](https://fonts.google.com/specimen/Fraunces) for voice, [Nunito](https://fonts.google.com/specimen/Nunito) for UI
- Motion: soft bloom on clear, no streak-break explosions
- Voice: game-lite, human, never “try harder”

## Built for

Adults in Australia (and elsewhere) who can plan a day on paper and still not launch it. Copy, gift-card brands, and examples lean Sydney / everyday AU life: kitchen reset, washing, Medicare mail, a shower that actually happens.

## Next builds

- Real Spotify and Apple Music OAuth
- Cloud save (the Plus promise)
- Native iOS / Android shell
- Actual gift-card fulfilment (legal, tax, and partner APIs)
- Optional body-doubling rooms
- Recurring quests that reset without guilt

## License

MIT. See [LICENSE](LICENSE).
