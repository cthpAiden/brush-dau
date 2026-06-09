# 🐾 Brush Đậu

A cute-but-scary cat-grooming game, inspired by the viral **Brush Jjaemu**, starring
**Đậu** the silver British Shorthair. Brush Đậu to earn points — but the moment he
snarls and lunges (the screen zooms into his open mouth + **FREEZE!**), stop brushing.
Keep going and he bites you → **YOU DIED**.

Made with plain HTML, CSS and JavaScript in a single file — no frameworks, no build step.

## Play
Open `index.html` in a browser, or visit the hosted link. Hold and drag (mouse or
finger) the comb across Đậu to brush. Freeze the instant he snarls.

## Features
- 🖌️ Brush to score, with floating heart & sparkle particles
- 😼 Random snarl with a Jjaemu-style **zoom into the mouth**; keep brushing → **YOU DIED**
- 🙀 **Fake-outs** — Đậu sometimes flinches/twitches *without* snarling, to bait you into freezing
- ❄️ Freeze-or-die timing that gets harder as your score climbs
- 🎉 Juicy feedback — the score pops, a confetti burst + chime celebrates every 50
  points, and the brush sound rises in pitch the longer your brushing streak lasts
- 🏆 **50 achievements** (score milestones, reflex streaks, grind goals) saved on your
  device, with an unlock toast + trophy panel and a **Reset progress** button
- 🎨 **6 background themes** — Cloud, Cozy Room, Cushion, Sunny Window, Lavender Dusk,
  Mint Garden (pick on the title screen; your choice is saved)
- 🏠 **Main menu** button to return to the title screen any time
- 🔊 Sound effects synthesised in-browser (no audio files), with a mute toggle
- 🥇 Best score saved on your device
- 📱 Works with mouse or finger (desktop + mobile)

## Controls
- **Hold & drag** — brush Đậu (each stroke scores ~1 point per 130px brushed)
- **Freeze** (stop moving / let go) the instant you see red / **FREEZE!**
- **🏠** top-right — back to main menu · **🔊** — mute · **🏆** — achievements

## How progress is saved
Achievements, stats, best score and chosen background live in your browser's
`localStorage` (per device, per browser). Use the **Reset progress** button inside the
Achievements panel to wipe it, or clear the site's data in your browser.

## Files
- `index.html` — the entire game (HTML + CSS + JS)
- `assets/Dau_calm.png` — calm Đậu (safe to brush)
- `assets/Dau_alerted.png` — snarling Đậu (FREEZE / bite)

Made with love. 💗
