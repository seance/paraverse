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

## Non-Combat (Unhurried?) Spells and Prayers

Cannot be cast in combat, need some time, but won't progress the watch.

## Ritual Spells and Prayers

A spell or prayer with the *Ritual* keyword require a more complex ritual cast or recital. Such spells or prayers take one [watch](time-and-space#watches) to cast or recite.

## Concentrating on a Spell or Prayer

Some spells or prayers have duration marked as Concentration. These spells or prayers remain in effect while the caster is actively concentrating.

Taking a skill check other than Evasion, suffering pain or a critical wound or becoming incapacitated breaks concentration. Only one spell or prayer can be concentrated on at a time.

## Spell and Prayer Saves

A spell or a prayer may grant a save check to the target of the spell or prayer. The save check has a governing stat, e.g. Physique, whose modifier (stat value minus 10) is `S`. The caster's Willpower modifier is `W`.

The save is resolved as `d20 + S - W`. If the result is *greater than* 10, the save is successful. Otherwise the save has failed.

## Arcana and Spellcasting

An Arcane sorcerer reaches with his mind to the Source and draws arcane power through raw willpower, bending the fabric of the universe to their will. A druid draws on the power of untamed nature through the mind's eye or blood rituals. Dwarven runesmiths craft runes from alchemical reagents, shaped to secret words of power branded onto weapons and armor. Gnomish artificers build mechanical constructs and imbue them with magic.

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

| Abjuration | Fire Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Target gains [resistance](combat#damage-resistance) to [fire](combat#damage-types). |

| Abjuration | Frost Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Target gains [resistance](combat#damage-resistance) to [frost](combat#damage-types). |

| Abjuration | Acid Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Target gains [resistance](combat#damage-resistance) to [acid](combat#damage-types). |

| Abjuration | Poison Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Target gains [resistance](combat#damage-resistance) to [poison](combat#damage-types). |

| Abjuration | Whirlwind |
|-|-|
| Difficulty | |
| Target | Self, moves with you and affects the area |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | Non-magical ranged attacks passing through your area (fired from, to or through) have disadvantage. |

| Abjuration | Warding Glyph |
|-|-|
| Difficulty | |
| Target | Area of resting |
| Duration | Rest/camp |
| Materials | &mdash; |
| Effects | Any character not designated by the caster entering the warded area causes a mental notice for the caster. See [ambushes](environment#ambushes) while resting. |

| Abjuration | Ambush Ward |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | The caster cannot be ambushed, unless the ambushers are magically masked from detection. |

| Abjuration | Mind Shield |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | *Psychic* spells or prayers cannot effect you. Spells or prayers cannot modify your secondary stats, unless you allow them to. |

| Abjuration | Containment |
|-|-|
| Difficulty | |
| Target | Touch, an enclosed existing structure with a door or latch |
| Duration | Permanent, until destroyed |
| Materials | Mercury |
| Effects | Encloses an existing structure in a containment field, which cannot be forced from the inside using physical force. The doorway is locked and is [difficult](characters#skill-target-difficulties) to lock pick. From the outside, the Containment becomes a [construct](combat#constructs) with 200 structure and AV 15. The caster can open and close the doorway without a key at will. |

| Abjuration | Magic Suppressor |
|-|-|
| Difficulty | |
| Target | Touch |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | All the target's spell and prayer saves have a `+2` modifier. |

| Abjuration | Spell Breaker |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Sustained(1), see effects |
| Materials | &mdash; |
| Effects | Absorbs the next single target spell or prayer cast at you, nullifying its effects, then dissipates. |

[//]: # (end/prevent magical condition)

#### Conjuring

Conjuring is the area of Sorcery that studies the very fabric of existence itself, and how sentient minds and material bodies interact and weave in and out of its myriad manifestations and planes. Illusions and Planarism are key areas of study.

| Conjuring | Illusory Wealth |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Momentary |
| Materials | &mdash; |
| Effects | *Illusion.* Manifest 1/2/5 illusory wealth, that can be used to gamble or purchase wares from merchants. Targets of this spell make a Cognition save. On a successful save, they perceive the illusion, and may take offense, at the least lowering their [disposition](characters#npc-disposition). |

| Conjuring | Muted Echo |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Illusion.* Your echo on the material plane is muted. Perform a Sneaking check. On partial failure, there is no disturbance. |

| Conjuring | Soothing Whispers |
|-|-|
| Difficulty | |
| Target | Single character in your area |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Illusion.* The target, whose alertness is [on duty](characters#npc-alertness), becomes [relaxed](characters#npc-alertness). Other NPCs interacting with this character may try to revitalize them. |

| Conjuring | Summon Wisp |
|-|-|
| Difficulty | |
| Target | Your area or adjacent |
| Duration | 1 round |
| Materials | &mdash; |
| Effects | *Summoning.* Summon an ethereal wisp from another plane of existence. Guards in the target area or overlooking it become [distracted](characters#npc-alertness) for the duration of the spell, but become [suspicious](characters#npc-alertness) afterwards. |

| Conjuring | Summon Fiend |
|-|-|
| Difficulty | |
| Target | Your area |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | *Summoning.* Summon a fiendish creature from some hellish plane of existence. The Fiend will obey your (very simple) commands, as long as there are some characters for it to kill. For any round there are not, roll `1d4`. On a `1` the Fiend will instead attack an ally. TODO: Fiend stats |

| Conjuring | Phase Shift |
|-|-|
| Difficulty | |
| Target | Ranged, Marksman targeting rules |
| Duration | 1 round |
| Materials | &mdash; |
| Effects | *Planar.* The target character, whether friend or foe, is shifted for one round (the next round) to another phase of reality. While in the other phase, they can perform actions as normal, but cannot move or affect anything in the ordinary phase, and cannot be affected. |

| Conjuring | Fade |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Concentration |
| Materials | &mdash; |
| Effects | *Planar.* You partially fade from the material plane, gaining [resistance](combat#damage-resistance) to all physical damage. |

| Conjuring | Blink |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Sustained(1) |
| Materials | &mdash; |
| Effects | *Planar.* You may trigger blink any time you would be or are engaged in melee combat, consuming the spell and performing a micro-teleportation behind your attacker. You become disengaged, effectively denying the attacker's [zone of control](time-and-space#zone-of-control). The teleportation cannot pass through obstructions. |

| Conjuring | Planar Paths |
|-|-|
| Difficulty | |
| Target | Group |
| Duration | Varying |
| Materials | &mdash; |
| Effects | *Planar.* Following little planar shortcuts invisible to the untrained eye, reduce travel time on a path previously traveled by one [watch](time-and-space#watches). |

| Conjuring | Phase Leap |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Instant |
| Materials | &mdash; |
| Effects | *Planar.* Perform an Athletics (jumping) check with [advantage](characters#advantage-and-disadvantage). |

| Conjuring | Phase Tunnel |
|-|-|
| Difficulty | |
| Target | Your area |
| Duration | Momentary |
| Materials | 1 Mercury per thing teleported |
| Effects | *Planar.* *Ritual.* The Phase Tunnel has two parts. First, you create a Mark by casting the Phase Tunnel without the material component. Then, at any location from which the Mark is reachable without passing through obstacles, Phase Tunnel can be recast with `X` material components. The Phase Tunnel can then instantaneously teleport `X` characters or other, medium sized objects to the Mark while the tunnel is open. |

[//]: # (spirit possession)

#### Transcendence

Transcendence is the meta-magical dimension of Sorcery that studies magic itself, as well as the non-material aspects of reality, including time.

| Transcendence | Flash Cast |
|-|-|
| Difficulty | |
| Target | Another spell |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Flash Cast is joined with another spell cast in combat. Their difficulty values are combined. The joined spell takes effect before the Ranged attack phase. |

| Transcendence | Counter Magic |
|-|-|
| Difficulty | |
| Target | Locale |
| Duration | Sustained(3) |
| Materials | &mdash; |
| Effects | Counter Magic produces a field of magical energy that resists the shaping of all other spells. All spells cast under the influence of Counter Magic have a difficulty of at least TODO. The field extends over the entire locale. |

| Transcendence | Sense Magic |
|-|-|
| Difficulty | |
| Target | Your area or adjacent |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Sense all magical spells in the targeted area that have not been Masked, and their cast strengths. |

| Transcendence | Dispel |
|-|-|
| Difficulty | Varying |
| Target | Single active spell |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Dispel an active spell (not an active magically caused effect, like the fire spread from a fireball), by succeeding in this spell against that spell. The difficulty value of this spell is the cast strength of the target spell. |

| Transcendence | Masking |
|-|-|
| Difficulty | |
| Target | Single active spell  |
| Duration | Duration of target spell |
| Materials | &mdash; |
| Effects | Neither the Sense Magic spell nor magic-sensing characters can detect the target spell, nor determine its cast strength. |

| Transcendence | Force Reflux |
|-|-|
| Difficulty | |
| Target | Single character in your area or adjacent  |
| Duration | Instant |
| Materials | &mdash; |
| Effects | A short circuited magical link forms between you and the target, creating a excruciating reflux of magical force. The target makes a Willpower save. On failure, the target takes `X` points of pain where `X` is the target's highest Arcane skill modifier, and you take `X / 2` points of pain (rounding up). On a success, `X` is halved to a minimum of 1. |

| Transcendence | Haste Self |
|-|-|
| Difficulty | Varying |
| Target | Self |
| Duration | X rounds |
| Materials | 1 Sulfur per round |
| Effects | You Haste yourself, allowing you to move at double speed, traversing up to two areas each round, and to physically attack twice each round. While attacking or evading, you have [advantage](charaters#advantage-and-disadvantage) . You can still only cast one spell per round. The difficulty of this spell is TODO + `X`. |

| Transcendence |  |
|-|-|
| Difficulty | |
| Target |  |
| Duration |  |
| Materials | &mdash; |
| Effects |  |

[//]: # (temporal gap)
[//]: # (antimagic aura)

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
| Target | Touch |
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
| Target | Single character in your area |
| Duration | Instant |
| Materials | &mdash; |
| Effects | Using druidic powers, you spit a spray of thick, caustic jelly from your mouth at the target. The target makes a Dexterity save. On a failure, the target takes 15 points of acid damage and their armor becomes in disrepair. On a success, they take 10 points of acid damage. |

| Druidism | Whip of Thorns |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Current fight |
| Materials | Blood |
| Effects | *Blood magic.* A thorned whip of vine sprouts from your hand. The whip is a one-handed weapon, has base damage `6 + BPL`, damage type piercing, wield cost of 6 and the trait *Curving*. The blood from lashing your foes nourishes the vine, but after the fight, the vine withers and dies. |

| Druidism | Swarm of Insects |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | |
| Materials | &mdash; |
| Effects | Summon a swarm of biting insects that surround you. Insect bites cause `1` Pain each round to characters, up to `BPL` in number, engaged in melee combat with you. After the first fight, the insects scatter. You may also dismiss the spell at any time. NPCs may be upset if you go indoors while this spell is active. |

| Druidism | Murder of Crows |
|-|-|
| Difficulty | |
| Target | Self |
| Duration | Momentary |
| Materials | &mdash; |
| Effects | You carry a small totem made of wood and carved bone that can be left anywhere in the current locale. When this spell is cast, you are transformed into a murder of crows, disengaging from any melee skirmish, and fly a maximum of `BPL` areas toward your totem before reforming in humanoid shape. |

| Druidism | Nature's Preserving |
|-|-|
| Difficulty | |
| Target | Touch, a dead body |
| Duration | 5 days |
| Materials | &mdash; |
| Effects | *Ritual.* The target body will last up to five days before becoming unresurrectable. |

| Druidism | Tranquil Grove |
|-|-|
| Difficulty | |
| Target | Your area |
| Duration | 2 watches |
| Materials | 1 Salt |
| Effects | The camp ground becomes tranquil and refreshing. A full [camp](time-and-space#camp) can be taken in just 2 watches. This spell can only be cast if the current biome is Verdant or Lush. |

[//]: # (leshen form, ritual, blood magic)

#### Runecraft

- Fire Rune: Weapon, activate, damage increased and type fire
- Rune of Power: Weapon/armor, increase base damage/AV by X, permanent
- Rune of Penetration: Weapon, add trait Penetration to weapon
- Rune of Protection: Shield, increase SV by X, permanent
- Rune of Deflection: Shield, if you'd take a critical hit, instead your shield shatters
- Rune of Keeping: Equipment, absorb disrepair/shatter check or effect
- Exploding Rune: Floor, wall, object explodes in fire
- Rune of Accuracy: Ranged weapon, activate, if hit, hits targeted location
- channel rune: deliver touch magic via weapon attack

#### Artifice

Golems:
- any chassis: 1-N module slots: X armor, Y structural, Z durability, W evasion
- hexapod chassis: high armor, structural, stealthy
- aquatic chassis: high armor, structural, undetectable
- aerial chassis: low armor, structural, cause disturbance
- armor module: increase armor by X
- spell module: stores 1 spell, artificer casts the spell to store it in golem. Golem can cast spell until it fails casting - the module is exhausted until the golem is maintained.
- sustain module: generate 1 sustain point
- manipulator module: carry items, manipulate objects
- enhanced logic module: more complicated instructions

Talismans:
- mana well, X points: consume well to add X to a spell cast check

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
- sacrifice: cause X points of pain to yourself; ranged single target takes 10X damage
- sanctity: sustain autosucceed in a WIL save

#### Rite of Death

- Smite: Ranged single target cause head critical hit
- Withering: Ranged single target reduce Crit limit by X
- Drain: Self restore Stamina by draining a living, incapacitated humanoid creature
- Cadaver: a fresh corpse will sustain a dead character for resurrection for X days
- Resurrection: resurrect a dead character
- Banish: summoned spirits
- query a corpse: gain info about how it died, some secret or something
- weaken saves: PHY or WIL

#### Rite of Truth

- Charm
- Compulsion
- Blessing: Consume blessing to be able to reroll any single roll
- Revelation/Psychic Shock: cause incapacitation
- Noosphere: sense (approximate number/location/xxx of humanoid) minds in the vicinity
- detect arcana (limited scope, no cast strength)
- Guidance: Consume guidance to add 1d4 to any skill check
- Judgment: ranged single target disadvantage to evasion
- melee single target has disadvantage on melee against you

#### Rite of Cordials

- healing
- melee buff
- pain suspend

### Sacred Materials

[&laquo; Table of Contents](..)

[&raquo; Time and Space](time-and-space)
