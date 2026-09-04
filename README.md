<div align="center">

# ☀️ AstraVanguard 3D

### *Sunwarden: Solaris Rescue* — a single-file 3D superhero platformer

> 🧪 **Benchmark build** — designed, coded, and play-tested end-to-end by
> **Muse Spark 1.3 `xhigh`** in one autonomous agentic session:
> third-person flight combat, a full mission arc, and **25/25 automated
> browser acceptance checks passing with zero console errors.**

[![Single-file HTML](https://img.shields.io/badge/single%20file-index.html-38bdf8)]()
[![Three.js r128](https://img.shields.io/badge/three.js-r128-8fa3b4)]()
[![No build step](https://img.shields.io/badge/build-none-4ade80)]()
[![Play online](https://img.shields.io/badge/play-GitHub%20Pages-ffd700)]()

</div>

---

## [▶️ Run it](https://joji228.github.io/Muse-Spark1.3-AstraVanguard3D/)

**Locally:** double-click `index.html` (or serve the folder statically). Internet is needed once for the Three.js CDN.

| Input | Action |
|---|---|
| `WASD` + mouse | Move (mouse steers the camera, GTA-style) |
| `Space` (hold) | Fly — release to hover, `C` dives |
| `Left-click` (hold) | Heat vision — infinite range, stops at walls |
| `Wheel-click` / double-tap | Lock onto a foe (beam + camera track it) |
| `Shift` | Hyperspeed ×2 — hold 0.5s mid-flight for a **sonic boom** |
| `Q` → `J`/click | Grab & throw street rubble |
| `J` / `K` / `P` / `M` / `F` | Punch / laser / pause menu / mute / fullscreen |

Full touch support included (pad, drag-to-aim, dive + hyper buttons).

## 🎯 The mission

1. **Rescue 5 citizens** 👪 (follow the light beacons)
2. **Defeat the UMBRA-MECH** 🤖 (dodge the telegraphed red slam ring — it enrages under 40% HP)
3. **Ignite the Beacon Tower** 🗼 (locked until 1 + 2 are done)

Three lives, checkpoint pylons, score + persistent best, God Mode in the pause menu.

## 🛠️ Under the hood

- ~2,300 lines of vanilla JS + Three.js in **one file**
- Fixed-timestep simulation, pooled particles/bullets/floaters, shared GPU assets (flat memory across restarts)
- GTA-style rate-steer camera, mouse-aimed infinite beam with wall occlusion, soft-lock melee, waypoint-following drones, telegraphed dasher dives, boss shockwaves
- Original IP: Sol the Sunwarden, Solaris City, Dr. Umbra — no third-party assets

---

<div align="center">

*Built as an agentic-coding benchmark with **Muse Spark 1.3 (xhigh)** — spec → code → browser play-testing → fix loops, all autonomous.*

</div>
