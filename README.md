# NEON GRAZE 🔮

**Get close. Get points. Don't crash.**

A neon 3D dodge runner. Steer a glowing orb down a bending synthwave highway, slip past obstacles by inches, and chain close calls into massive combos.

### ▶ Play now: [neon-graze.vercel.app](https://neon-graze.vercel.app)

Runs in any modern browser, phone or desktop. No install, no sign-up.

---

## How to play

- **Hold & slide** to steer (or use ← → / A D on desktop)
- **Dodge** everything in your path
- **Graze** obstacles, passing as close as you dare, to build a combo up to **x10**
- **Grab gems** to unlock new orbs
- Reach the end of a world to clear it and earn up to **3 stars**

The run starts slow and builds momentum. The closer you play, the higher you score.

## 6 worlds

| # | World | Signature hazards |
|---|-------|-------------------|
| 1 | **Sunset Drive** | Gap walls, wrecking balls, rolling wheels, bouncers |
| 2 | **Neon City** | Blinking laser gates, crossing traffic, crusher walls, darts |
| 3 | **Crystal Caves** | Erupting spike traps, spinners, laser sweepers, serpents |
| 4 | **Deep Ocean** | Drifting jellyfish, pulsing sea mines, whirlpools |
| 5 | **Volcano Core** | Falling fireballs, lava pits, magma pillars, hammers |
| 6 | **The Void** | Black holes that pull you sideways, asteroids, warp rings |

Each world has its own soundtrack, scenery and sky that shifts as you progress. New obstacle types unlock one by one, each announced with a **NEW** tag.

**Endless mode** cycles through all six worlds while the speed keeps climbing. How far can you go?

## Features

- The road bends and sways like a roller coaster, while the camera stays steady for precise control
- 30+ obstacle patterns across 6 worlds, unlocked progressively
- Graze combo system that rewards risky play
- 8 unlockable orbs
- Original synth soundtrack generated live in the browser, tempo rising with your speed
- Progress, stars, best score and orbs saved locally
- Auto quality mode that turns off heavy glow effects on slower phones

## Tech

- Single `index.html`, no build step
- [three.js](https://threejs.org) r128 for 3D rendering, with UnrealBloom post-processing
- Custom GLSL shaders for skies, floors and the curved-world effect
- Web Audio API for all music and sound effects
- All visuals and audio are generated in code, with no external images or sound files

### Run locally

```bash
git clone https://github.com/DamianWeb1/neon-graze.git
cd neon-graze
# open index.html in a browser, or serve it:
npx serve .
```

## Credits

- Built by **[@liamxbtt](https://x.com/liamxbtt)** for **Twigpine's Project Treetop**, Round 01: Games
- Built with help from AI tools (Claude)
- three.js © three.js authors, MIT License
- Fonts: Rubik and Chakra Petch via Google Fonts (SIL Open Font License)
