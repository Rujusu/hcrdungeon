---
{"dg-publish":true,"permalink":"/open-game/published/craft/rules/harvesting-creatures/"}
---

## Harvesting System
### Harvesting Rules
After a creature is slain, its components must be harvested quickly before their magic fades. There are five steps involved in this process.

#### Step 1 - Description

When a creature dies, the GM consults the harvest table corresponding to the creature’s type and determines which of the listed components are available to be harvested.

**Example:** In the example below, the party wishes to harvest a dragon they have slain. The GM consults the Dragon Harvest table and decides that the dragon has the following components on offer: 1 breath sac, 1 heart, 1 liver, 2 eyes, 2 horns, 4 pouches of claws, 4 pouches of teeth, 10 bones, as well as scales, blood, flesh, and fat. Because a young red dragon is CR 10, one can also harvest robust essence from it.

#### Step 2 - Harvest List

The harvesters then quickly decide what they want to harvest and in which order. This order is known as the harvest list.

**Example:** The party chooses to harvest the following components in the listed order: a pouch of teeth, two eyes, the breath sac, and then the essence.

#### Step 3 - Harvest DCs

After the party has created its harvest list, the GM calculates the Harvest DCs. They list out the chosen components in the order the party wishes to harvest them and sequentially add each Component DC to the total of all the previous Component DCs. The Component DC represents how hard a component is to harvest.

**Example Harvest List:**

| Component      | Component DC | Harvest DC        |
| -------------- | ------------ | ----------------- |
| Pouch of teeth | 10           | 10 (10)           |
| Eye (1)        | 5            | 15 (10+5)         |
| Eye (2)        | 5            | 20 (10+5+5)       |
| Breath sac     | 25           | 45 (10+5+5+25)    |
| Robust essence | 30           | 75 (10+5+5+25+30) |
#### Step 4 - Harvesting Check

The players make a Harvesting check. A Harvesting check is the combined total of two ability checks: an Assessment check and a Carving check.

#### Step 5 - Loot

Compare the result of the Harvesting check to the harvest list made in Step 3. If the Harvesting check’s result met or exceeded the Harvest DC for a component, that component is successfully harvested.

**Example:** A result of 37 means that everything except the breath sac and essence are acquired.

### Harvesting Overview
The harvesting process involves two main steps: Assessment and Carving. The Harvesting check is the summed total of two ability checks: one for Assessment and one for Carving. A single character can choose to make both checks; if they do so, they make these checks with disadvantage. The skill used for each check depends on the type of creature being harvested.

#### Creature Types and Associated Skills
| Creature Type | Assessment Skill (Intelligence) | Carving Skill (Dexterity) |
|---------------|----------------------------------|---------------------------|
| Aberration    | Arcana                           | Arcana                    |
| Beast         | Nature                           | Survival                  |
| Celestial     | Religion                         | Religion                  |
| Construct     | Investigation                    | Investigation             |
| Dragon        | Nature                           | Survival                  |
| Elemental     | Arcana                           | Arcana                    |
| Fey           | Nature                           | Arcana                    |
| Fiend         | Religion                         | Religion                  |
| Giant         | Medicine                         | Medicine                  |
| Humanoid      | Medicine                         | Medicine                  |
| Monstrosity   | Nature                           | Survival                  |
| Ooze          | Nature                           | Nature                    |
| Plant         | Nature                           | Nature                    |
| Undead        | Religion                         | Medicine                  |

#### Assessment
To correctly assess how best to extract and store creature components, a character must make an Intelligence check. The skill applicable to the check depends on the type of creature. A character attempting this Assessment check is known as the assessing harvester.

**Assessment Check:** `1d20 + Intelligence modifier + proficiency bonus (if applicable)`

#### Carving
Skill with a knife is the proven method of harvesting components. A character attempting to harvest a corpse makes a Dexterity check. The skill applicable to the check depends on the type of creature. A character attempting this Carving check is known as the carving harvester.

**Carving Check:** `1d20 + Dexterity modifier + proficiency bonus (if applicable)`

#### Harvesting Check
The Harvesting check is the combined result of the Assessment and Carving checks.

**Harvesting Check:** `Assessment check result + Carving check result`

#### Tools for Harvesting

Certain tools can assist with the Assessment and Carving checks, providing a bonus. Letting you add you proficiency bonus to the check again.

| Tool                  | Assessment Check | Carving Check |
| --------------------- | ---------------- | ------------- |
| Alchemist's Supplies  | Yes              | No            |
| Cook's Utensils       | No               | Yes           |
| Herbalism Kit         | Yes              | No            |
| Leatherworker's Tools | No               | Yes           |
| Poisoner's Kit        | Yes              | No            |
| Smith's Tools         | No               | Yes           |
| Tinker's Tools        | Yes              | No            |
| Woodcarver's Tools    | No               | Yes           |


#### Time Required by Creature Size
The time required to harvest materials from a creature varies based on its size.

| Creature Size | Time Required |
| ------------- | ------------- |
| Tiny          | 5 minutes     |
| Small         | 10 minutes    |
| Medium        | 1 hour        |
| Large         | 2 hours       |
| Huge          | 4 hours       |
| Gargantuan    | 12 hours      |

#### Helpers
The number of helpers that can assist in the harvesting process also varies based on the size of the creature. Helpers can reduce the total time required for harvesting by dividing the work among themselves.

| Creature Size | Maximum Number of Helpers |
| ------------- | ------------------------- |
| Tiny          | 0                         |
| Small         | 1                         |
| Medium        | 2                         |
| Large         | 4                         |
| Huge          | 6                         |
| Gargantuan    | 10                        |

**Adjusted Harvesting Time with Helpers:** The total time required for harvesting can be reduced based on the number of helpers. Each helper effectively divides the total harvesting time by the number of participants (including the primary harvester).

**Example:** Harvesting a Medium creature (1 hour) with 2 helpers (total 3 participants) would take approximately 20 minutes (1 hour / 3).

#### Spells and Buffs
For a spell or magical effect to influence the outcome of harvesting, it must affect a harvester for the entire duration of the Harvesting check. Spells with a duration of 1 minute, like *bless* and *guidance*, do not confer their bonuses to the result of the check. Spells like *enhance ability*, which lasts 1 hour, can confer their advantage to a Harvesting check as long as the spell begins before the check starts and does not end until after the check is completed.
### Essences
*Essence* is required to craft more powerful magic items and comes in five forms: frail, robust, potent, mythic, and deific. These *essences* are required to craft items of uncommon, rare, very rare, legendary, and artifact rarity, respectively. *Essence* can be extracted from all creature types, but the *essence* available depends on the creature’s Challenge Rating (CR). The following harvest table can be appended to all the monster harvest tables.

|Creature CR|Component DC|Components|Item Rarity|
|---|---|---|---|
|3-6|25|Frail essence|Uncommon|
|7-11|30|Robust essence|Rare|
|12-17|35|Potent essence|Very rare|
|18-24|40|Mythic essence|Legendary|
|25+|50|Deific essence|Artifact|

You can’t harvest a lower-level *essence* from a higher CR creature—they have only one *essence*, the one dictated by its CR!

**Appearance:** *Essence* can look like whatever you want it to: a nebulous ball of energy, a random creature component, or something you extract into a crystal to make it glow. This is intentionally undefined to let you build your own world!


## Foraging for Ingredients Rule Set

Characters can forage for ingredients in the wild using skill checks. This rule set provides guidelines on how to determine the success of foraging attempts, the quantity of ingredients found, and the environmental factors that influence foraging difficulty.

#### Skill Checks

Characters can make skill checks to forage for ingredients. The appropriate skills include:

- **Wisdom (Survival):** General foraging.
- **Intelligence (Nature):** Identifying edible plants.
- **Wisdom (Perception):** Spotting ingredients.

**Set DCs:** Based on the abundance and difficulty of finding ingredients in the environment. Adjust the DCs for different environments as follows:

#### Environment-Based DC Adjustments


| Environment | DC    |
| ----------- | ----- |
| Forest      | - 1   |
| Desert      | +5    |
| Dungeon     | +3    |
| Underdark   | +2    |
| Arctic      | +4    |
| Coastal     | +1    |
| Grassland   | +/- 0 |
| Mountain    | +2    |
| Swamp       | +1    |
| Urban       | +2    |


#### Foraging Time

Foraging takes time. A typical foraging attempt might take 1-2 hours. The DM decides how much time passes and what encounters might occur during this period.

#### Gathering Results

Based on the skill check result, determine the quantity and quality of ingredients found. Use the table below to determine results:

|**Skill Check Result**|**Ingredients Found**|
|---|---|
|DC 1-5|-|
|DC 6-9|Enough for 1 meal|
|DC 10-12|Enough for 2 meals|
|DC 13-14|Enough for 3 meals|
|DC 15-19|Enough for 4 meals|
|DC 20+|Enough for 6 meals|

### Example Foraging Process

**1. Identify the Environment:**

- The characters are in a forest, so the DC is set to normal (e.g., DC 10 for a lush forest).

**2. Skill Check:**

- Each character makes a skill check using either Wisdom (Survival), Intelligence (Nature), or Wisdom (Perception).
