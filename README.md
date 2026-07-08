<div align="center">

# WORDFALL

### Orbital Typing Defense

**Type fast. Prioritize threats. Defend Earth.**

[![Play Wordfall](https://img.shields.io/badge/PLAY%20WORDFALL-55E7FF?style=for-the-badge&logo=github&logoColor=06101e)](https://thiepn.github.io/wordfall/)

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?style=flat-square&logo=github)](https://thiepn.github.io/wordfall/)
![HTML5](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-64F5A5?style=flat-square)
![Local Save](https://img.shields.io/badge/Save-localStorage-AE6CFF?style=flat-square)

</div>

---

## Play now

**Live game:** [https://thiepn.github.io/wordfall/](https://thiepn.github.io/wordfall/)

Wordfall is a browser-based typing defense game set above Earth. Alien wordships descend through the atmosphere, and every ship carries a word. Lock onto the most dangerous target, type its word to fire orbital lasers, and destroy the invasion fleet before it reaches the planetary defense line.

No installation, account, backend, or download is required.

---

## Core gameplay

- Type a ship’s first letter to lock the closest dangerous matching target.
- Finish the word to destroy the ship.
- Correct letters fire visible laser shots.
- Mistakes reduce accuracy and may weaken the combo.
- Ships that reach Earth damage the planetary shield and health.
- Complete waves, choose upgrades, and survive increasingly difficult attack patterns.
- Defeat **The Void Harvester** at the end of the Campaign.

Wordfall combines:

- typing speed
- accuracy
- target prioritization
- arcade survival
- lightweight roguelite upgrades
- procedural wave generation

---

## Game modes

### Campaign

Survive ten escalating waves and defeat **The Void Harvester**.

Campaign includes:

- procedural enemy waves
- upgrade choices after every second wave
- multiple enemy classes
- a full boss encounter
- a victory screen with run statistics

### Endless Mode

Continue through increasingly difficult procedural waves for as long as Earth survives.

Every tenth wave introduces a stronger boss encounter.

---

## Controls

### During gameplay

| Input | Action |
|---|---|
| `A–Z` | Type enemy words |
| `Esc` | Pause or resume |
| Mouse | Activate abilities |
| Mouse | Switch or cancel the current target |
| Mouse | Toggle sound or fullscreen |

### Menus and overlays

| Input | Action |
|---|---|
| Arrow keys | Move between options |
| `Enter` | Select the focused option |
| `Esc` | Return, close, or resume where applicable |

> Wordfall is designed primarily for a physical keyboard.

---

## Targeting system

Targeting is based on danger rather than screen order.

When no ship is selected, typing a letter:

1. Finds all visible ships beginning with that letter.
2. Ranks them by threat.
3. Selects the most dangerous candidate.
4. Counts the same keypress as the first typed letter.

The selected target receives:

- a cyan glow
- an animated crosshair
- a targeting line from Earth’s cannon
- a larger word label
- highlighted typed letters
- reduced visual emphasis on other ships

Use the on-screen **Next Match** button to cycle through ships with the same first letter, or **Cancel Target** to release the current lock.

---

## Enemy types

| Enemy | Role |
|---|---|
| **Scout** | Standard balanced ship |
| **Interceptor** | Fast short-word threat |
| **Destroyer** | Slow heavy ship with long words |
| **Shielded Ship** | Requires a shield code before the main word |
| **Carrier** | Releases additional Drones |
| **Drone** | Small, fast secondary threat |
| **Orbital Projectile** | Boss attack that can be typed down |
| **The Void Harvester** | Multi-phase Campaign boss |

---

## Abilities

Wordfall includes three active orbital-defense systems.

### Time Freeze

Stops enemy movement temporarily while still allowing the player to type.

### Plasma Pulse

Damages all active standard enemies at once.

### Shield Repair

Restores planetary shielding without wasting the cooldown when the shield is already full.

All abilities are activated through the on-screen interface.

---

## Upgrade system

After every second wave, choose one of three upgrades.

Available upgrade paths include:

- stronger targeting
- chain damage
- perfect-word bonuses
- increased health and shielding
- faster shield recharge
- stronger abilities
- shorter cooldowns
- improved scoring
- earlier combo multipliers
- emergency survival systems

Upgrades apply only to the current run, keeping each playthrough distinct.

---

## Score, combo, accuracy, and WPM

Wordfall tracks:

- score
- wave reached
- current combo
- best combo
- accuracy
- current WPM
- average WPM
- highest WPM
- words completed
- ships destroyed
- playtime

Higher scores come from:

- longer words
- perfect words
- high combos
- dangerous last-second kills
- stronger enemy types
- higher difficulty settings

---

## Difficulty modes

| Mode | Description |
|---|---|
| **Cadet** | Slower enemies, stronger shield, lighter combo penalties |
| **Defender** | Standard intended balance |
| **Commander** | Faster enemies, more special threats, higher score potential |

---

## Accessibility and settings

Wordfall includes:

- adjustable master, effects, and ambient volume
- screen-shake toggle
- reduced-motion mode
- particle-density control
- automatic pause on focus loss
- high-contrast targeting
- large-text mode
- fullscreen support
- persistent browser settings

No essential gameplay information is communicated through sound alone.

---

## Technical overview

Wordfall is built as a self-contained static web game.

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Canvas 2D**
- **Inline SVG**
- **Web Audio API**
- **localStorage**
- **requestAnimationFrame**

The complete game runs from a single `index.html` file.

No framework, package manager, build tool, backend, database, or external game engine is required.

---

## Project structure

```text
wordfall/
├── index.html
└── README.md
```

---

## Run locally

Download or clone the repository, then open:

```text
index.html
```

in a modern browser.

For the most reliable local behavior, serve the directory with a simple local server.

### Python

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## Deploy with GitHub Pages

1. Upload `index.html` and `README.md` to the repository root.
2. Open the repository’s **Settings**.
3. Select **Pages**.
4. Set the source to **GitHub Actions**.
5. Choose the **Static HTML** workflow.
6. Commit the generated workflow.
7. Wait for the deployment action to finish.

The live deployment is available at:

**[https://thiepn.github.io/wordfall/](https://thiepn.github.io/wordfall/)**

---

## Save data

Progress and settings are stored locally in the browser through `localStorage`.

Saved data includes:

- settings
- high scores
- best wave
- lifetime statistics
- tutorial completion

Save data is device- and browser-specific. Clearing browser storage resets it.

---

## Browser support

Wordfall is intended for current desktop versions of:

- Chrome
- Edge
- Firefox
- Safari

A physical keyboard is strongly recommended.

---

## Current version

```text
v1.0.2 — Keyboard Fix
```

The current version removes conflicting letter-key shortcuts so all alphabetic keys remain dedicated to word typing.

---

<div align="center">

## Defend Earth now

[![Launch Wordfall](https://img.shields.io/badge/LAUNCH%20GAME-5B8CFF?style=for-the-badge&logo=rocket&logoColor=white)](https://thiepn.github.io/wordfall/)

**[thiepn.github.io/wordfall](https://thiepn.github.io/wordfall/)**

</div>
