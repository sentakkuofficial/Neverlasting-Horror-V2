# NEVERLASTING: Escape the Grand Selection

*A horror escape game set in the Neverlasting (終わりのない) universe.*

---

## Story

You are a child — one of many taken for the Grand Selection, a brutal tournament where fighters are chosen, broken, and remade. You were never meant to fight. You were meant to be forgotten.

But tonight, while the halls are dark and Satoshi patrols with his ledger and pen, you run.

Satoshi is the tournament's registrar. He records every name, every death, every soul that enters the Grand Selection. He knows every corridor, every hiding spot, every shadow. And he knows you're missing.

Find the Blood Seals. Open the gates. Escape — or be found.

*"Found you."*

---

## How to Play

**Objective:** Collect all Blood Seals (封) in each level to unlock the exit gate, then reach the gate to escape. Survive all 5 levels to escape the Grand Selection forever.

**Controls:**

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move | WASD or Arrow Keys | D-Pad (left side) |
| Hide / Leave hiding spot | Spacebar or E | HIDE/USE button (right side) |
| Start / Restart | Click or any key | Tap screen |

**Core Mechanics:**

- **Limited Vision** — You carry a lantern that only lights a small radius around you. Everything beyond is darkness.
- **Blood Seals** — Glowing red collectibles scattered across each level. Collect enough to unlock the exit gate.
- **Hiding** — Wardrobes (purple square tiles) are your only safety. Step onto one and press SPACE to hide. Satoshi cannot find you while hidden. Press SPACE again to leave.
- **Satoshi's AI** — He patrols the halls. If he sees you (line of sight within range), he chases. He uses full pathfinding and will not give up easily. His `!` means he sees you. His `?` means he's suspicious.
- **Heartbeat** — Audio heartbeat intensifies as Satoshi gets closer. Red screen vignette warns you of danger.
- **Lives** — Each level gives you 3 lives. Getting caught costs one life and resets your position — but Satoshi gets slightly faster each time.

---

## The 5 Levels

### Level 1: The Dungeon Cells
*A cramped prison beneath the arena.*

- 4 rooms, tight corridors
- **2 Blood Seals** required
- Satoshi is slow — learn the mechanics here
- Plenty of hiding spots relative to the small space

### Level 2: The Tournament Grounds
*The central halls where fighters are chosen.*

- 8 interconnected rooms with winding passages
- **3 Blood Seals** required
- Satoshi patrols faster
- Multiple paths between rooms give you options to evade

### Level 3: The Cathedral of Bones
*Ancient halls lined with the remains of the fallen.*

- 9 rooms in a 3×3 grid layout
- **4 Blood Seals** required
- Satoshi is faster with an extended detection range (14 tiles)
- More open spaces mean fewer places to hide from his line of sight

### Level 4: The Labyrinth
*A twisting maze. Satoshi knows every turn.*

- 16 small rooms in a 4×4 grid connected by a dense corridor network
- **5 Blood Seals** required
- Satoshi is very fast
- Many intersections and crossings — constant risk of running into him

### Level 5: The Grand Gate
*The final path to freedom. Satoshi will not let you leave.*

- 12 rooms, the most complex layout
- **6 Blood Seals** required
- Satoshi is at maximum speed
- The exit is your way out of the tournament forever

---

## Tips

- **Listen for the heartbeat.** It tells you how close Satoshi is before you can even see him.
- **Watch the screen edges.** A red vignette means danger is near.
- **Don't panic when you see `!`.** Get to the nearest wardrobe immediately.
- **Learn the map.** Each level has a fixed layout. Knowing where the seals and wardrobes are gives you a massive advantage.
- **Satoshi patrols toward seals.** He occasionally walks toward uncollected seals, so grab ones near his patrol route first.
- **Don't stay hidden too long.** Satoshi will move on, but time spent hiding is time not spent collecting seals.
- **Each catch makes him faster.** Don't waste lives — play carefully.

---

## Technical Details

- Single-file HTML5 Canvas game — no dependencies, no install
- Works in any modern browser (Chrome, Firefox, Safari, Edge)
- Mobile touch controls included
- WebAudio API for ambient drone, heartbeat, footsteps, and jump scare audio
- A* pathfinding for Satoshi's chase AI
- Line-of-sight detection for realistic stealth gameplay
- Satoshi's character art embedded directly in the game file

---

## Part of the Neverlasting Universe

**NEVERLASTING** (*Owari No Nai / 終わりのない*) is a dark fantasy series following characters trapped in cycles of violence, survival, and transformation. The Grand Selection is the crucible where it all begins — a tournament that takes everything and gives back only scars.

This game is a companion experience to the Neverlasting novel series.

## Game is live at:
https://sentakkuofficial.github.io/Neverlasting-Horror-V2/
---

*Escape the Grand Selection. Escape Satoshi. Escape the night.*
