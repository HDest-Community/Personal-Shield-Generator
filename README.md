### Important
- This mod requires [AceCoreLib](https://gitlab.com/accensi/hd-addons/acecorelib).

### Notes
---
- The Personal Shield Generator can be found both in the wild and in backpacks.
- Loadout code is `psg`.
- Configuration codes are:
	- `points`: Start with this many upgrade points.
	- `elem`: Shield will help extinguish fire.
	- `medical`: Shield will help close wounds, regenerate health, and heal burns.
	- `shock`: Shield will damage latched babuins and eventually kill them.

### Mechanics
---
- The generator needs three batteries to function. Any fewer and the shield will not regenerate.
- If the shield disappears, be it due to batteries depleting or dropping the generator or switching between modes, the excess shields will crush you and you will take damage depending on the amount of shield.
- Thickness is how good the shield is at stopping bullets. Thicker shields absorb projectile energy better. Only really affects bullets.
- Efficiency is how many units of shield need to be recharged for all batteries to lose 1 charge. Each cycle reduces efficiency.
- Recharge rate varies depending on shield amount and mode. It peaks at half capacity and goes down as shield depletes or regenerates.
- Multiple shield generators do not stack due to interference.
- Hold Firemode with your PSG selected when picking up another generator to consume the item and gain upgrade points. This is a passive bonus.