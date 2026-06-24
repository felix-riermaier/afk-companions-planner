# AFK Companions Planner

A single-file, dependency-free web tool for **[AFK Arena: Companions](https://afkcompanions.com/)**
that helps you decide which heroes to **summon, ascend, and upgrade SI** on next, based on a
community tier list.

**▶ Open it:** **<https://felix-riermaier.github.io/afk-companions-planner/>**

## What it does

- Track your roster: ascension tier, SI level, banked Elite copies per hero, and your
  **Dimensional Spirits** pool.
- Manage it in a **searchable, faction-filterable** hero list: tap a hero to set its state, or
  use **Bulk mode** to step through many heroes one at a time for fast setup.
- See an **account summary** at a glance: heroes owned out of the total, total Elite copies and
  Dimensional Spirits invested, and how your roster breaks down by SI level and investment band.
- Get prioritized recommendations: who to **summon**, who's **ready to ascend**, your
  **stargazer** priority, **Dimensional** spirit investment, and which **SI** upgrades to chase.
- On **Recommendations**, tap any hero for a detail card: its Minimum / Optimal / Competitive
  breakpoints, the copies (E) or Dimensional Spirits (S) still needed for each, and a link to its guide.
- See when your banked copies (or Dimensional Spirits) are enough to **ascend** a hero to its next
  breakpoint, and apply it in one tap, in the hero's edit sheet and on Recommendations.
- **Hide** specific Dimensional heroes you can't obtain from Recommendations and Bulk mode, while
  keeping them on your roster.
- Use the **Tools** tab for calculators: a Realm of Shadows (Mythic Gate) Blessed Flame planner
  (the stamina, wait time, or Army Units to your next stopping point), plus Ascension and
  Signature Item cost references.
- Check the in-app **Changelog** (tap the date in the header, or the footer link) to see what
  changed, with an option to hide routine tier-list updates.
- Sort recommendations by Overall Score or any of the 8 game modes.
- Set per-faction wishlists and a stargazer target.
- Export / import your roster as plain text (back it up or move it between devices).

## Privacy & how it works

- **100% local.** No accounts, no servers, no network calls, no analytics. Everything runs
  in your browser and your roster is stored only in your browser's `localStorage`.
- It's a single self-contained HTML file with inline styles and vanilla JS, no dependencies.
  You can download `index.html` and open it directly from disk; it works offline.
- Mobile-first (it's mostly used on a phone).

## Usage

1. Open the app. The roster starts empty (every hero "not owned").
2. On the **Roster** tab, tap a hero to set its ascension, SI, and spare Elite copies; use the
   search box and faction filters to find heroes, or **Bulk mode** to step through many at once.
   Set your stargazer target, wishlists, and Dimensional Spirits in the **Wishlist / Dimensional
   Spirits** section.
3. Check the **Recommendations** tab for what to invest in next; tap any hero for its
   breakpoints, costs, and guide.
4. The **Tools** tab has calculators for the Realm of Shadows mode and for ascension / Signature
   Item costs.
5. Use **Export** to save a text backup; **Import** to restore it later.

## Credits

Tier data is transcribed from the community tier list by **SaiLus**
(<https://afk-web.onrender.com/tier-list>). All hero/game content belongs to Lilith Games.
This is an unofficial fan-made tool.
