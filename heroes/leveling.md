# Hero Leveling

![Hero Leveling](https://placeholder.com/wp-content/uploads/2018/10/placeholder.png)

## Experience and Levels

In Everpixel, Heroes gain experience (EXP) from dungeon runs and level up over time, becoming more powerful and profitable.

### Level System Basics

- Heroes start at **Level 1**
- Maximum level in MVP is **Level 10**
- Each level provides permanent stat improvements
- Leveling is independent of class but affected by rarity

## Experience Gains

Heroes earn EXP from completing dungeons:

| Dungeon | Base EXP |
|---------|----------|
| Easy | 10 EXP |
| Normal | 25 EXP |
| Hard | 50 EXP |

Rarity affects EXP gain:
- Legendary: +15% EXP
- Epic: +10% EXP
- Rare: +5% EXP
- Common: Standard EXP (no bonus)

### EXP Gain Calculation Examples

**Example 1:** Common Hero in Easy Dungeon
- Base EXP: 10 EXP
- Rarity Bonus: 0% (Common)
- Total EXP: 10 EXP

**Example 2:** Rare Hero in Normal Dungeon
- Base EXP: 25 EXP
- Rarity Bonus: +5% (Rare)
- Total EXP: 25 × 1.05 = 26.25 EXP

**Example 3:** Epic Hero in Hard Dungeon
- Base EXP: 50 EXP
- Rarity Bonus: +10% (Epic)
- Total EXP: 50 × 1.1 = 55 EXP

**Example 4:** Legendary Hero in Hard Dungeon
- Base EXP: 50 EXP
- Rarity Bonus: +15% (Legendary)
- Total EXP: 50 × 1.15 = 57.5 EXP

## Experience Required Per Level

The following table shows the EXP required to reach each level:

| Level | Total EXP Required | EXP from Previous Level |
|-------|-------------------|-------------------------|
| 1 | 0 | Starting Level |
| 2 | 100 | 100 |
| 3 | 250 | 150 |
| 4 | 450 | 200 |
| 5 | 700 | 250 |
| 6 | 1,000 | 300 |
| 7 | 1,350 | 350 |
| 8 | 1,750 | 400 |
| 9 | 2,200 | 450 |
| 10 | 2,700 | 500 |

### Leveling Time Examples

**Example 1:** Common Hero running Easy Dungeons
- EXP per run: 10 EXP
- EXP needed for Level 10: 2,700 EXP
- Dungeon runs needed: 2,700 ÷ 10 = 270 runs

**Example 2:** Legendary Hero running Hard Dungeons
- EXP per run: 50 × 1.15 = 57.5 EXP
- EXP needed for Level 10: 2,700 EXP
- Dungeon runs needed: 2,700 ÷ 57.5 ≈ 47 runs

## Level Benefits

Each level provides multiple benefits:

1. **+2% Coin Drop Rate per Level**
    - Increases $EVER rewards from dungeons
    - Stacks with rarity bonuses

2. **+2% Recovery Rate per Level**
    - Improves fatigue recovery speed

3. **Cooldown Reduction per Level**
    - Decreases the cooldown time between dungeon runs
    - Reduction percentage varies by rarity:
        - Common: 2% per level
        - Rare: 3% per level
        - Epic: 4% per level
        - Legendary: 5% per level

### Cooldown Duration By Level

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

### Cooldown Reduction Calculation Examples

**Example 1:** Level 5 Common Hero
- Base Cooldown: 6 hours
- Reduction per Level: 2%
- Total Reduction: 2% × 4 = 8%
- Final Cooldown: 6 × (1 - 0.08) = 5.52 hours

**Example 2:** Level 10 Legendary Hero
- Base Cooldown: 6 hours
- Reduction per Level: 5%
- Total Reduction: 5% × 9 = 45%
- Final Cooldown: 6 × (1 - 0.45) = 3.3 hours

### Example Bonuses By Level

| Level | Coin Drop Bonus | Recovery Bonus | Cooldown Reduction (Legendary) |
|-------|-----------------|----------------|-------------------------------|
| 1 | +0% | +0% | 0% |
| 3 | +4% | +4% | 10% |
| 5 | +8% | +8% | 20% |
| 7 | +12% | +12% | 30% |
| 10 | +18% | +18% | 45% |

## Combined Rarity and Level Bonuses

Rarity base bonuses stack with level bonuses for powerful combinations:

| Hero Type | Base + Level 10 | Total Drop Rate |
|-----------|----------------|-----------------|
| Common L10 | 0% + 18% | +18% |
| Rare L10 | 10% + 18% | +28% |
| Epic L10 | 20% + 18% | +38% |
| Legendary L10 | 30% + 18% | +48% |

### Reward Calculation Examples

Assuming base dungeon rewards: Easy = 10 $EVER, Normal = 25 $EVER, Hard = 50 $EVER

**Example 1:** Level 8 Common Hero in Normal Dungeon
- Base Reward: 25 $EVER
- Level Bonus: 2% × 8 = 16%
- Rarity Bonus: 0% (Common)
- Total Bonus: 16%
- Final Reward: 25 × 1.16 = 29 $EVER

**Example 2:** Level 10 Rare Hero in Hard Dungeon
- Base Reward: 50 $EVER
- Level Bonus: 2% × 10 = 20%
- Rarity Bonus: 10% (Rare)
- Total Bonus: 30%
- Final Reward: 50 × 1.3 = 65 $EVER

**Example 3:** Level 10 Legendary Hero in Hard Dungeon
- Base Reward: 50 $EVER
- Level Bonus: 2% × 10 = 20%
- Rarity Bonus: 30% (Legendary)
- Total Bonus: 50%
- Final Reward: 50 × 1.5 = 75 $EVER

## Level-Up Visual Effects

When a Hero levels up:
- Special pixel animation plays
- Hero appearance subtly enhances
- Level number displayed prominently
- Stat increases are shown

## Daily Dungeon Run Potential

The number of dungeon runs a Hero can make in 24 hours varies by level and rarity:

| Level | Common | Rare | Epic | Legendary |
|-------|--------|------|------|-----------|
| 1 | 4 runs | 4 runs | 4 runs | 4 runs |
| 5 | 4.35 runs | 4.55 runs | 4.76 runs | 5 runs |
| 10 | 4.88 runs | 5.48 runs | 6.25 runs | 7.27 runs |

### Daily Runs Calculation Examples

**Example 1:** Level 10 Common Hero
- Cooldown: 4.92 hours
- Daily Runs: 24 ÷ 4.92 = 4.88 runs per day

**Example 2:** Level 10 Legendary Hero
- Cooldown: 3.3 hours
- Daily Runs: 24 ÷ 3.3 = 7.27 runs per day

## Leveling Strategy

### Optimal Leveling Approaches

| Hero Type | Recommended Approach |
|-----------|---------------------|
| Common | Natural leveling through dungeons |
| Rare | Prioritize dungeon runs |
| Epic | Focus on leveling to 8+ |
| Legendary | Prioritize leveling to 10 ASAP |

### ROI Calculation

| Hero | Extra Daily Earnings at L10 | Days to ROI |
|------|----------------------------|-------------|
| Common | +1.8 $EVER/day | 100 days |
| Rare | +2.8 $EVER/day | 64 days |
| Epic | +3.8 $EVER/day | 47 days |
| Legendary | +4.8 $EVER/day | 38 days |

### ROI Calculation Examples

**Example 1:** Level 10 vs Level 1 Common Hero running Easy Dungeons 4 times daily
- Level 1 Earnings: 4 runs × 10 $EVER = 40 $EVER
- Level 10 Earnings: 4.88 runs × (10 × 1.18) = 57.58 $EVER
- Extra Daily Earnings: 57.58 - 40 = 17.58 $EVER
- Assuming leveling cost of ~1,800 $EVER: 1,800 ÷ 17.58 ≈ 102 days to ROI

**Example 2:** Level 10 vs Level 1 Legendary Hero running Hard Dungeons
- Level 1 Earnings: 4 runs × (50 × 1.3) = 260 $EVER
- Level 10 Earnings: 7.27 runs × (50 × 1.48) = 538 $EVER
- Extra Daily Earnings: 538 - 260 = 278 $EVER
- Assuming leveling cost of ~3,500 $EVER: 3,500 ÷ 278 ≈ 13 days to ROI

### Leveling or New Hero?

When deciding whether to focus on leveling existing Heroes or mint new ones:

| Situation | Recommendation |
|-----------|---------------|
| < 3 Heroes | Focus on minting new Heroes |
| 3-5 Heroes | Balance between minting and leveling |
| 5+ Heroes | Focus on leveling your best Heroes |
| Limited time | Level Legendary/Epic Heroes first |

Remember, higher level Heroes earn more, have better fatigue recovery, AND have shorter cooldowns between dungeon runs, creating a compounding benefit that makes leveling increasingly valuable over time.