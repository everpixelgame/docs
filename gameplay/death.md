# Death & Graveyard System

![Graveyard](https://placeholder.com/wp-content/uploads/2018/10/placeholder.png)

## Permanent Death

In Everpixel, death is permanent. When a Hero dies, they cannot be revived and will be moved to the Graveyard. This creates meaningful risk/reward decisions in how you use your Heroes.

## Death Chance

Each Hero has a base death chance determined by their rarity:

| Rarity | Base Death Chance |
|--------|-------------------|
| Common | 5% |
| Rare | 3% |
| Epic | 2% |
| Legendary | 1% |

This chance is modified by dungeon difficulty:
- **Easy Dungeon**: Base chance
- **Normal Dungeon**: Base chance × 1.5
- **Hard Dungeon**: Base chance × 2

### Death Chance Calculation Examples

**Example 1:** Common Hero in Easy Dungeon
- Base Death Chance: 5%
- Dungeon Modifier: 1× (Easy)
- Final Death Chance: 5% × 1 = 5%

**Example 2:** Rare Hero in Normal Dungeon
- Base Death Chance: 3%
- Dungeon Modifier: 1.5× (Normal)
- Final Death Chance: 3% × 1.5 = 4.5%

**Example 3:** Epic Hero in Hard Dungeon
- Base Death Chance: 2%
- Dungeon Modifier: 2× (Hard)
- Final Death Chance: 2% × 2 = 4%

**Example 4:** Legendary Hero in Hard Dungeon
- Base Death Chance: 1%
- Dungeon Modifier: 2× (Hard)
- Final Death Chance: 1% × 2 = 2%

## The Graveyard System

When Heroes die, they're not completely useless! They enter the Graveyard and become "Stakers."

### How Graveyard Staking Works

When Heroes die and enter the Graveyard:
- 20% of all $EPXL spent in the game goes to the Graveyard staking pool
- Dead Heroes earn rewards from this pool based on their proportion of the total staking power
- Rewards are based on:
   - **Hero Rarity**: Higher rarity = better rewards
   - **Dungeon Difficulty**: Heroes that died in harder dungeons earn more

### Graveyard Rewards Formula

Basic reward formula: `Base Rate × Rarity Multiplier × Difficulty Multiplier`

| Factor | Multiplier |
|--------|------------|
| **Rarity** |  |
| Common | 1x |
| Rare | 1.5x |
| Epic | 2x |
| Legendary | 3x |
| **Difficulty** |  |
| Easy | 1x |
| Normal | 1.5x |
| Hard | 2x |

### Graveyard Rewards Calculation Examples

Assuming a base rate of 10 $EPXL per day for staking calculation:

**Example 1:** Common Hero that died in Easy Dungeon
- Base Rate: 10 $EPXL
- Rarity Multiplier: 1× (Common)
- Difficulty Multiplier: 1× (Easy)
- Daily Rewards: 10 × 1 × 1 = 10 $EPXL per day

**Example 2:** Rare Hero that died in Normal Dungeon
- Base Rate: 10 $EPXL
- Rarity Multiplier: 1.5× (Rare)
- Difficulty Multiplier: 1.5× (Normal)
- Daily Rewards: 10 × 1.5 × 1.5 = 22.5 $EPXL per day

**Example 3:** Epic Hero that died in Hard Dungeon
- Base Rate: 10 $EPXL
- Rarity Multiplier: 2× (Epic)
- Difficulty Multiplier: 2× (Hard)
- Daily Rewards: 10 × 2 × 2 = 40 $EPXL per day

**Example 4:** Legendary Hero that died in Hard Dungeon
- Base Rate: 10 $EPXL
- Rarity Multiplier: 3× (Legendary)
- Difficulty Multiplier: 2× (Hard)
- Daily Rewards: 10 × 3 × 2 = 60 $EPXL per day

## Strategic Considerations

- **Risk Assessment**: Balance reward potential against death risk
- **Hero Value**: Consider if a Hero is worth risking in a harder dungeon
- **Graveyard Value**: Sometimes it's strategic to send Heroes to the Graveyard for long-term staking
- **Portfolio Balance**: Maintain a mix of living Heroes and Graveyard stakers

### Strategic Decision Examples

**Example 1:** Is it worth sending a Common Hero to a Hard Dungeon?
- Death Risk: 10% (high)
- Living Value: Low rewards and slow cooldown
- Graveyard Value: 10 × 1 × 2 = 20 $EPXL per day
- Strategic Decision: Might be worth the risk for Common Heroes, especially at lower levels

**Example 2:** Is it worth sending a Legendary Hero to a Hard Dungeon?
- Death Risk: 2% (still significant)
- Living Value: Highest rewards and fastest cooldown
- Graveyard Value: 10 × 3 × 2 = 60 $EPXL per day
- Strategic Decision: Generally not worth the risk unless you have multiple Legendary Heroes

## Graveyard Dashboard

You can monitor your Graveyard Heroes through the Graveyard Dashboard, which shows:
- All your staked dead Heroes
- Individual and total earning rates
- Historical earnings