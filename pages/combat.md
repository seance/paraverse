# Combat

Combat is initiated when a character attacks another character, and is resolved in combat turns, during which each character can do actions.

## Combat round

During a combat round, each character acts simultaneously. Different *actions* are grouped into *turn phases*, which occur in order.

### Combat actions

During a combat round, a character can take one of the following actions.

- Attack another character (melee or ranged)
- Move to an adjacent [area](#TODO)
- Perform miscellaneous action (e.g. a skill check)

In addition, at the start of the round, a character may draw a weapon, or switch to another weapon as a free action.

### Combat phases

The combat phases are as follows.

| Phase | Notes |
|-|-|
| Planning | Each player character decides what they want to do in this round, and tell the Game Master. The Game Master decides actions for each of the NPCs. |
| Ranged combat | Ranged combat, whether using marksman or throwing weapons, is resolved using the [ranged combat resolution](#TODO) rules. |
| Melee combat | Melee combat is resolved using the [melee combat resolution](#TODO) rules. |
| Magic and divinity | Magical spells and divine prayers are resolved. |
| Miscellaneous actions | Other actions, such as climbing a wall, are resolved. A character being attacked while performing such action has [disadvantage](./characters#advantage-and-disadvantage) in both that action and evading the attack. |
| End phase | End-of-turn effects, such as bleeding, are applied. |

All actions in a phase are resolved simultaneously, i.e. if two characters fire arrows at each other, and the first arrow kills its target, the second attack is still resolved normally.

Movement occurs simultaneously with other phases, and depends on the actions of characters, at the discretion of the Game Master.

### Assignment

Characters who share the same [area](#TODO), or move into it, can engage in melee combat.

Generally, one character can opt to fight a single opponent. However, multiple characters are allowed to target a single character, when there are no unengaged targets nearby. In such a case, a single *skirmish* will have multiple participants on one side (other effects may allow there to be multiple characters on both sides).

The process of determining which character is in which skirmish is called assignment, and depends on the relative locations of the various characters and the Game Master's discretion.

The particular situation allowing, player characters should generally be allowed to pick their assignments first, with extra NPCs taking their picks after.

### Ranged attack resolution

A ranged attack is resolved during the appropriate phase as follows.

1. The attacker rolls `d20` and adds either the [Marksman or Throwing skill](./characters#list-of-skills) modifier depending on the weapon type
1. The defender rolls `d20` and adds the [Evasion skill](./characters#list-of-skills) modifier and [shield](#TODO) modifier, if using a shield.
1. If the attack roll is *higher* than the defense roll, the attack hits. See [attack damage multiplier](#TODO). Otherwise, the attack misses, and the resolution ends.
1. Calculate and apply pain using [damage resolution](#TODO)
1. Determine and apply critical wounds using [wounds resolution](#TODO)

### Melee skirmish resolution
