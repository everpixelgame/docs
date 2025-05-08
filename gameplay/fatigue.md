# Fatigue System

![Fatigue Meter](https://placeholder.com/wp-content/uploads/2018/10/placeholder.png)

## What is Fatigue?

Fatigue represents your Hero's energy and stamina. Each time a Hero enters a dungeon, they use energy and become more fatigued. Heroes with too much fatigue can't enter dungeons until they recover.

## Fatigue Cooldown

All Heroes start with the same base cooldown of 6 hours at Level 1, which decreases as your Hero levels up. Higher rarity Heroes receive greater cooldown reductions per level.

### Cooldown Reduction Per Level by Rarity

| Rarity | Cooldown Reduction per Level |
|--------|----------------------------|
| Common | 2% per level |
| Rare | 3% per level |
| Epic | 4% per level |
| Legendary | 5% per level |

### Cooldown Duration Table

| Level | Common | Rare | Epic | Legendary |
|-------|--------|------|------|-----------|
| 1 | 6 hours | 6 hours | 6 hours | 6 hours |
| 2 | 5.88 hours | 5.82 hours | 5.76 hours | 5.7 hours |
| 3 | 5.76 hours | 5.64 hours | 5.52 hours | 5.4 hours |
| 4 | 5.64 hours | 5.46 hours | 5.28 hours | 5.1 hours |
| 5 | 5.52 hours | 5.28 hours | 5.04 hours | 4.8 hours |
| 6 | 5.40 hours | 5.10 hours | 4.8 hours | 4.5 hours |
| 7 | 5.28 hours | 4.92 hours | 4.56 hours | 4.2 hours |
| 8 | 5.16 hours | 4.74 hours | 4.32 hours | 3.9 hours |
| 9 | 5.04 hours | 4.56 hours | 4.08 hours | 3.6 hours |
| 10 | 4.92 hours | 4.38 hours | 3.84 hours | 3.3 hours |

Once a Hero reaches their fatigue limit, they can't enter dungeons until the cooldown period passes naturally. Heroes must rest for their full cooldown duration before they can enter dungeons again.

### Cooldown Calculation Examples

**Example 1:** Level 5 Common Hero
- Base Cooldown: 6 hours
- Cooldown Reduction: 2% × 4 = 8% reduction
- Final Cooldown: 6 hours × (1 - 0.08) = 5.52 hours (5 hours and 31 minutes)

**Example 2:** Level 7 Rare Hero
- Base Cooldown: 6 hours
- Cooldown Reduction: 3% × 6 = 18% reduction
- Final Cooldown: 6 hours × (1 - 0.18) = 4.92 hours (4 hours and 55 minutes)

**Example 3:** Level 10 Epic Hero
- Base Cooldown: 6 hours
- Cooldown Reduction: 4% × 9 = 36% reduction
- Final Cooldown: 6 hours × (1 - 0.36) = 3.84 hours (3 hours and 50 minutes)

**Example 4:** Level 10 Legendary Hero
- Base Cooldown: 6 hours
- Cooldown Reduction: 5% × 9 = 45% reduction
- Final Cooldown: 6 hours × (1 - 0.45) = 3.3 hours (3 hours and 18 minutes)

## Daily Dungeon Runs

The number of dungeon runs a Hero can make in 24 hours varies by level and rarity:

| Level | Common | Rare | Epic | Legendary |
|-------|--------|------|------|-----------|
| 1 | 4 runs | 4 runs | 4 runs | 4 runs |
| 5 | 4.35 runs | 4.55 runs | 4.76 runs | 5 runs |
| 10 | 4.88 runs | 5.48 runs | 6.25 runs | 7.27 runs |

### Daily Runs Calculation Examples

**Example 1:** Level 10 Common Hero
- Cooldown Time: 4.92 hours
- Potential Runs in 24 hours: 24 ÷ 4.92 = 4.88 runs

**Example 2:** Level 10 Legendary Hero
- Cooldown Time: 3.3 hours
- Potential Runs in 24 hours: 24 ÷ 3.3 = 7.27 runs

## Fatigue Recovery Bonuses

Heroes with higher levels recover fatigue faster:

- **Level Bonus**: +2% recovery rate per level

For example, a Level 5 Hero would have:
- Level bonus: +10% (Level 5 × 2%)
- Total: +10% faster recovery

### Recovery Rate Calculation Examples

**Example 1:** Level 7 Hero
- Base Recovery Time: Let's say 6 hours
- Level Bonus: 2% × 7 levels = 14% faster recovery
- Actual Recovery Time: 6 hours ÷ 1.14 = 5.26 hours

**Example 2:** Level 10 Hero
- Base Recovery Time: 6 hours
- Level Bonus: 2% × 10 levels = 20% faster recovery
- Actual Recovery Time: 6 hours ÷ 1.2 = 5 hours

## Risk-Reward Balance

To maintain game economy balance, additional mechanics are in place:

1. **Progressive Risk**: As you use the same Hero multiple times in a single day, the death risk increases slightly:
- Runs 1-3: Normal death chance
- Runs 4-6: +1% death chance
- Runs 7+: +2% death chance

2. **Progressive Reward Lock**: Rewards from multiple runs in a day are locked for longer periods:
- Runs 1-3: Standard unlock period (24 hours)
- Runs 4-6: Extended unlock period (48 hours)
- Runs 7+: Long unlock period (72 hours)

### Progressive Risk Examples

**Example 1:** Level 8 Rare Hero in Normal Dungeon
- Base Death Chance: 3% × 1.5 = 4.5%
- First 3 runs: 4.5% death chance each
- Runs 4-6: 4.5% + 1% = 5.5% death chance each
- Runs 7+: 4.5% + 2% = 6.5% death chance each

**Example 2:** Level 10 Legendary Hero in Hard Dungeon
- Base Death Chance: 1% × 2 = 2%
- First 3 runs: 2% death chance each
- Runs 4-6: 2% + 1% = 3% death chance each
- Runs 7+: 2% + 2% = 4% death chance each

## Strategic Fatigue Management

- **Plan your dungeon runs** around the cooldown period
- **Balance risk and reward** with multiple daily runs
- **Level up your Heroes** to improve recovery rates
- **Create a diverse roster** with Heroes of different rarities for optimal play
- **Stagger your runs** to always have some Heroes available to play