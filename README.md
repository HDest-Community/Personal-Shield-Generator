### Notes
---
- The Personal Shield Generator can be found both in the wild and in backpacks.
- Loadout code is `psg`.
- Configuration codes are:
	- `energy [1-6]`: Start with this much unallocated energy.
	- `noenergy`: Start with no unallocated energy.
- CVars are:
	- `psg_invert [true/false]`: Inverts the "menu" selection. Client-side CVar.

### Mechanics
---
- The generator needs three batteries to function. If all batteries are missing or empty, the shield will disappear. With 1 and 2 batteries, the shield will not regenerate.
- Efficiency is how many units of shield need to be recharged for all batteries to lose 1 charge. Each cycle reduces efficiency.
- You only have a limited number of "points" you can distribute between CAP, EFF, and RCH, so choose wisely.
- Recharge rate varies depending on shield amount. It peaks at half capacity and goes down as shield depletes or regenerates.
- Multiple shield generators do not stack due to interference.
