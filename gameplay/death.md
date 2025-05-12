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

## The Graveyard System - Direct Pool Distribution

When Heroes die, they're not completely useless! They enter the Graveyard and become "Stakers."

### How Graveyard Staking Works

When Heroes die and enter the Graveyard:
- 20% of all dungeon entry fees go directly to the Graveyard staking pool
- Dead Heroes earn rewards from this pool based on their staking power relative to all other Graveyard Heroes
- The distribution is weighted based on:
  - **Hero Rarity**: Higher rarity = greater staking power
  - **Dungeon Difficulty**: Heroes that died in harder dungeons earn more

### Graveyard Staking Power Formula

Staking power formula: `Rarity Multiplier × Difficulty Multiplier`

| Factor | Multiplier |
|--------|------------|
| **Rarity** |  |
| Common | 1× |
| Rare | 1.5× |
| Epic | 2× |
| Legendary | 3× |
| **Difficulty** |  |
| Easy | 1× |
| Normal | 1.5× |
| Hard | 2× |

### Reward Distribution Formula

Each Hero's reward = `(Hero's Staking Power ÷ Total Staking Power of All Heroes) × Available Pool`

### Staking Power Calculation Examples

**Example 1:** Common Hero that died in Easy Dungeon
- Rarity Multiplier: 1× (Common)
- Difficulty Multiplier: 1× (Easy)
- Staking Power: 1 × 1 = 1 unit

**Example 2:** Rare Hero that died in Normal Dungeon
- Rarity Multiplier: 1.5× (Rare)
- Difficulty Multiplier: 1.5× (Normal)
- Staking Power: 1.5 × 1.5 = 2.25 units

**Example 3:** Epic Hero that died in Hard Dungeon
- Rarity Multiplier: 2× (Epic)
- Difficulty Multiplier: 2× (Hard)
- Staking Power: 2 × 2 = 4 units

**Example 4:** Legendary Hero that died in Hard Dungeon
- Rarity Multiplier: 3× (Legendary)
- Difficulty Multiplier: 2× (Hard)
- Staking Power: 3 × 2 = 6 units

### Graveyard Distribution Example

Assuming:
- Total Graveyard Pool: 1,000 $EVER
- Total combined staking power of all Heroes: 100 units
- Your Heroes' combined staking power: 10 units

Your Graveyard earnings would be:
- (10 ÷ 100) × 1,000 = 100 $EVER

## Strategic Considerations

- **Risk Assessment**: Balance reward potential against death risk
- **Hero Value**: Consider if a Hero is worth risking in a harder dungeon
- **Graveyard Value**: Sometimes it's strategic to send Heroes to the Graveyard for long-term staking
- **Portfolio Balance**: Maintain a mix of living Heroes and Graveyard stakers

### Strategic Decision Examples

**Example 1:** Is it worth sending a Common Hero to a Hard Dungeon?
- Death Risk: 10% (high)
- Living Value: Low rewards and slow cooldown
- Graveyard Value: 1 × 2 = 2 staking power units
- Strategic Decision: Might be worth the risk for Common Heroes, especially at lower levels

**Example 2:** Is it worth sending a Legendary Hero to a Hard Dungeon?
- Death Risk: 2% (still significant)
- Living Value: Highest rewards and fastest cooldown
- Graveyard Value: 3 × 2 = 6 staking power units (highest possible)
- Strategic Decision: Generally not worth the risk unless you have multiple Legendary Heroes

## Graveyard Dashboard

You can monitor your Graveyard Heroes through the Graveyard Dashboard, which shows:
- All your staked dead Heroes
- Individual and total staking power
- Current share of the Graveyard pool
- Historical earnings
- Graveyard pool size and growth metrics