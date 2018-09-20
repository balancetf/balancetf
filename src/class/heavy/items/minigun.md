# Minigun

| Misc               |         |
|--------------------|--------:|
| Hitscan/Projectile | Hitscan |
| Ranged/Melee       |  Ranged |
| Ammo Reserve       |     200 |
| Windup move speed  |     47% |

| Damage                  |                |
|-------------------------|---------------:|
| Type                    |         Bullet |
| Max rampup (150%)       |  13.5 / bullet |
| Base damage (100%)      |     9 / bullet |
| Max falloff (50%)       |   4.5 / bullet |
| Crit                    |    27 / bullet |
| Mini-crit               | 12-18 / bullet |

| Function Times          |                |
|-------------------------|---------------:|
| Attack interval         |    0.1 seconds |
| Windup time             |   0.87 seconds |

*Source: [TF Wiki](https://wiki.teamfortress.com/wiki/Minigun)*

## Approved Change
...

## Disputed Change #1

### Changes from Stock
Completely replace the minigun with a Burstgun:

* **This weapon fires in bursts.**

| Misc               |         |
|--------------------|--------:|
| Hitscan/Projectile | Hitscan |
| Ranged/Melee       |  Ranged |
| Ammo per burst     |       1 |
| Bullets per burst  |       4 |
| Clip size          |       6 |
| Ammo reserve       |      36 |

| Damage                  |                |
|-------------------------|---------------:|
| Type                    |         Bullet |
| Max rampup (150%)       |  17.5 / bullet |
| Base damage (100%)      |    11 / bullet |
| Max falloff (50%)       |   5.5 / bullet |
| Crit                    |    33 / bullet |

| Function Times          |                |
|-------------------------|---------------:|
| Attack interval         |    0.3 seconds |
| Burst time              |   0.45 seconds |
| Reload (first)          |   0.75 seconds |
| Reload (consecutive)    |   0.55 seconds |

Notes:
Burst time is the amount of time that it takes for all bullets in a burst to be fired consecutively. Meaning that each bullet has an intermediate interval of `x ÷ n` where x is Burst time and n is the number of bullets fired.

### Current Problems
A lot of the skill involved in TF2 involves the complex and dynamic relationship between movement and aim. The Heavy is the only class that directly segregates these two features with the Windup mechanic on the Heavy's Minigun - from the time when windup starts to when the minigun is unwound, the player's movement speed is significantly slowed. The Minigun is also designed around random spread in order to reduce the effective range of the weapon, instead of relying on damage fall off and the player's ability to track when aiming.

Overall it seems that the the Heavy is a complete contradiction to the design of the rest of the classes, as it pertains to movement.

### Explanation of Changes
Removing the decoupling between movement and fighting, by removing the wind up mechanic, should introduce a healthier relationship between movement and fighting for this class. The overall damage output of the class has been reduced significantly, but the opportunities where the class can output damage have been increased significantly. The weapon still shoots a stream of bullets, but only for a short period of time, and with a delay between each burst of bullets. This inherently rewards players who have good aim and can reliably track their targets.

### Additional Comments
Originally, when designing this weapon, there was an additional mechanic called "Vulnerability" which would replace the ramp-up/fall-off of the Burstgun. Instead, all players had "Vulnerability" stat which starts at 0.5 by default. Damage caused by the Burstgun would increase the player's vulnerability by a proportional amount, capping off at 1.5. Vulnerability decreases back down to 0.5 over time. The damage done to players by the Burstgun would be multiplied by the effected players Vulnerability before being applied to the player.

I decided to scrap this mechanic. It was originally intended to further promote players who could track and aim effectively; but, in the end, I think it was too complicated and that a simpler solution was in order - which is what these changes are a conclusion to.

*Contributors: tristenmilk*
