# Characters

## Races

### Men

Men are a diverse and populous race, who &mdash; despite their average racial traits &mdash; have reached a dominant position in many of the presently habitable lands.

#### Scythians

The Scythian people comprise multiple cultures from the coastal raiders of the north, the nomads of the eastern steppes to the desert tribes of the southern wastelands. Druidic and wild in nature, Scythians have heightened senses, and are somewhat lithe and tough.

#### Garrandines

The valleys and coasts are dotted by fiefdoms of a people priding in both their natural athleticism and learnedness. Through their more collectivist outlook, the Garrandines, as these people are known, have managed to rebuild much on the ruins of the old world.

### Elves

Elves are an Elder race that dominated much of the known world before Man’s ascendance. Proud and strong willed, elves have extremely keen senses and graceful dexterity. The elven race, like all the Elder races, is in terminal decline due to genetic damage caused by the Glow.

#### Gray Elves

The noble Gray elves embody the elven ideals of cool intellect, grace and presence of mind. Once the ruling class of glittering cities, the Gray elves now mainly cohabit human settlements, although some islands in the boundless sea still hold their once-proud spired castles.

#### Sylvan Elves

In the long years of elven ancestry, the Sylvan elves have become far estranged from their Gray elven kindred. Their isolationist society is brutally martial and values skill with the blade and the bow in combat above all else. The strongholds of these tribal elves are in the deep woods, but many of their kin are found in human lands as well.

### Dwarves

Dwarves are an Elder race as hard and unyielding as the bedrock in which they carve their fortresses. Standing slightly shorter than Men, dwarves are of a sturdy and muscular build and almost invariably wear large beards. The dwarven race, like all the Elder races, is in terminal decline due to genetic damage caused by the Glow.

#### Redbeards (Baraz-tarâg)

The Redbeard dwarf most immediately recognizable is the raucous, boisterous warrior armed to the teeth and clad in heavy armor. Redbeards revel in battle and carnage, but observe their own strict code of honor, making them a common sight in various mercenary companies. The Redbeards are no strangers to human lands, but prefer the fortresses of their Longbeard kin whenever practical.

#### Longbeards (Sigin-tarâg)

Longbeard dwarves share many of the traits of their red-bearded kin, but keep slightly cooler heads on their shoulders, well suited to the fine arts of cogitation and mercantilism. Despite this, these stout dwarves have not forgotten how to wield the axe and hammer. Their many mountainside fortresses, quarries, mines and forges dot the landscape far and wide.

### Gnomes

Gnomes are a curious and ancient Elder race, often mistaken as either young elves or dwarves due to their smaller stature. Their mischievous and humorous nature conceals exceptionally keen cognitive and empathic abilities. Surprisingly resilient and nimble, gnomes are the size of smallish, slender humans and sport a variety of facial hair styles. The gnomish race, like all the Elder races, is in terminal decline due to genetic damage caused by the Glow.

#### Tinkers

While not strictly a separate ethnic group, Tinker gnomes ascribe to a somewhat different philosophy than their Astromancer cousins. They have a mind of machinery and cogwheels, and embrace a more physically adventurous world view. Tinker gnomes are often found in dwarven smitheries and forges, but are well traveled.

#### Astromancers

Astromancer gnomes are those of their kin who have long taken a more spiritual interest in the world. Although they share the mechanical aptitude of their gnomish brethren, they are also fascinated by the deep currents of magic and the divine. These gnomes, rather uniquely, can be found among all of the other cultures &mdash; even the reclusive Sylvan elves &mdash; but also build their own settlements which mix the natural and the technological.

## Stats

### Primary Stats

Primary stats describe the fundamental nature of a character, governing the character's starting skills, skill development and derived stats.

| Stat | Key | Description | Mechanics |
|-|-|-|-|
| Physique | PHY | Athleticism, strength and speed of body. | Athletics, melee combat, weapons, armor |
| Dexterity | DEX | Gracefulness, balance, hand-eye-coordination, flexibility, fine-motor skills. | Acrobatics, ranged combat, stealth, sleight of hand |
| Constitution | CON | Health and robustness of body. | Endurance, critical wounds |
| Willpower | WIL | Presence of mind, focus, mental control. | Fortitude, magical/divine ability |
| Cognition | COG | Comprehension, deep learning, memory, judgment. | Professional skills, magical/divine ability |
| Empathy | EMP | Ability to read, anticipate and manipulate persons based on social cues. | Social interaction, mercantile skills |
| Perception | PER | Awareness, sensory acuteness, attention to discrepancy. | Traps, ambushes, secrets, forgery, forensics |

### Secondary Stats

Secondary stats are derived from primary stats, but may also have external modifiers to their values.

| Stat | Derived as | Description |
|-|:-:|-|
| Endurance | `⌊(CON - 7) / 2⌋ + 4` | Exhaustion limit from hardship and pain. |
| Fortitude | `⌊(WIL - 7) / 2⌋ + 4` | Pain threshold from injury. |
| Wield | `PHY` | Soft limit on wieldable weapons and shields. |
| Spell memory | `⌊COG / 2⌋`|Number of spells memorizable at once. |
| Spell sustain | `COG - 10` | Number of sustainable spell points. Minimum zero. |

## Character Creation

Character creation proceeds with the following steps.

1. Select your character's race and gender. Record the racial stat modifiers and traits on your character sheet. Record your primary stats.
1. Select a name for your character.
1. Perform the [life path](#life-path) process.
1. Derive and record your secondary stats.
1. Record your base skill values.
1. Assign modifiers and XP points from your life path.
1. Assign XP points from group experience pool.
1. Acquire abilities based on your XP distribution.
1. Purchase starting equipment.
1. Bonus: Find a portrait image and print your character card.
1. Bonus: Write a bio for your character based on the life path.

### Racial Stat Modifiers

The base value of every primary stat is `10`.

| Race | PHY | DEX | CON | WIL | COG | EMP | PER |
|-|-:|-:|-:|-:|-:|-:|-:|
| **Men** ||||||||
| Scythians ||+1|+1||-1|-1|+2|
| Garrandines |+1|||+1|+1|+1|-1|
| **Elves** ||||||||
| Gray elves ||||||||
| Sylvan elves ||||||||
| **Dwarves** ||||||||
| Redbeards ||||||||
| Longbeards ||||||||
| **Gnomes** ||||||||
| Tinker gnomes ||||||||
| Astromancer gnomes |||||||||

### Life Path

The Life Path represents the formative years of character development, in abstract terms.

## Skills

Most character actions are resolved through the application of skills.

Each skill is governed by a primary stat, whose value is here denoted `P`. The base value of a skill is derived as `P - 10` (can be negative). See [list of skills](#list-of-skills) for a list of which stats govern which skills.

See also TODO(experience, half plus one, skillsets, abilities).

### Skill Resolution

To resolve a skill check, roll a `d20` and add your skill modifier to obtain your roll value `R`. Then compare the roll value to a target difficulty `T`.

If `R > T`, the skill check is successful. Otherwise if `T - R < 5`, the skill check is a partial failure. Otherwise, the skill check is a failure.

The effect of success, partial failure and failure vary from skill to skill.

### Critical Success and Fumble

A natural (i.e. unmodified) `20` is a critical success, and counts as a success, even if the roll value is insufficient.

A natural `1` is a fumble, and counts as a failure, even if the roll value is sufficient.

### Opposed Skill Resolution

Some skill checks are opposed, meaning that two characters directly oppose each other in their skill checks. In such cases, the character with higher roll value succeeds. If both characters roll a fumble or critical success, resolve as if neither had.

### Advantage and Disadvantage

When you have *advantage*, you roll two `d20`'s for skill checks, and the natural roll value is the higher die result. With *disadvantage*, it's the lower result.

### Skill Target Difficulties

To make gameplay faster, skill check target difficulties are by default limited to a set of predefined target values with standardized names.

| Name | Target | Notes |
|-|-:|-|
| Normal | 10 | Default difficulty. Unskilled character has about 50% success rate.|
| Difficult | 20 | Highly skilled character has about 50% success rate.|
| Extreme | 25 | Natural `20` does not count as critical success.|

### Fatigue in Skill Checks

When a character is fatigued, each skill check is further modified by fatigue points. Roll value `R` is `d20` plus skill modifier `S` minus fatigue points `F`.

### List of Skills

Skills are divided into categories called skillsets. Some skills have associated keywords (e.g. *Melee.*) which can be used as a reference.

| Martial | Stat | Notes |
|-|-|-|
| One-handed | PHY | *Melee.* Weapons wieldable by one hand. |
| Two-handed | PHY | *Melee.* Two-handed weapons. |
| Weapon-and-shield | PHY | *Melee.* Fighting with a shield. |
| Fired weapons | DEX | *Ranged.* Bows, crossbows, guns etc. |
| Thrown weapons | DEX | *Ranged.* Knives, hatchets, javelins etc. |
| Evasion | DEX | Evading melee or ranged attacks passively. |

| Cloak and dagger | Stat | Notes |
|-|-|-|
| Sneaking | DEX | Move without been noticed. |
| Lockpicking | DEX | Silently pick locks on doors etc. |
| Pickpocketing | DEX | Lift from or plant objects on persons unnoticed. |
| Traps/devices | DEX | *Mechanical.* Set or disarm traps and operate devices. |
| Forgery | PER | Forge or identify a forged document. |

| Magic and divinity | Stat | Notes |
|-|-|-|
|TODO|TODO|TODO|

| Utility | Stat | Notes |
|-|-|-|
| Stabilization | COG | *Medical.* Stop bleeding. |
| Trauma treatment | COG | *Medical.* Treat a critical wound. |
| Investigation | PER | Actively search a scene for clues etc. |
| Interaction | EMP | *Social.* Inquiry, interrogation, persuasion, deception. |
| Mercantile | EMP | *Social.* Purchases of items. |
| Field repair | PER |

## Abilities

## Non-Player Characters