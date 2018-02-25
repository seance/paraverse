[&laquo; Table of Contents](..)

# Sorcery and Divinity

Sorcery and Divinity are supernatural powers whose origins are shrouded in mystery.

The arcane arts of Sorcery take a more scientific, direct approach to manipulating these forces. Divinity is a more spiritual approach, whose proponents believe that all magical force derives from Deities who grant power to those who are deemed worthy through unwavering faith and worship.

In any case, great exertion of willpower is necessary for both spellcasting and divine prayer. Some arcanists even purport this as evidence that priests and monks of the divine faiths are actually channeling arcane power, just like sorcerers. Such claims, naturally, are condemned as heretical ravings by the faithful.

## Sorcery and Spellcasting

A sorcerer reaches with his mind to the Source and draws arcane power through raw willpower, bending the fabric of the universe to their will.

To become a sorcerer, no formal education is necessary, although it can be beneficial. It simply suffices to unlock one of the Aspects, or Schools, of sorcerous magic. But beware, for the flow of magic is treacherous, and will burn the careless dabbler to cinder in the blink of an eye.

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
| 13 | Caster suffers 1 pain and starts [bleeding](combat#critical-wound-effects). |
| 14 | Caster is [incapacitated](combat#incapacitation) and starts [bleeding](combat#critical-wound-effects). |
| 15 | Caster is [incapacitated](combat#incapacitation), starts [bleeding](combat#critical-wound-effects) and permanently loses `1` WIL. |
| 16&ndash;18 | Caster is instantly killed (lost `1` WIL if resurrected). |
| 19&ndash;20 | Caster is instantly killed, and the body is burned to cinder. |

### List of Spells

| Evocation | Difficulty | Target | Range | Effect |
|-|-:|-|-|-|
||||||

## Divinity and Divine Prayer

Anyone who has accepted the Divine to their heart is a Faithful. It is only necessary to pledge your soul to a Deity to unlock the aspect of Faith.

The Faithful of the Divine express their faith through piety and fervent prayers to their Deities, so that they might grant them Divine power at their hour of need.

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

However, if there is one thing the Deities do not tolerate, it appears to be Sorcery. Whenever a Faithful casts a sorcerous spell, they gain Disfavor.

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
| 19&ndash;20 | Supplicant is instantly killed, and the body is burned to cinder. |

### List of Prayers

| Prayer | Zeal | Target | Range | Effect |
|-|-|-|-|-|
| Smite | Fervent | 1 | | Smite the heathen. Game Master discretion. |

[&laquo; Table of Contents](..)

[&raquo; Time and Space](time-and-space)
