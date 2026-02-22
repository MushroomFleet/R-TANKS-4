# R-TANKS 4: Car-Mero Edition

A TRON-inspired wireframe tank combat game built with React, Three.js, and TypeScript. Blast through neon arenas, master five distinct weapons, outsmart AI opponents, and hunt hidden secrets across 10 handcrafted battlegrounds.

**[Play Now in Your Browser](https://scuffedepoch.com/react-tanks-4/)**

---

## Gameplay

You command a customizable tank in fast-paced arena combat against AI enemies. Each match takes place in a distinct 3D arena with elevated platforms, destructible cover, ramps, and hidden secrets to discover.

### Controls

| Action | Keys |
|--------|------|
| Move Forward / Back | `W` `S` or Arrow Keys |
| Strafe Left / Right | `A` `D` or Arrow Keys |
| Aim | Mouse |
| Fire | Left Mouse Button |
| Boost | `Spacebar` (2.5s burst, 6s cooldown) |
| Drift | `Shift` |
| Switch Weapon | `1` `2` `3` `4` `5` |
| Toggle Camera | `V` |
| Reset Camera | `X` |
| Toggle Aim Mode | `Q` |
| Pause | `Escape` |

### Weapons

All weapons have unlimited ammo — cooldowns and overheat are the limits.

| # | Weapon | Damage | Fire Rate | Range | Special |
|---|--------|--------|-----------|-------|---------|
| 1 | **Precision Cannon** | 25 | 3/sec | Long | 2x critical on rear hits |
| 2 | **Plasma Mortar** | 50 | 1/sec | Mid | Splash damage, destroys cover, area denial |
| 3 | **Rapid Pulse** | 10 | 8/sec | Short-Mid | Slows targets, overheat mechanic |
| 4 | **Scatter Shot** | 12x8 | 1.5/sec | Close | 8 pellets, knockback |
| 5 | **Seeker Missile** | 90 | 0.5/sec | Any | Guaranteed hit, 8s cooldown |

### Arenas

10 arenas, each with unique layout philosophy and 3 hidden secrets:

- **The Horseshoe Colosseum** — Classic horseshoe flow with vantage platforms and trenches
- **The Crucible** — Tight opposing platforms with destructible center cover
- **The Expanse** — Largest arena with wide-open sightlines and distributed platforms
- **Neon Switchbacks** — Zigzag elevated walkways and sniper perches
- **The Gauntlet** — Narrow corridor with alternating cover on each side
- **Skybridge** — Vertical combat across elevated towers connected by bridges
- **The Cauldron** — Sunken center bowl surrounded by elevated rim positions
- **Circuit Breaker** — Figure-8 track with cover islands at intersections
- **The Maze** — Dense pillar grid forming tight corridors, shotgun territory
- **Overlord** — Massive 4-quadrant arena connected by central bridges

### Secrets

Every arena contains 3 hidden secrets at easy, medium, and hard difficulty. Discover them by exploring — look for destructible walls, hidden paths, and timed doors. Rewards include health boosts, shield upgrades, damage multipliers, and speed buffs.

### The Bunker

Before each mission, visit The Bunker to customize your tank:
- **Tank Color** — Choose from 6 neon colors
- **Armor** — Trade speed for survivability (1-10)
- **Shield Recharge** — Adjust shield recovery rate (1-10)
- **Arena Selection** — Pick your battleground

### Level Editor

Build your own arenas with the built-in level editor. Place platforms, ramps, cover elements, and landmarks to create custom combat spaces.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI Framework | React 18 |
| Language | TypeScript |
| 3D Rendering | Three.js + @react-three/fiber + drei |
| State Management | Zustand |
| Build Tool | Vite |

## Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Type check
npx tsc --noEmit

# Production build
npm run build
```

The dev server runs at `http://localhost:5173`.

---

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{r_tanks_4,
  title = {R-TANKS 4: Car-Mero Edition — TRON-Inspired Wireframe Tank Combat},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/R-TANKS-4},
  version = {1.0.0}
}
```

### Donate:

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
