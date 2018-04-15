[&laquo; Table of Contents](..)

# Arcane and Divine

The Arcane and Divine are supernatural powers whose origins are shrouded in mystery.

The Arcane arts take a more scientific, direct approach to manipulating these forces. Divinity is a more spiritual approach, whose proponents believe that all magical force derives from Deities who grant power to those who are deemed worthy through unwavering faith and worship.

In any case, great exertion of willpower is necessary for both spellcasting and divine prayer. Some arcanists even purport this as evidence that priests and monks of the divine faiths are actually channeling arcane power, just like sorcerers. Such claims, naturally, are condemned by the faithful as heretical ravings.

The more esoteric magical realms of Druidism, Dwarven Runecrafting and Gnomish Artifice, are usually grouped with the Arcane arts, although they are not strictly appropriate.

## Memorizing Spells and Prayers

Before spells can be casted or prayers recited, they must be memorized. A character whose [Spell memory](characters#secondary-stats) secondary stat value is `M` can memorize equally many spells or prayers.

Memorizing a new set of spells or prayers can be done during a [rest](time-and-space#rest) or [camp](time-and-space#camp).

## Sustained Spells and Prayers

A spell or prayer whose Duration is *Sustained(X)*, must be sustained for the spell or prayer to remain in effect. A character whose [Spell sustain](characters#secondary-stats) is `S` can sustain a total of equally many sustain points `X`.

Sustained spells need to be recast after a [camp](time-and-space#camp).

> **Example**
>
> A character's Spell sustain value is 4. They could sustain spells with Sustained(1) and Sustained(2), and still have 1 spell sustain point (4 - 1 - 2 = 1) available for another sustained spell.

## Ritual Spells and Prayers

A spell or prayer with the *Ritual* keyword require a more complex ritual cast or recital. Such spells or prayers take one [watch](time-and-space#watches) to cast or recite.

## Concentrating on a Spell or Prayer

Some spells or prayers have duration marked as Concentration. These spells or prayers remain in effect while the caster is actively concentrating.

Taking a skill check other than Evasion, suffering pain or a critical wound or becoming incapacitated breaks concentration. Only one spell or prayer can be concentrated on at a time.

## Arcana and Spellcasting

An Arcane sorcerer reaches with his mind to the Source and draws arcane power through raw willpower, bending the fabric of the universe to their will. A druid draws on the power of untamed nature through the mind's eye or blood rituals. Dwarven runesmiths craft runes from alchemical reagents, shaped to secret words of power. Gnomish artificers build mechanical constructs and imbue them with magic.

To become an arcanist, no formal education is necessary, although it can be beneficial. It simply suffices to unlock one of the Aspects, or Schools, of Arcane magic. But beware, for the flow of magic is treacherous, and will burn the careless dabbler to cinder in the blink of an eye.

### Spellcasting Resolution

To cast a spell, you must first have memorized it.

Let `T` be a spell's target difficulty and `S` your skill in that spell's aspect. To be able to attempt to cast this spell, `T` must be *equal to or less than* `S + 10`.

Roll `d20` and add `S`. If the result is *greater than* `T`, you will have successfully cast the spell. Otherwise, you have failed in casting the spell, and must roll `d10` on the spell failure table, modified by `T - S - 10` (minimum modifier value is zero).

A natural `20` is a success and natural `1` is a failure.

#### Spell Failure

| Roll | Result |
|-:|-|
| 1&ndash;10 | Spell fails without further effect. |
| 11 | Caster suffers 1 pain. |
| 12 | Caster suffers 2 pain. |
| 13 | Caster suffers 2 pain and starts [bleeding](combat#critical-wound-effects). |
| 14 | Caster is [incapacitated](combat#incapacitation) and starts [bleeding](combat#critical-wound-effects). |
| 15 | Caster is [incapacitated](combat#incapacitation), starts [bleeding](combat#critical-wound-effects) and permanently loses `1` WIL. |
| 16&ndash;18 | Caster is instantly killed (lost `1` WIL if resurrected). |
| 19&ndash;20 | Caster is instantly killed, and their body is burned to cinder. |

### Arcane Aspects

#### Evocation

Evocation is a discipline of Sorcery that focuses on the elemental powers of Fire and Frost and direct manipulation of the physical world. Spells are produced mentally, without the aid of material components, manifesting instantly, but may require physical manipulation in practical applications.

| Evocation | Ignition |
|-|-|
| Difficulty | |
| Target | One character, Marksman targeting rules |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Elemental.* TODO Burn one target, autohit |

| Evocation | Fireball |
|-|-|
| Difficulty | |
| Target | One area, Marksman targeting rules |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Elemental.* Throw a blazing boulder of fire that explodes for `20` points of [Fire](combat#damage-types) damage on contact. Roll Throwing skill, targeting your area or an adjacent area. All characters in the target area must use their Evasion skill against your roll. A successful evasion results in half damage. Characters staying in cover take half damage. |

| Evocation | Repulse |
|-|-|
| Difficulty | |
| Target | One character in your area |
| Duration | Concentration |
| Materials | &mdash; |
| Effects | *Telekinetic.* While you concentrate on the spell, the target cannot approach to melee engagement range with you, held back by a force emanating from you. |

| Evocation | Constrict |
|-|-|
| Difficulty | |
| Target | One character in your area |
| Duration | Concentration |
| Materials | &mdash; |
| Effects | *Telekinetic.* Lift one character into the air and hold them in place. The target makes a Physique save; on a success the spell has the effects of Repulse. While held, the target has disadvantage to *Melee* and Evasion rolls, and cannot move. |

| Evocation | Shockwave |
|-|-|
| Difficulty | |
| Target | Melee |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Telekinetic.* Strike a target with a shockwave of psychokinetic force. The target makes a Evasion check against your cast roll. The target takes damage as if struck by a 9 base damage impact weapon. On a hit, the target is flung back one area, or if they are performing a Acrobatics check, they fail it. On a miss, you are disengaged. |

| Evocation | Aura of Frost |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | *Elemental.*  Frost aura centered on and moving with self. TODO |

| Evocation | Frost Storm |
|-|-|
| Difficulty | One area, Marksman targeting rules |
| Target | |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Elemental.* Frost AoE TODO |

| Evocation | Ice Spear |
|-|-|
| Difficulty | |
| Target | One character, Marksman targeting rules |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Elemental.* Throwing frost attack. TODO |

| Evocation | Radiant Orb |
|-|-|
| Difficulty | |
| Target | Your area |
| Duration | Concentration |
| Materials | &mdash; |
| Effects | Provide daylight for Investigation/tracking checks etc. |

| Evocation | Wall of Earth |
|-|-|
| Difficulty | |
| Target | Your area |
| Duration | Permanent |
| Materials | &mdash; |
| Effects | Permanent obstacle. TODO |

| Evocation | Shield Rend |
|-|-|
| Difficulty | |
| Target | One character, Marksman targeting rules |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Shatter target's shield. |

| Evocation | Water Breathing |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | X rounds |
| Materials | &mdash; |
| Effects | Cannot drown while spell is in effect. |

#### Abjuration

Abjuration is the manifestation of Sorcery that is aligned obversely to other magical and fundamental forces. Many spells of this discipline thus can be used to counter and shield from other effects.

| Abjuration | Force Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Target is enveloped by a magical barrier that deflects damage. A hit of `10` or more damage will cause the barrier to collapse, while still deflecting `10` points of damage. |

| Abjuration | Feather Fall |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | While falling |
| Materials | &mdash; |
| Effects | Target will float gently to the ground, after which the spell dissipates. |

- Fire Shield: Touch sustain resistance to fire
- Frost Shield: Touch sustain resistance to frost
- Acid Shield: Touch sustain resistance to acid
- Whirlwind: Self area, sustain, ranged attacks have disadvantage
- Warding Glyph: Alarm sensors on rest/camp ground
- ambush protection
- Mind Shield: Touch sustain protect from mental/2ndary effects?
- Force Cage: cage and magical lock, cast on existing structure

#### Conjuring

- Illusory Wealth: Create 1/2/5 illusory wealth for gambling/merchants. Disposition
- Muffle: Perform a Sneaking check. On failure, there is no disturbance.
- Soothing Whispers: Ranged single target alertness becomes relaxed, if alertness was on duty
- Summon Wisp: Guards become distracted, then suspicious
- Summon Fiend: Fighting monster, banished after combat / sustained
- Phase Shift: Ranged single target is shifted for one round into another phase
- Fade: Self resistant to physical damage, concentration
- possession?
- Blink: Precast, sustained, disengage from melee through a micro-teleportation
- Planar Shortcut: reduce travel time on a path previously traveled by 1

#### Transcendence

- Flashcast: Cast with another spell w/difficulty +X for spell, effect before ranged phase
- Countermagic: Cause all Arcane magic to have difficulty level X/Y/Z
- Dispel: dispel magical spells, not effects
- probe/sense magic properties e.g. cast strength
- haste

#### Druidism

Druidism draws power from the living force of untamed nature through herbs, rituals and blood magic. Nature manifests not as a gentle nurturer, but as a brutal contest for survival, fitness and fertility.

##### Biome Power Level

Druidic magic waxes and wanes in power with the verdancy of the local biome. Each Place of Interest's verdancy is determined by the Game Master. The resulting Biome Power Level is referenced as `BPL` in the spell descriptions.

| Verdancy | BPL |
|-|-|
| Barren | 0 |
| Stunted | 1 |
| Verdant | 3 |
| Lush | 5 |

##### Blood Magic

Blood magic changes its nature by the blood used. Blood freely given yields more stable magic, while blood forcibly taken produces more powerful, unpredictable results.

Blood can be harvested from any slain or wounded creature that has blood, or volunteered by any player character at the cost of `1` point of Stamina.

| Druidism | Hallucinogens |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | 1 watch |
| Materials | Salt |
| Effects | Mix and consume a hallucinogenic concoction which increases your Fortitude by `BPL`. |

| Druidism | Stimulant |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | 1 watch |
| Materials | Salt |
| Effects | Mix and consume a stimulating concoction which negates the skill modifier from Fatigue for one watch. |

| Druidism | Healing Herbs |
|-|-|
| Difficulty | |
| Target | One character |
| Duration | Instant |
| Materials | Salt |
| Effects | Prepare and apply a herbal paste that heals one point of Fatigue. |

| Druidism | Barkskin |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | See effects |
| Materials | Blood |
| Effects | *Blood magic.* Your skin hardens to a bark-like substance that increases your Armor Value by `BPL`. Only usable while wearing no armor or Light armor. NPC disposition may be lowered while in this state. TODO Blood |

| Druidism | Bloodbriar |
|-|-|
| Difficulty | |
| Target | Any reasonably sized passage |
| Duration | Permanent |
| Materials | Blood |
| Effects | *Blood magic.* Thick, barbed vines sprout out of the ground and block a connection, letting only the caster and persons close to them pass. TODO |

| Druidism | Acid Spray |
|-|-|
| Difficulty | |
| Target | One character in or entering your area |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Using druidic powers, spit a spray of thick, caustic acid from your mouth at a character. TODO |

| Druidism | Whip of Thorns |
|-|-|
| Difficulty | |
| Target | One character in or entering your area |
| Duration | |
| Materials | |
| Effects | |

| Druidism | Swarm of Insects |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | |
| Materials | |
| Effects | Summon a swarm of biting insects that surround you. Insect bites cause `1` Pain each round to any characters, up to `BPL`, engaged in melee combat with you. |

- Murder of Crows: Transform into a murder of crows and retreat, reforming in humanoid shape at totem
- Leshen Form: *Ritual.* *Blood magic.* Transform into a Leshen
- Preserving: *Ritual.* The target dead body will last up to `5` days before becoming

#### Runecraft

- Fire Rune: Weapon, activate, damage increased and type fire
- Rune of Power: Weapon/armor, increase base damage/AV by X, permanent
- Rune of Penetration: Weapon, add trait Penetration to weapon
- Rune of Protection: Shield, increase SV by X, permanent
- Rune of Deflection: Shield, if you'd take a critical hit, instead your shield shatters
- Rune of Keeping: Equipment, absorb disrepair/shatter check or effect
- Exploding Rune: Floor, wall, object explodes in fire
- Rune of Accuracy: Ranged weapon, activate, if hit, hits targeted location

#### Artifice

- golems
- mana wells

### Alchemical Materials

Alchemical materials include the following.

- Reagents: Salt (), Sulfur () and Mercury ()
- Alloys: Metal, Dwarven and Gnomish

## Divinity and Divine Prayer

Anyone who has accepted the Divine to their heart is a Faithful. It is only necessary to pledge your soul to a Deity.

The Faithful of the Divine express their faith through piety and fervent prayers to their Deities, so that they might grant them Divine power at their hour of need. Prayer can take the form of a quick litany or that of a complex ritual. Further, the distilling and consecrating of *cordials* is practised.

While many claim to have done so, the Deities do not speak to mortals, and their will is perceived only indirectly through so-called *precepts*. No one knows exactly how this happens, but upon waking from slumber, the Faithful seem to possess absolute certainty of how they should conduct themselves.

### Precepts

A true Faithful walks a difficult path, where mortal needs and desires must be tempered by the will of the Divine.

A Faithful is always under a precept. Upon taking a [camp](time-and-space#camp), roll a `d20`. If the result is `11-20`, you receive a new, random precept. If the character prays for changing the precept, this roll has [advantage](characters#advantage-and-disadvantage).

| Precept | Obligations |
|-|-|
| Rancor | Walk among the heathen with fire and sword. Always choose the more severe and harsh judgment. |

### Favor and Disfavor

Whenever a Faithful acts upon a precept, whether honoring its obligations or either neglecting or even contravening them, they gain Favor or Disfavor.

A Faithful is not absolutely beholden to the precepts &mdash; they may choose to act according to their own judgment and morals instead.

However, if there is one thing the Deities do not tolerate, it appears to be Arcane magic. Whenever a Faithful casts an Arcane spell, they gain Disfavor.

### Oblivious Deities

At the end of each session, one Favor is forgotten by the deities, while Disfavor is not.

### Divine Prayer

There are two levels of zeal of prayers, *Pious* and *Fervent* prayer.

A Pious prayer is one where the supplicant offers their worship for a lesser favor from their Deity. Pious prayers have a target difficulty value.

A Fervent prayer is when the supplicant calls Divine Judgment upon themselves in recognition of their deeds and to grant a greater favor. Whatever the outcome, a Fervent prayer resets the accrued Favor and Disfavor.

#### Pious Prayer Resolution

To utter a divine prayer, you must first have memorized it.

Let `T` be a prayer's target difficulty and `S` your skill in divine prayer. To be able to attempt to utter this prayer, `T` must be *equal to or less than* `S + 10`.

Roll `d20` and add `S`. If the result is *greater than* `T`, the prayer has been Favored. Otherwise, the prayer has been Disfavored, and must roll `d10` on the prayer disfavor table, modified by `T - S - 10` (minimum modifier value is zero).

A natural `20` is Favored and natural `1` is Disfavored.

#### Fervent Prayer Resolution

Let Favor value `F` be twice the number of accrued Favors, and Disfavor value `D` be twice the number of accrued Disfavors.

If `F + D` is *greater than* `20`, then redefine `F` to be `20 - D`. Intuitively this means that Favors cannot cancel out Disfavors, while the opposite can happen.

Roll `d20` and let `R` be the result. Then, if `R` is *greater than* `20 - F` (in the top `F` possible die results), the prayer is Favored. If `R` is *less than or equal* to `D`, the prayer is Disfavored. Otherwise, the prayer is ignored.

When a Fervent prayer is Disfavored, you must roll `d12 + D` on the prayer disfavor table.

Whatever the outcome, accrued Favor and Disfavor are reset.

> **Example**
>
> A character has accrued three Favors and one Disfavor. Hence the Favor value is 2 × 3 = 6 and Disfavor value is 2 × 1 = 2. The die roll result is 14, and the prayer is unfortunately ignored. If the roll value had been just one higher, the prayer would have been Favored (15 > 20 - 6).

#### Prayer Disfavor

| Roll | Result |
|-:|-|
| 1&ndash;10 | Prayer is ignored without further effect. |
| 11 | Supplicant suffers 1 pain. |
| 12 | Supplicant suffers 2 pain. |
| 13 | Supplicant suffers 1 pain and starts [bleeding](combat#critical-wound-effects). |
| 14 | Supplicant is [incapacitated](combat#incapacitation) and starts [bleeding](combat#critical-wound-effects). |
| 15 | Supplicant is [incapacitated](combat#incapacitation), starts [bleeding](combat#critical-wound-effects) and permanently loses `1` WIL. |
| 16&ndash;18 | Supplicant is instantly killed (lost `1` WIL if resurrected). |
| 19&ndash;20 | Supplicant is instantly killed, and their body is burned to cinder. |

### Divine Rites

#### Rite of Life

- Lay on Hands: Touch single target heal X Fatigue
- Crucible of Pain: Ranged single target cause 1 Pain, reduce Fortitude by X
- Inner Resolve: Touch increase Fortitude by X
- assist trauma check by X
- Bloodstill: stop bleeding of a conscious character
- Recorporation: restore a limb
- nullify arm/leg critical effects during a combat
- Stasis: Delay death checks, sustained

#### Rite of Death

- Smite: Ranged single target cause head critical hit
- Withering: Ranged single target reduce Crit limit by X
- Drain: Self restore Stamina by draining a living, incapacitated humanoid creature
- Cadaver: a fresh corpse will sustain a dead character for resurrection for X days
- Resurrection: resurrect a dead character
- Banish: summoned spirits

#### Rite of Truth

- Charm
- Compulsion
- Blessing: Consume blessing to be able to reroll any roll
- Revelation/Psychic Shock: cause incapacitation
- Noosphere: sense (approximate number/location/xxx of humanoid) minds in the vicinity

#### Rite of Cordials

- healing
- melee buff
- pain suspend

### Sacred Materials

[&laquo; Table of Contents](..)

[&raquo; Time and Space](time-and-space)
