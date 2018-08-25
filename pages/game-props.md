[&laquo; Table of Contents](..)

# Game Props

Game props are tools that organize records and make keeping track of things easier.

## Character Sheet

Character sheet is where all information concerning a single player character is recorded.

- Name
- Race
- Gender
- Primary stats
- Secondary stats
- Life path
- Weapons & shield
- Armor
- Abilities
- Skills
- Current fatigue
- Current effects

[&raquo; HTML Character Sheet](../../assets/props/character-sheet.html)

## Group Sheet

Group sheet is where information concerning the whole player character group is recorded.

- Group members, past and present
- Completed quests and objectives, with XP
- Current quest and objectives
- Total group XP
- Group wealth level
- Quest items and other junk

[&raquo; HTML Group Sheet](../../assets/props/group-sheet.html)

## Combat Sheet

Combat sheet is where information about significant values concerning combat, such as thresholds for pain received and weapon damage are pre-calculated.

Pre-calculating these values assists in reducing the mental load in arithmetic required to calculate various numbers during combat.

[&raquo; HTML Combat Sheet](../../assets/props/combat-sheet.html)

### Armor Block

Records the thresholds of suffering [pain](combat#pain-resolution) and [critical wounds](combat#critical-wound-effects) while wearing a particular piece of [armor](equipment#armor) for received [damage](combat#attack-damage).

| Property | Notes | Calculation |
|-:|-|
| 1 Pain | Minimum amount of damage received while wearing current armor (with armor value `AV`) to cause 1 point of pain. | `AV + 1` |
| N Pain | Minimum amount of damage received by character with [Fortitude](characters#secondary-stats) `F` while wearing current armor to cause N points of pain. | `AV + 1 + F x (N - 1)` |
| Critical wound | Minimum amount of damage received by character with [Critical](characters#secondary-stats) secondary stat `C` to suffer a [critical wound](combat#critical-wound-effects). | `AV + C` |
| Supercritical wound | Minimum amount of damage received by character with [Critical](characters#secondary-stats) secondary stat `C` to suffer a [supercritical wound](combat#critical-wound-effects). | `AV + 3 x C` |

In addition, for each threshold the damage value is calculated for armor which is in [disrepair](equipment#durability-and-disrepair).

### Weapon Block

Records [damage](combat#attack-damage) dealt when successfully attacking an opponent. This table can be consulted when your character wins either in a [melee skirmish](combat#melee-skirmish-resolution) or hits with a [ranged attack](combat#ranged-attack-resolution).

The labeling on the horizontal axis above the grid indicates the value of your modified roll, while the vertical axis on the right indicates the opponent's modified roll. The grid cell at the intersection of these values falls within one of the color-coded areas corresponding to single, double and triple [damage multiplier](combat#attack-damage) attacks.

The particular damage values for the current weapon corresponding to these multiplier values are recorded in the boxes at the bottom of the grid, for both nominal and [disrepair](equipment#durability-and-disrepair) values.

## Character Card

Character card is a playing card like prop which summarizes the character's stats and can be used as a token to indicate location on tactical maps, skirmish assignment and to host effect cards.

## Effect Cards

Effect cards are "attached" to character cards to remind of a condition, such as a [critical wound](combat#critical-wound-effects).

## Watch Clock

The watch clock tracks the current time of day and the passage of time as [watches](time-and-space#watches).

[&laquo; Table of Contents](..)
