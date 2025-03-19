# Week-on-Week (WoW) Change Metrics

## Overview
Week-on-Week (WoW) analysis measures percentage changes in key business metrics compared to the previous week. This approach helps track trends and identify areas for improvement.

## Key Metrics
1. **Revenue WoW Change %** - Tracks weekly revenue fluctuations.
2. **Occupancy WoW Change %** - Measures occupancy rate changes.
3. **ADR WoW Change %** - Calculates changes in Average Daily Rate.
4. **RevPAR WoW Change %** - Monitors Revenue Per Available Room shifts.
5. **Realisation WoW Change %** - Tracks changes in realized revenue.
6. **DSRN WoW Change %** - Analyzes Daily Sellable Room Nights variations.

## Example: Revenue WoW Change Calculation

### Formula Breakdown
1. **Variable `selv`**
   - Retrieves the selected or latest week number.

2. **Variable `revcw`**
   - Calculates revenue for the current week.

3. **Variable `revpw`**
   - Computes revenue for the previous week.

4. **WoW Change Calculation**
   ```
   WoW Revenue Change % = (revcw / revpw) - 1
   ```
   - Uses the `DIVIDE` function to prevent division errors.

## Implementation in Power BI
This formula can be used as a calculated column or measure in Power BI to visualize WoW percentage changes.

---

**Note:** This methodology can be applied to other metrics by replacing the revenue measure accordingly.

