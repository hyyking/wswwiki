# Weapons

| Weapon                           | Abbr | Description                                                     |
|----------------------------------|------|-----------------------------------------------------------------|
| <a href="#gunblade">Gunblade</a> | GB   | A melee weapon that can also fire projectiles if it is upgraded |
| <a href="#machinegun">Machinegun</a>       | MG   | A weapon that fires bullets at a regular interval                                                                      |<a href="#riotgun"> Riotgun </a> Riotgun          | RG   | A shotgun that fires a spread of bullets that each deal damage                                                         |
| <a href="#grenade-launcher">Grenade Launcher</a>  | GL   | Launches grenade like projectiles dealing that persist until they hit an enemy or explode after a fixed amount of time |
| <a href="#rocket-launcher">Rocket Launcher</a>   | RL   | Launches rockets in a straight line until they hit a player or terrain                                                 |
| <a href="#plasma-gun">Plasma Gun</a>        | PG   | Launches plasma projectiles at a fixed interval                                                                        |
| <a href="#laser-gun">Laser Gun</a>        | LG   | Emits a fixed distance laser damaging the first encountered enemy                                                      |
| <a href="#electrobolt">Electrobolt</a>      | EB   | Sniper rifle that emits a ray of light damaging the first enemy hit.                                                   |
| <a href="#instabeam">Instabeam</a>        | IB   | Similar to the Electrobolt but it will one hit kill the enemy. This weapon is only available in Instagib gamemode.     |

## Ammo:

In some gamemodes weapons might have two kinds of ammo:

- Weak ammo that you get by picking the weapon item up
- Strong ammo that you get by picking the corresponding ammo box up

##  Gunblade

<div align="center">
<img src="../static/gunblade.jpg" height="480px">
</div>

#### Game variables

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 0                      |
| Projectile/shot      | 1                      | 0                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 600                    | 600                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 5000                   | 64                     |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 35                     | 50                     |
| Self damage ratio    | 1                      | 0                      |
| Knockback            | 90                     | 50                     |
| Stun                 | 0                      | 0                      |
| Splash radius        | 70                     | 0                      |
| Splash min damage    | 8                      | 0                      |
| Splash min knockback | 10                     | 0                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | 3000                   | 0                      |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 0                      | 0                      |
| Pickup amount        | 0                      | 0                      |
| Max amount           | 1                      | 0                      |
| Low threshold        | 0                      | 0                      |


##  Machinegun

<div align="center">
<img src="../static/machinegun.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 100                    | 100                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 6000                   | 6000                   |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 10                     | 10                     |
| Self damage ratio    | 0                      | 0                      |
| Knockback            | 10                     | 10                     |
| Stun                 | 50                     | 50                     |
| Splash radius        | 0                      | 0                      |
| Splash min damage    | 0                      | 0                      |
| Splash min knockback | 0                      | 0                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | INSTANT                | INSTANT                |
| spread               | 10                     | 10                     |
| v_spread             | 10                     | 10                     |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 50                     | 0                      |
| Pickup amount        | 50                     | 0                      |
| Max amount           | 100                    | 0                      |
| Low threshold        | 20                     | 0                      |



##  Riotgun


<div align="center">
<img src="../static/riotgun.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 20                     | 25                     |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 900                    | 900                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 8192                   | 8192                   |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 5                      | 4                      |
| Self damage ratio    | 0                      | 0                      |
| Knockback            | 7                      | 7                      |
| Stun                 | 85                     | 85                     |
| Splash radius        | 0                      | 0                      |
| Splash min damage    | 0                      | 0                      |
| Splash min knockback | 0                      | 0                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | INSTANT                | INSTANT                |
| spread               | 160                    | 160                    |
| v_spread             | 90                     | 90                     |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 10                     | 0                      |
| Pickup amount        | 10                     | 0                      |
| Max amount           | 20                     | 0                      |
| Low threshold        | 3                      | 0                      |


##  Grenade Launcher


<div align="center">
<img src="../static/grenade_launcher.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 800                    | 800                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 1250                   | 1250                   |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 80                     | 80                     |
| Self damage ratio    | 1                      | 1                      |
| Knockback            | 100                    | 100                    |
| Stun                 | 1250                   | 1250                   |
| Splash radius        | 125                    | 135                    |
| Splash min damage    | 15                     | 15                     |
| Splash min knockback | 35                     | 35                     |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | 1000                   | 1000                   |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 10                     | 0                      |
| Pickup amount        | 10                     | 0                      |
| Max amount           | 20                     | 0                      |
| Low threshold        | 3                      | 0                      |

##  Rocket Launcher


<div align="center">
<img src="../static/rocket_launcher.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 950                    | 950                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 10000                  | 10000                  |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 80                     | 80                     |
| Self damage ratio    | 1                      | 1                      |
| Knockback            | 100                    | 100                    |
| Stun                 | 1250                   | 1250                   |
| Splash radius        | 125                    | 135                    |
| Splash min damage    | 15                     | 15                     |
| Splash min knockback | 35                     | 35                     |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | 1150                   | 1150                   |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 5                      | 0                      |
| Pickup amount        | 10                     | 0                      |
| Max amount           | 20                     | 0                      |
| Low threshold        | 3                      | 0                      |

##  Plasma Gun


<div align="center">
<img src="../static/plasma_gun.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 100                    | 100                    |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 5000                   | 5000                   |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 15                     | 15                     |
| Self damage ratio    | 0.5                    | 0.5                    |
| Knockback            | 20                     | 20                     |
| Stun                 | 200                    | 200                    |
| Splash radius        | 45                     | 45                     |
| Splash min damage    | 5                      | 5                      |
| Splash min knockback | 1                      | 1                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | 2500                   | 2500                   |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 50                     | 0                      |
| Pickup amount        | 100                    | 0                      |
| Max amount           | 150                    | 0                      |
| Low threshold        | 20                     | 0                      |

##  Laser Gun


<div align="center">
<img src="../static/laser_gun.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 50                     | 50                     |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 850                    | 850                    |
| Smooth Refire        | true                   | true                   |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 7                      | 7                      |
| Self damage ratio    | 0                      | 0                      |
| Knockback            | 14                     | 14                     |
| Stun                 | 300                    | 300                    |
| Splash radius        | 0                      | 0                      |
| Splash min damage    | 0                      | 0                      |
| Splash min knockback | 0                      | 0                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | INSTANT                | INSTANT                |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 50                     | 0                      |
| Pickup amount        | 100                    | 0                      |
| Max amount           | 150                    | 0                      |
| Low threshold        | 20                     | 0                      |

##  Electrobolt


<div align="center">
<img src="../static/electrobolt.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 1250                   | 1250                   |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 900                    | 900                    |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 75                     | 75                     |
| Self damage ratio    | 0                      | 0                      |
| Knockback            | 80                     | 40                     |
| Stun                 | 1000                   | 1000                   |
| Splash radius        | 0                      | 0                      |
| Splash min damage    | 75                     | 75                     |
| Splash min knockback | 35                     | 35                     |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | INSTANT                | INSTANT                |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 5                      | 0                      |
| Pickup amount        | 10                     | 0                      |
| Max amount           | 10                     | 0                      |
| Low threshold        | 3                      | 0                      |

##  Instabeam

<div align="center">
<img src="../static/instabeam.jpg" height="480px">
</div>

| Description          | Strong Amount          | Weak Amount            |
|----------------------|------------------------|------------------------|
| Ammo/shot            | 1                      | 1                      |
| Projectile/shot      | 1                      | 1                      |
| <b>Timing (ms)</b>   | ---------------------- | ---------------------- |
| Weapon Up            | WEAPONUP_FRAMETIME     | WEAPONUP_FRAMETIME     |
| Weapon Down          | WEAPONDOWN_FRAMETIME   | WEAPONDOWN_FRAMETIME   |
| Reload               | 1300                   | 1300                   |
| Cooldown             | 0                      | 0                      |
| Projectile Timeout   | 8024                   | 8024                   |
| Smooth Refire        | false                  | false                  |
| <b>Damages</b>       | ---------------------- | ---------------------- |
| Damage               | 200                    | 200                    |
| Self damage ratio    | 0.1                    | 0.1                    |
| Knockback            | 95                     | 95                     |
| Stun                 | 1000                   | 1000                   |
| Splash radius        | 80                     | 80                     |
| Splash min damage    | 0                      | 0                      |
| Splash min knockback | 0                      | 0                      |
| <b>Projectile</b>    | ---------------------- | ---------------------- |
| speed                | INSTANT                | INSTANT                |
| spread               | 0                      | 0                      |
| v_spread             | 0                      | 0                      |
| <b>Ammo</b>          | ---------------------- | ---------------------- |
| Weapon pickup amount | 5                      | 0                      |
| Pickup amount        | 5                      | 0                      |
| Max amount           | 5                      | 0                      |
| Low threshold        | 0                      | 0                      |