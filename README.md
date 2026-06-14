# AFK Companions Planner

A single-file, dependency-free web tool for **[AFK Arena: Companions](https://afkcompanions.com/)**
that helps you decide which heroes to **summon, ascend, and upgrade SI** on next, based on a
community tier list.

**▶ Open it:** **<https://felix-riermaier.github.io/afk-companions-planner/>**

## What it does

- Track your roster — ascension tier, SI level, and banked Elite copies per hero.
- Get prioritized recommendations: who to **summon**, who's **ready to ascend**, your
  **stargazer** priority, and which **SI** upgrades to chase.
- Sort recommendations by Overall Score or any of the 8 game modes.
- Set per-faction wishlists and a stargazer target.
- Export / import your roster as plain text (back it up or move it between devices).

## Privacy & how it works

- **100% local.** No accounts, no servers, no network calls, no analytics. Everything runs
  in your browser and your roster is stored only in your browser's `localStorage`.
- It's a single self-contained HTML file — inline styles and vanilla JS, no dependencies.
  You can download `index.html` and open it directly from disk; it works offline.
- Mobile-first (it's mostly used on a phone).

## Usage

1. Open the app. The roster starts empty (every hero "not owned").
2. On the **Roster** tab, set each hero you own (ascension, SI, spare Elite copies).
3. Check the **Recommendations** tab for what to invest in next.
4. Use **Export** to save a text backup; **Import** to restore it later.

## Credits

Tier data is transcribed from the community tier list by **SaiLus**
(<https://afk-web.onrender.com/tier-list>). All hero/game content belongs to Lilith Games.
This is an unofficial fan-made tool.
