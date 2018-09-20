# Global Changes

## Removal of Random Spread
Every weapon that has any amount of random spread has it removed. This refers specifically to non-shotgun type weapons, as shotgun spread can already be disabled with the `tf_use_fixed_weaponspreads` cvar.

Random spread creates 3 possible outcomes:
1. A player should hit a shot, but random spread causes them to miss.
2. A player should miss a shot, but random spread causes them to hit.
3. The same result as if random spread didn't exist at all.

Since the only results of random spread are either rewarding players for missing or punishing players for aiming well, let's just do away with it. However, this makes certain weapons become too powerful (e.g. the pistol). To counteract this, random spread will be replaced by harsher falloff, lower minimum damage values, or both.

The following weapons would be affected by this change:
* [Pistol](class/multiclass/items/pistol.md)
* [Winger](class/scout/items/winger.md)
* [Pretty Boy's Pocket Pistol](class/scout/items/pretty-boys-pocket-pistol.md)
* [Huntsman](class/sniper/items/huntsman.md)
* [SMGs](class/sniper/sniper.md#smgs)
* [Grenade Launchers](class/demoman/demoman.md#grenade-launchers)
* [Stickybomb Launchers](class/demoman/demoman.md#stickybomb-launchers)
* [Revolvers](class/spy/spy.md#revolvers)
* [Beggar's Bazooka](class/soldier/items/beggars-bazooka.md)
* [Miniguns](class/heavy/heavy.md#miniguns)

There are potentially more items to be added to this list. See [Contributing](contributing.md).
