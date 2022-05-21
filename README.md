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
	- `cloak`: Bravo six, going dark. Cloaks you if below 25% flux. Side effect is that it hides your sights. Disabling the shield also disables cloaking.
- Use + Use Item can be used to quickly toggle the shield on and off without having to bring up the interface.

### Mechanics
---
- The generator needs three batteries with 1 charge in them to function.
- Taking damage generates soft flux. A fraction of that is hard flux. The latter cannot be vented without disabling the shield. Soft flux cannot go under the hard flux amount.
- Taking *too much* damage will overload the shield, causing the following effects:
	- Battery charge will be partially depleted. This may result in battery loss if the initial charge was low to begin with.
	- Disable the generator and prevent reactivation until all flux is vented.
	- Set you on fire a little.
- The generator has two modes: full-coverage and frontal. The former makes you virtually impervious to attacks, but shields will take 100% damage, meaning faster flux build-up. Frontal shield makes you open to flanking, but damage to shields is greatly reduced.
- The average battery charge for all loaded batteries will increase or reduce flux dissipation rate.
- Shields block all damage completely.
- Multiple shield generators do not stack due to interference.
- Hold Firemode with your PSG selected when picking up another generator to consume the item and gain upgrade points. This is a passive bonus.