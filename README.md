# ⚛ Cold War Life Simulator

An interactive browser-based life simulator set during the Cold War era (1957–1969). Create a character, watch their story unfold through pivotal historical moments, and make choices that shape — or end — their life.

---

## Features

- **Character creation** — Choose your name, birth year, nationality (American, Soviet, British, Cuban), occupation, social class, and location type
- **Dynamic life story** — Your character's narrative is generated based on who they are and where they live, with historically grounded writing for each year
- **Interactive decision points** — At critical historical moments (Cuban Missile Crisis, Vietnam draft, 1968 protests), you're asked to make real choices that affect the outcome
- **Auto-advancing timeline** — Choices auto-resolve after 5 seconds if no input is given
- **Typewriter text effect** — Story text types out line by line with smooth auto-scroll keeping you anchored to the latest content
- **Personalized death** — The simulation ends with a cause of death specific to your choices, nationality, occupation, and social status
- **CRT aesthetic** — Scanline overlay, glowing text, and animated gradients for a period-appropriate feel

---

## Historical Coverage

| Year | Event |
|------|-------|
| 1957 | Sputnik launch and the start of the Space Race |
| 1961 | Gagarin's orbit; construction of the Berlin Wall |
| 1962 | Cuban Missile Crisis |
| 1963 | Assassination of President Kennedy |
| 1968 | Global protests, assassinations, social upheaval |
| 1969 | Apollo 11 Moon landing |

---

## Playable Nationalities & Occupations

**Nationalities:** American · Soviet · British · Cuban

**Occupations:** Aerospace Engineer · Nuclear Scientist · Military Pilot · Diplomat · Factory Worker · School Teacher · Journalist · Farmer

Each combination produces meaningfully different narrative branches. A Soviet journalist in 1967 disappears after writing the wrong article. A Cuban farmer watches neighbors flee to Miami. An American pilot maintains constant readiness to intercept Soviet aircraft probing U.S. airspace.

---

## Decision Points

Depending on your character's profile, you may face:

- **1961 (Cuban)** — Your neighbor is arrested for counter-revolutionary activity. Do you report them, stay silent, help them, or flee by boat?
- **1962 (Pilot)** — The Cuban Missile Crisis. Do you volunteer for high-risk recon flights over Cuba, request defensive patrols, or take medical leave?
- **1962 (Diplomat/Scientist)** — Do you work toward peace, prepare your family to evacuate, or leak classified information to the press?
- **1965 (American, draft age)** — Vietnam is escalating. Do you enlist, defer through college, flee to Canada, or declare conscientious objector status?
- **1968 (Ages 18–30)** — The world is on fire. Do you protest, support law and order, stay apolitical, or campaign for change?

Your choices carry consequences — some will kill you years before the simulation ends.

---

## Historical Accuracy Notes

The narratives are written to reflect documented history:

- Duck-and-cover drills included the historically accurate neck-covering instruction
- The U-2 recon pilot death references Rudolf Anderson's October 27, 1962 shootdown over eastern Cuba — the only combat fatality of the Cuban Missile Crisis
- Low-level Cuban recon missions correctly reference RF-8 Crusader aircraft and Cuban anti-aircraft fire (not SA-2s, which were a high-altitude threat)
- The Vietnam Veterans Memorial is referenced with its correct 1982 dedication date, not anachronistically as existing in the 1960s
- Soviet cosmonaut selection is described as secretive and competitive, consistent with how the program actually operated
- Conscientious objector status is correctly described as requiring two years of mandatory alternative civilian service
- NASA's creation (1958) is placed correctly relative to the Sputnik shock (1957)

---

## Usage

No installation or build step required. Open `index.html` in any modern browser or go to GitHub Pages https://46s8s4s2k9-commits.github.io/cold_war_era_life_sim/.

```bash
git clone https://github.com/your-username/cold_war_era_life_sim
cd cold_war_era_life_sim
open index.html
```

---

## Tech Stack

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build tools.
