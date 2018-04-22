[&laquo; Table of Contents](..)

# Arcana and Spellcasting

An Arcane sorcerer reaches with his mind to the Source and draws arcane power through raw willpower, bending the fabric of the universe to their will. A druid draws on the power of untamed nature through the mind's eye or blood rituals. Dwarven runesmiths craft runes from alchemical reagents, shaped to secret words of power branded onto weapons and armor. Gnomish artificers build mechanical constructs and imbue them with magic.

To become an arcanist, no formal education is necessary, although it can be beneficial. It simply suffices to unlock one of the Aspects, or Schools, of Arcane magic. But beware, for the flow of magic is treacherous, and will burn the careless dabbler to cinder in the blink of an eye.

## Spellcasting Resolution

To cast a spell, you must first have memorized it.

Let `T` be a spell's target difficulty and `S` your skill in that spell's aspect. To be able to attempt to cast this spell, `T` must be *equal to or less than* `S + 10`.

Roll `d20` and add `S`. If the result is *greater than* `T`, you will have successfully cast the spell. Otherwise, you have failed in casting the spell, and must roll `d10` on the spell failure table, modified by `T - S - 10` (minimum modifier value is zero).

A natural `20` is a success and natural `1` is a failure.

### Spell Failure

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

## Arcane Aspects

### Evocation

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

### Abjuration

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

### Conjuring

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

### Transcendence

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

| Transcendence | Spell Masking |
|-|-|
| Difficulty | |
| Target | Single active spell |
| Duration | Duration of target spell |
| Materials | &mdash; |
| Effects | Neither the Sense Magic spell nor magic-sensing characters can detect the target spell, or determine its cast strength. |

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

[//]: # (temporal gap)
[//]: # (antimagic aura)

### Druidism

Druidism draws power from the living force of untamed nature through herbs, rituals and blood magic. Nature manifests not as a gentle nurturer, but as a brutal contest for survival, fitness and fertility.

#### Biome Power Level

Druidic magic waxes and wanes in power with the verdancy of the local biome. Each Place of Interest's verdancy is determined by the Game Master. The resulting Biome Power Level is referenced as `BPL` in the spell descriptions.

| Verdancy | BPL |
|-|-|
| Barren | 0 |
| Stunted | 1 |
| Verdant | 3 |
| Lush | 5 |

#### Blood Magic

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

### Runecraft

Deep in their mountainside fortresses, the Dwarves have long devised their secret language. Runes written in this language, when branded on steel using alchemical means, gives weapons, shields and armor special powers and qualities.

Since the Dwarves will not reveal the secrets of these runes to outsiders, generally only Dwarf characters may unlock the Runecraft Aspect.

Each piece of equipment (weapon, shield or armor) may only have one rune branded onto it at a time, unless otherwise specified.

| Runecraft | Fire Rune |
|-|-|
| Difficulty | |
| Target | Weapon |
| Duration | Until spent |
| Materials | 1 Sulfur |
| Effects | The wielder of the target weapon may activate the rune at any time. When activated, the next hit will have `+3` base damage and the damage type of the attack is [fire](combat#damage-types), after which the rune is spent. If the fight ends before you hit, the rune is also spent. |

| Runecraft | Rune of Might |
|-|-|
| Difficulty | |
| Target | Weapon |
| Duration | Permanent |
| Materials | 1 Sulfur |
| Effects | Increase target weapon base damage by `1`. Its wield cost is unchanged. |

| Runecraft | Rune of Penetration |
|-|-|
| Difficulty | |
| Target | Weapon |
| Duration | Permanent |
| Materials | 1 Sulfur |
| Effects | Adds the trait *Penetration* to target weapon. |

| Runecraft | Rune of Protection |
|-|-|
| Difficulty | |
| Target | Shield |
| Duration | Permanent |
| Materials | 1 Mercury |
| Effects | Increase target shield's shield value by `2`. Its wield cost is unchanged. |

| Runecraft | Rune of Deflection |
|-|-|
| Difficulty | |
| Target | Shield |
| Duration | Permanent |
| Materials | 1 Mercury |
| Effects | If you are about to suffer a critical wound while wielding the target shield, the shield shatters instead. You still suffer pain from the hit as usual. The shield is permanently destroyed. |

| Runecraft | Rune of Keeping |
|-|-|
| Difficulty | |
| Target | Weapon, Shield or Armor |
| Duration | Until spent |
| Materials | 1 Mercury |
| Effects | The rune absorbs the next durability check for the target piece of equipment, and is then spent. Also absorbs any spell or prayer that would shatter your shield, and is then spent. This rune cannot coexist with the Rune of Deflection. |

| Runecraft | Exploding Rune |
|-|-|
| Difficulty | |
| Target | Any surface |
| Duration | Permanent, until triggered |
| Materials | 1 Sulfur |
| Effects | When a character not designated by the caster steps on or touches the rune, it explodes in a fireball. The victim makes a Dexterity save, suffering `20` points [fire](combat#damage-types) damage on failure or half as much on success. The rune is [difficult](characters#skill-target-difficulties) to detect using normal means. |

| Runecraft | Rune of Accuracy |
|-|-|
| Difficulty | |
| Target | Ranged weapon |
| Duration | Until spent |
| Materials | 1 Sulfur |
| Effects | The wielder of the target weapon may activate the rune at any time. When activated, the next hit with the weapon will hit the body location, or other precise target, designated by the wielder. The rune is then spent, which also occurs if you do not hit before the fight ends. |

[//]: # (channel rune: deliver touch magic via weapon attack)

### Artifice

Artifice is the Gnomish art of producing magically imbued artifacts of exceedingly finely crafted mechanical inner workings. No other races can match the clockwork precision required to make these constructs, thus generally only Gnome characters may unlock the Artifice Aspect.

#### Golem Construction

The construction of true golems is a deeply involved art and science, which even few Gnomes master. Instead, mechanically and magically gifted Gnomish adventurers find much more utility in so-called *mini-golems*, which are [constructs](combat#constructs) the size of a buckler shield and come in several varieties.

A mini-golem consists of a metallic alloy *chassis*, or frame, and any number of *modules* which give the golem capabilities beyond its basic logic functions.

To construct a chassis, the [Traps/devices](characters#list-of-skills) skill is used in conjunction with *alloys* determined by the desired chassis properties, including module slots.

##### Hexapod Chassis

Hexapod golems move on the ground and can climb and jump. They have [Athletics](characters#list-of-skills) 5 and [Evasion](characters#list-of-skills) 5. Their Armor Value (AV) and Structural points (S) depend on the construction as follows.

| Alloys | Slots (M) | AV/S | Durab. | Diff. |
|-|-:|-:|-:|-:|
| Metal (`1 + M`) | 1&ndash;3 | 10/50 | 12 | `14 + M` |
| Dwarven (`1 + M`) | 1&ndash;3 | 13/80 | 15 | `16 + M` |
| Gnomish (`1 + M`) | 4&ndash;6 | 10/100 | 12 | `18 + M` |
| Gnomish (`M`), Dwarven (`3`) | 4&ndash;6 | 15/150 | 15 | `20 + M` |

##### Aquatic Chassis

Aquatic golems move in water and perform Athletics (swim) checks only in very difficult conditions. They have [Athletics](characters#list-of-skills) 10 and [Evasion](characters#list-of-skills) 7. Their Armor Value (AV) and Structural points (S) depend on the construction as follows.

| Alloys | Slots (M) | AV/S | Durab | Diff |
|-|-:|-:|-:|-:|
| Metal (`1 + M`) | 1&ndash;3 | 10/40 | 12 | `14 + M` |
| Dwarven (`1 + M`) | 1&ndash;3 | 13/65 | 15 | `16 + M` |
| Gnomish (`1 + M`) | 4&ndash;6 | 10/80 | 12 | `18 + M` |
| Gnomish (`M`), Dwarven (`3`) | 4&ndash;6 | 15/120 | 15 | `20 + M` |

##### Aerial Chassis

Aerial golems use four mechanical wings to become airborne, and can maneuver at a low altitude. They have [Evasion](characters#list-of-skills) 10. Their Armor Value (AV) and Structural points (S) depend on the construction as follows.

| Alloys | Slots (M) | AV/S | Durab | Diff |
|-|-:|-:|-:|-:|
| Metal (`1 + M`) | 1&ndash;2 | 6/30 | 12 | `14 + M` |
| Dwarven (`1 + M`) | 1&ndash;2 | 9/40 | 15 | `16 + M` |
| Gnomish (`1 + M`) | 3&ndash;4 | 6/55 | 12 | `18 + M` |
| Gnomish (`M`), Dwarven (`3`) | 3&ndash;4 | 9/80 | 15 | `20 + M` |

##### Modules

Modules are constructed using the Artifice skill and alchemical reagents required.

| Module | Reagents | Function | Diff |
|-|-|-|-:|
| Telepathic Vision | 1 Sulfur | Allows the operator to telepathically see through the module. Controlling the golem in combat through the module is an action. | 15 |
| Manipulators | 1 Salt | Enables the golem to open unlocked doors, windows, carry small objects, pull rope etc. | 15 |
| Hardened Armor | 1 Salt | Increase golem's Armor Value by 50%. | 15 |
| Coalescing Lens Array | 1 Sulfur | Store a single Arcane spell. The artificer must cast the spell into the module. The module can then attempt to cast the spell using skill modifier `S`. A failed spell cast attempt renders the module inoperable, until it has received basic maintenance. | `15 + S` |
| Static Resonator | 1 Mercury | Provides the golem 1 Sustain point. | 20 |
| Enhanced Logic Unit | 1 Sulfur | Enables conditional and more complex instructions to the golem. | 15 |
| ... | ... | ... | ... |

#### Golem Operation

A mini-golem can be carried in the sidearm equipment slot.

A golem can be given a set of simple instructions &mdash; guard this area, follow me, destroy enemies, protect a target &mdash; which the golem will then execute. Golems equipped with Telepathic Vision can also be directly controlled.

After each operation, a durability check needs to be made on the chassis.

Structural damage can be repaired using one unit of the alloy most used in the chassis and a [Field repair](characters#list-of-skills) check during a [rest](time-and-space#rest).

#### Talismans

Talismans are small artifacts that have various purposes.

| Talisman | Reagents | Description | Diff |
|-|-|-|
| Mana Well | 1 Sulfur | Store `X` points to a maximum of `3`. The bearer of a Mana Well can consume the well when casting a spell to gain `+X` to the skill check. Only one well can be consumed per spell cast. | `10 + 5X` |
| ... | ... | ... | ... |

## Alchemical Materials

Alchemical materials include the following.

- Reagents: Salt (&#x1f714;), Sulfur (&#x1f70d;) and Mercury (&#x1f710;)
- Alloys: Metal, Dwarven and Gnomish

Reagents can be purchased from Alchemists and found in the world.

[&laquo; Table of Contents](..)

[&raquo; Divinity and Prayer](divinity-and-prayer)
