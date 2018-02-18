[&laquo; Table of Contents](..)

# Quest and Experience

## Quests

Quests are the scenarios crafted by the Game Master, which give the player characters purpose in the world.

Quests are characterized by *objectives*, which are goals that the group needs to fulfill to have completed the quest or scenario.

In Paraverse, experience points are gained solely by the completion of quest objectives. Slaying monsters, succeeding in difficult skill checks etc. do not confer experience points (XP).

### Primary Objectives

Primary objectives are goals that *must* be met for a quest to progress.

These are the story carrying medium, that set the backbone of a scenario. If possible, objectives should be set in general terms that allow players to achieve the goal through various means.

The next primary objective or objectives should always be explicitly clear. For example, finding a crucial clue must not rely on a skill check, since this would create a kind of paradox where the characters fail to follow the thread of the story &mdash; this is where secondary objectives come in.

Suggested XP rewards for completing primary objectives are detailed below.

| Primary objective | Reward XP |
|-|-:|
| Intermediate objective | 2-3 |
| Scenario objective | 5-10 |

### Secondary Objectives

Secondary objectives are goals which are not necessary to fulfill.

They can be simple "bonus" tasks that yield rewards in [wealth](wealth) or [equipment](equipment), but they can also completely change the tone of the adventure. Perhaps the poor widower looking to reclaim their inheritance is an evil doppelgänger instead?

Suggested XP rewards for completing secondary objectives are detailed below.

| Primary objective | Reward XP |
|-|-:|
| Bonus objective | 1 |
| Story objective | 3-5 |

## Experience

### Group Experience

In Paraverse, experience is not gained by individual characters, but rather by the group as a whole. Each character's experience point pool is equal to that of the group.

If a player characters dies, a new character created by that player will have starting XP pool equal to that of the group, as noted in [character creation](charaters#character-creation).

### Character Progression

When a group receives experience points, or XP, they must be assigned to [skills](characters#skills). This is usually done independently by the players between sessions. Experience points *cannot* be left unspent in a "reserve" pool.

#### Assigning XP

Assigning XP to a skill raises the value of that skill, along a curve with diminishing returns as detailed below.

Experience skill modifier `M` for given amount of `XP` is equal to `⌊√(4 × XP + 1)⌋ - 1` (i.e. the *floor* of the *square root* of four times `XP` plus one, minus one). For convenience, these values are tabulated below.

| Spent XP | Skill modifier |
|-:|-:|
| 1 | 1 |
| 2&ndash;3 | 2 |
| 4&ndash;5 | 3 |
| 6&ndash;8 | 4 |
| 9&ndash;11 | 5 |
| 12&ndash;15 | 6 |
| 16&ndash;19 | 7 |
| 20&ndash;24 | 8 |
| 25&ndash;29 | 9 |
| 30 | 10 |

This corresponds to the first two skill increases each costing 1 XP, the next two 2 XP each, the next two 3 XP each and so on.

Experience modifier to a skill is capped at `+10`. Thus a character with a primary stat value `P` governing a skill has maximum (natural) skill modifier `+P` for that skill, since a skill's starting value is `P - 10`. Other modifiers may extend this value.

#### Half Round Up

A single skill within a [skillset](characters#list-of-skills) (e.g. Martial) can have at any time at most half, rounded up, of the total XP spent on that skillset (including the newly assigned XP).

The total amount of XP assigned to a skillset is the sum of the XP assigned to individual skills in that skillset.

> **Example**
>
> A character has spent a total of 9 XP in Martial skills. Thus the maximum amount of XP which may be assigned to a single Martial skill, e.g. One-handed, is ⌈9 / 2⌉ = 5.
>
> Another character assigns their first XP to some skill in the Cloak-and-dagger skillset. The total XP assigned to that skillset is then 1 XP, and the skill maximum is ⌈1 / 2⌉ = 1, making the assignment legal.

#### Acquiring Abilities

When assigning XP into a skillset, the total amount of XP for that skillset may enable you to acquire an Ability. See [abilities](characters#abilities) for details.

[&laquo; Table of Contents](..)

[&raquo; Game Props](game-props)
