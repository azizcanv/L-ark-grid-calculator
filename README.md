# Ark Grid Calculator

A lightweight web tool to optimize **Ark Passive Core** gem layouts using your inventory.

---

## How It Works

The calculator simulates all valid gem combinations for **3 cores**, based on:

- Your available gems (Class / General astrogem inventory)
- Core rarity (Legendary / Relic / Ancient)
- Willpower limits per core
- Target point goals (Auto or Manual)

It then selects the **best possible combination** by:
1. Prioritizing reaching target points
2. Minimizing wasted points (over-target)
3. Maximizing total points
4. Using the least willpower when ties occur

---

## How to Use

### 1. Enter Your Ark Grid Page
- Fill in the quantity of each gem you own.
- Class and General astrogems are calculated separately.

### 2. Configure Cores
- Choose **Legendary / Relic / Ancient** for each core.
- **Auto Target (recommended)**:
  - Legendary → 14 pts  
  - Relic / Ancient → 17 pts
- Or disable Auto and set targets manually.

### 3. Calculate
- Click **Calculate** for one side
- Or **Calculate Both** to optimize Class and General at once.

### 4. Read Results
For each core you will see:
- Used astrogems
- Willpower used
- Points vs target
- Progress bar
- Remaining unused astrogems

---

## Notes

- Results always respect your inventory limits.
- If inventory is insufficient, the calculator shows the **best achievable result** below the target.
- Manual targets affect priority order between cores.
- The site may continue to receive updates and improvements over time.

---

## Credits

Original template and inspiration by **u/skyhawkx3** (Reddit).
