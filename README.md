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
	- `cloak`: Bravo six, going dark. Cloaks you if above 75% shield. Side effect is that it hides your sights. Disabling the shield also disables cloaking.

### Mechanics
---
- The generator needs three batteries to function. Any fewer and the shield will not regenerate.
- If the maximum shield amount is suddenly lowered to be under the current shield amount, the excess shields will be discharged with great force and deal damage to anything near you. Range and damage grow with difference.
- Thickness is how good the shield is at stopping bullets. Thicker shields absorb projectile energy better. Only really affects bullets.
- Efficiency is how many units of shield need to be recharged for all batteries to lose 1 charge. Each cycle reduces efficiency.
- Recharge rate varies depending on shield amount and mode. It peaks at half capacity and goes down as shield depletes or regenerates.
- Multiple shield generators do not stack due to interference.
- Hold Firemode with your PSG selected when picking up another generator to consume the item and gain upgrade points. This is a passive bonus.