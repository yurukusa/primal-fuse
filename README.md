# Primal Fuse

**Element merge puzzle** — combine elements to discover all 30 hidden elements.

🎮 **[Play in Browser](https://yurukusa.github.io/primal-fuse/)**

Built with Claude Code for the [AI Browser Game Jam 2026](https://itch.io/jam/ai-browser-game-jam).

---

## How to Play

1. **Select** an element tile — highlighted cells show all possible merges
2. **Click** an adjacent tile to merge them into a new element
3. **Discover** all 30 elements across 4 layers to complete the Compendium
4. **Share** your rarest discoveries with one click (Layer 4 ULTIMATE elements!)

---

## Element Layers

| Layer | Count | Examples |
|-------|-------|---------|
| **Layer 1** — Base | 4 | 🔥 Fire, 💧 Water, 🌍 Earth, 💨 Wind |
| **Layer 2** — Compound | 10 | 🌋 Lava, ❄️ Ice, ⛈️ Storm, ⚡ Lightning… |
| **Layer 3** — Rare | 10 | 🪨 Rock, 🌴 Oasis, 🌪️ Tornado, 🟠 Magma… |
| **Layer 4** — Ultimate | 6 | 🌀 Hurricane, 🏔️ Glacier, 🌱 Life, ✨ Cosmos… |

26 total merge recipes. Both same-type and cross-type merges are possible.

---

## Scoring

- Layer 2 merge: **100 pts** × combo multiplier
- Layer 3 merge: **300 pts** × combo multiplier
- Layer 4 merge: **600 pts** × combo multiplier
- New discovery bonus: **+500 pts** (Layer 4: **+1000 pts**)

---

## Tech

Single HTML file (~1,300 lines), zero dependencies. Runs in any browser.

```
index.html    ~1,300 lines   Full game (HTML + CSS + JS, all-in-one)
thumbnail.png              Cover art for itch.io
```
