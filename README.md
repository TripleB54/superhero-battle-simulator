# Stark Multiverse Battle Simulator

Open `index.html` in a modern desktop browser or publish it with GitHub Pages. The restored classic Stark HUD is built entirely into the HTML and does not require a separate image asset.

## Advanced draft modes

- **Ban & Draft:** Generate 10, 20, or 30 fighters, or use Free Select. Each team bans one fighter before drafting.
- **Universe Clash:** Generate separate pools of 10, 20, or 30 fighters per universe. The team that wins first pick drafts Marvel; the other team drafts DC.
- **Tier Draft:** Select any combination of Street, Enhanced, Heavy, Mystic, and Cosmic, then use Generate 10, 20, 30, or Free Select. Draft requirements rotate evenly through the selected tiers. In a 5v5 with all five tiers, every team drafts exactly one fighter from each tier.
- **Captain Draft:** Each team chooses a captain first. The remaining pool options—Generate 10, 20, 30, or Free Select—appear only after all captains are locked.
- **Full Roster / Free Select:** Shows every fighter allowed by the main universe and tier filters.
- **Prep Time:** Uses Generate 10, 20, 30, or Free Select. Every fighter receives a preparation rating based on intelligence, battle strategy, tactical role, planning/tool use, adaptability, and combat behavior. Preparation ratings affect the battle simulation; Batman is calibrated as the top preparation specialist.

The simulator contains 175 fighters, two- and three-player support, team sizes from 1–5, Standard/Amped/Mixed versions, character dossiers, battle narration, health tracking, and tactical-map playback.

## Persistent roster editing

- Changing Alpha, Omega, or Sigma's team size preserves every pick that still fits.
- Reducing a team returns only that team's excess fighters to the selectable pool.
- Switching between two and three players preserves Alpha and Omega. Removing the third player returns Sigma's fighters to the pool.
- The full roster is cleared only by the **Reset** button or by intentionally changing to a different game mode.

## Power Passport database

- Marvel fighters use the cream-paper **Concept A / Agency Issue** layout with a **S.H.I.E.L.D. VERIFIED** stamp.
- DC fighters use the midnight-blue **Concept B / Meta Registry** layout with an **A.R.G.U.S. VERIFIED** stamp.
- Every card receives a permanent file number and a documented nickname or title when one is well established. Characters without a recognized secondary title use their established codename instead of an invented nickname.
- The front contains identity, affiliations, five priority stats, powers, and selectable Standard/Amped versions.
- The card flips to a complete reverse-side dossier containing all 18 stats, powers, moves, fighting style, combat personality, weaknesses, resistances, special mechanics, AI behavior, counters, matchup knowledge, team behavior, and battlefield behavior.

## Draft controls

- **Alternating Turns:** Teams take one pick at a time in first-pick order.
- **Complete One Team First:** The first-pick team fills its entire roster before the next team begins. Captain Draft still distributes one captain to every team before this order takes effect.
- **Fighter Search:** The selectable pool can be filtered live by character name without removing fighters or bypassing the current mode's universe and tier restrictions.
