# The Iron Tide  RMU Combat Reference Site

A GitHub Pages reference site for running Rolemaster Unified tactical combat with the Iron Tide mercenary company.

## How To Use With Claude

Start a new conversation and say something like:

> "We're continuing the Iron Tide RMU campaign. The reference site is at https://[your-username].github.io/iron-tide-rmu/. Fetch the session state at /sessions/saltmaw-caves.md to see where we left off. When you need to resolve any attack, spell, critical, or other mechanic, fetch the specific reference file you need from the site rather than guessing. The index of all files is at the root index.md."

Claude will use web_fetch to pull only the specific files needed for each resolution  attack tables, critical tables, character sheets, rules  keeping context lean and accuracy high.

## Site Structure

```
index.md                     Master index of all files
rules/
  combat-resolution.md       Attack rolls, SCR, criticals, RR, fumbles
  movement-and-pace.md       Pace table, AP costs, Footwork
  defense.md                 Shields, parry, dodge, cover
  size-and-positional.md     Size adjustments, flanking, restricted quarters
  spellcasting.md            SCR formula, PP, preparation, concentration
  injuries.md                Hit loss, bleeding, stun, healing
  fear-and-morale.md         Fear RR, morale, rally
attack-tables/
  war-hammer.md              Grond's primary
  rapier.md                  Ambrosia's primary
  composite-bow.md           Ralhann's primary
  crossbow.md                Ambrosia's hand crossbow
  arming-sword.md            Ralhann's backup
  dagger.md                  Ambrosia's backup
  bolt-lightning.md          Rian's Shock/Lightning Bolt
  bolt-fire.md               Rian's Fire Bolt
  bolt-ice.md                Rian's Ice Bolt
  bite.md                    Dog/creature attacks
  claw.md                    Creature attacks
  ram.md                     Dog/creature ram attacks
critical-tables/
  krush.md                   Warhammer criticals
  puncture.md                Rapier, bow, crossbow criticals
  slash.md                   Sword criticals
  electricity.md             Lightning bolt criticals
  cold.md                    Ice bolt criticals
  heat.md                    Fire bolt criticals
  impact.md                  Ram/blunt force criticals
  strikes.md                 Unarmed criticals
  grapple.md                 Wrestling criticals
  unbalance.md               Knockdown criticals
  fumble-melee.md            Melee fumble table
  fumble-ranged.md           Ranged fumble table
characters/
  grond.md                   Troll Fighter sheet
  ambrosia.md                Human Rogue sheet
  ralhann.md                 Wood Elf Ranger sheet
  rian.md                    Gnome Magician sheet
  party-tactics.md           Formation, synergies, combos
spells/
  light-law.md               Rian's primary (Quick-Caster II)
  ice-law.md                 Rian's secondary
  fire-law.md                Rian's tertiary
  earth-law.md               Terrain control
  wind-law.md                Wind attacks
  water-law.md               Water attacks
  elemental-shields.md       Party protection
  spell-wall.md              Anti-magic defense
  beastly-ways.md            Ralhann's self-buffs
creatures/
  humanoid-npcs.md           Smuggler/bandit/guard stat guidelines
  dogs.md                    Guard dogs, wolves
sessions/
  saltmaw-caves.md           Current mission state
```

## Setup

1. Create a GitHub repository called `iron-tide-rmu`
2. Push all files from this directory
3. Go to Settings  Pages  Deploy from branch (main)
4. Wait a minute for the site to build
5. Access at `https://[your-username].github.io/iron-tide-rmu/`

## Campaign Info

- **System:** Rolemaster Unified (RMU)
- **Party Level:** 3
- **Party Size:** 4 characters
- **Campaign Focus:** Tactical combat exploration
- **GM:** Claude (AI) | **Player:** Jim (rolls all dice for all combatants)
