<style>
    :root {
        --content-max-width: 75%;
    }
    .weapons {
        margin:0 auto;
        max-width: 800px;
    }
    img {
        width: auto;
        max-height: 480px;
    }
</style>

# Weapons

| Weapon                                | Abbr | Description                                                                                                            |
|---------------------------------------|------|------------------------------------------------------------------------------------------------------------------------|
| [Gunblade](#gunblade)                 | GB   | A melee weapon that can also fire projectiles if it is upgraded                                                        |
| [Machinegun](#machinegun)             | MG   | A weapon that fires bullets at a regular interval                                                                      |
| [Riotgun](#riotgun)                   | RG   | A shotgun that fires a spread of bullets that each deal damage                                                         |
| [Grenade Launcher](#grenade-launcher) | GL   | Launches grenade like projectiles dealing that persist until they hit an enemy or explode after a fixed amount of time |
| [Rocket Launcher](#rocket-launcher)   | RL   | Launches rockets in a straight line until they hit a player or terrain                                                 |
| [Plasma Gun](#plasma-gun)             | PG   | Launches plasma projectiles at a fixed interval                                                                        |
| [Laser Gun](#laser-gun)               | LG   | Emits a fixed distance laser beam damaging the first encountered enemy                                                 |
| [Electrobolt](#electrobolt)           | EB   | Sniper rifle that emits a ray of light damaging the first enemy hit.                                                   |
| [Instabeam](#instabeam)               | IB   | Similar to the Electrobolt but it will one hit kill the enemy. This weapon is only available in Instagib gamemode.     |

#### Game variables

| Description              | [GB](#gunblade) | [MG](#machinegun) | [RG](#riotgun) | [GL](#grenade-launcher) | [RL](#rocket-launcher) | [PG](#plasma-gun) | [LG](#laser-gun) | [EB](#electrobolt) | [IB](#instabeam) |
|--------------------------|-----------------|-------------------|----------------|-------------------------|------------------------|-------------------|------------------|--------------------|------------------|
| Ammo/shot                | 1               | 1                 | 1              | 1                       | 1                      | 1                 | 1                | 1                  | 1                |
| Projectile/shot          | 1               | 1                 | 20             | 1                       | 1                      | 1                 | 1                | 1                  | 1                |
| <p><b>Timing (ms)</b><p> |                 |                   |                |                         |                        |                   |                  |                    |                  |
| Weapon Up                | 50              | 50                | 50             | 50                      | 50                     | 50                | 50               | 50                 | 50               |
| Weapon Down              | 50              | 50                | 50             | 50                      | 50                     | 50                | 50               | 50                 | 50               |
| Reload                   | 600             | 100               | 900            | 800                     | 950                    | 100               | 50               | 1250               | 1300             |
| Cooldown                 | 0               | 0                 | 0              | 0                       | 0                      | 0                 | 0                | 0                  | 0                |
| Projectile Timeout       | 5000            | 6000              | 8192           | 1250                    | 10000                  | 5000              | 850              | 900                | 8024             |
| Smooth Refire            | false           | false             | false          | false                   | false                  | false             | true             | false              | false            |
| <p><b>Damages</b></p>    |                 |                   |                |                         |                        |                   |                  |                    |                  |
| Damage                   | 35              | 10                | 5              | 80                      | 80                     | 15                | 7                | 75                 | 200              |
| Max DPS                  | 58.33           | 100               | 111.1          | 100                     | 84.2                   | 150               | 140              | 60                 | 153.3            |
| Self damage ratio        | 1               | 0                 | 0              | 1                       | 1                      | 0.5               | 0                | 0                  | 0.1              |
| Knockback                | 90              | 10                | 7              | 100                     | 100                    | 20                | 14               | 80                 | 95               |
| Stun                     | 0               | 50                | 85             | 1250                    | 1250                   | 200               | 300              | 1000               | 1000             |
| Splash radius            | 70              | 0                 | 0              | 125                     | 125                    | 45                | 0                | 0                  | 80               |
| Splash min damage        | 8               | 0                 | 0              | 15                      | 15                     | 5                 | 0                | 75                 | 0                |
| Splash min knockback     | 10              | 0                 | 0              | 35                      | 35                     | 1                 | 0                | 35                 | 0                |
| <p><b>Projectile</b></p> |                 |                   |                |                         |                        |                   |                  |                    |                  |
| speed                    | 3000            | INSTANT           | INSTANT        | 1000                    | 1150                   | 2500              | INSTANT          | INSTANT            | INSTANT          |
| spread                   | 0               | 10                | 160            | 0                       | 0                      | 0                 | 0                | 0                  | 0                |
| v_spread                 | 0               | 10                | 90             | 0                       | 0                      | 0                 | 0                | 0                  | 0                |
| <p><b>Ammo</b><p>        |                 |                   |                |                         |                        |                   |                  |                    |                  |
| Weapon pickup amount     | 0               | 50                | 10             | 10                      | 5                      | 50                | 50               | 5                  | 5                |
| Pickup amount            | 0               | 50                | 10             | 10                      | 10                     | 100               | 100              | 10                 | 5                |
| Max amount               | 1               | 100               | 20             | 20                      | 20                     | 150               | 150              | 10                 | 5                |
| Low threshold            | 0               | 20                | 3              | 3                       | 3                      | 20                | 20               | 3                  | 0                |

<div class="weapons">

##  Gunblade

<div align="center">
<img src="../static/gunblade.jpg" >
</div>

#### Description

The gunblade is a melee weapon that can also fire projectiles if you hold the upgraded version. When in close combat against an enemy player the gunblade will automatically spin and deal damage to the opponent. When fired the upgraded gunblade launches a small projectile dealing AOE damage in a small area.

#### Strategy

- The melee damage from the gunblade can be useful to finish off an enemy that is low and is in close range as you will have a harder time hitting them consistently with the other weapons.
- The AOE damage from the upgraded gunblade inflicts self-damage so you can use it to increase your speed or perform a rocket jump.


##  Machinegun

<div align="center">
<img src="../static/machinegun.jpg" >
</div>

#### Description
The machine gun is weapon that fires damaging bullets at a regular interval.

#### Strategy

- The bullet travel instantaneously so the machine gun can be used to snipe low enemies.
- Each bullet will stun the enemies so you can use the machine gun to reduce the speed of an incoming enemy.

##  Riotgun

<div align="center">
<img src="../static/riotgun.jpg" >
</div>

#### Description

The Riotgun is a shotgun like weapon that fires a burst of bullets. The spread of each shot is fixed, making it the ideal weapon for close combat as you will be able to land more bullets.

#### Strategy

- You can wait at the exit of teleporters with the riot gun, bursting the outgoing enemy.
- The riotgun can be used to finish low enemies as you will, at least land part of the bullet spread.



##  Grenade Launcher

<div align="center">
<img src="../static/grenade_launcher.jpg" >
</div>

#### Description

The grenade launcher is a projectile weapon that fires explosive grenades. It's a powerful weapon that can deal significant damage to both enemies and the environment. The grenades are affected by gravity, which means players need to adjust their aim to compensate for the arc of the grenade's flight. The grenades bounce off walls and other surfaces before detonating. This allows skilled players to use the grenades to hit enemies around corners or behind cover. 

#### Strategy

- The grenades have a small blast radius, so players need to aim accurately to hit their target.
- The grenade launcher has a slow rate of fire, which means players need to carefully time their shots.
- The grenade launcher can also be used to rocket jump, which involves firing a grenade at the ground beneath the player's feet to propel themselves into the air.
- It can be risky to use in close-quarters combat, as the grenades can cause self-damage

##  Rocket Launcher

<div align="center">
<img src="../static/rocket_launcher.jpg" >
</div>

#### Description

The rocket launcher is a powerful projectile weapon that fires explosive rockets. The rockets travel quickly through the air and have a large blast radius and can deal significant damage to enemies. The damage dealt will decreased with the distance of the enemy to the rocket's explosion, dealing a minimum of damage after a certain range.

#### Strategy

- The rocket launcher has a moderate rate of fire, which means players need to carefully time their shots.
- You can shoot at the feet of your opponents to launch them into the air, making them easier to hit with other weapons like the [electrobolt](#electrobol).
- The rocket launcher can also be used to rocket jump, which involves firing a rocket at the ground beneath the player's feet to propel themselves into the air.
- It can be risky to use in close-quarters combat, as the rockets can cause self-damage


##  Plasma Gun

<div align="center">
<img src="../static/plasma_gun.jpg" >
</div>

#### Description

The plasma gun is a rapid-fire weapon that fires streams of plasma energy. Each plasma bullet acts as a projectile and has a small blast radius that will inflict the damage to the enemies.

#### Strategy

- Aim at the feet of you enemies as the blast deals as much damage as the bullet.
- Spam chokepoints to prevent enemies from reaching a specific area as they will have to go through the stream of plasma to reach you.

##  Laser Gun

<div align="center">
<img src="../static/laser_gun.jpg" >
</div>

#### Description

The laser gun is a futuristic energy weapon that fires a continuous beam of energy. It's a powerful and versatile weapon that can be used for both offensive and defensive purposes. The weapons fires a continuous beam of energy that deals continuous damage to enemies as long as it's hitting them. However the beam has a limited range and can only travel a short distance before dissipating. This means players need to be close to their targets to use the laser gun effectively.

#### Strategy
- The laser gun is a very effective weapon against stationary or slow-moving targets as won't be able to dodge the stream.
- The laser gun has a high rate of fire and can quickly drain enemy health if the beam stays locked onto the target so it's important to practice your tracking skills use it as effectively as possible.


##  Electrobolt

<div align="center">
<img src="../static/electrobolt.jpg" >
</div>

#### Description

The electrobolt is a powerful long-range weapon that fires a single, highly accurate shot. It's a deadly weapon that deals great amount of damages at the cost of a slow firing rate. 

#### Strategy

- This weapon is very aim dependent so it's key to practice it.
- When you know the enemy's location it can be great way of dealing damage while outranging them.


##  Instabeam

<div align="center">
<img src="../static/instabeam.jpg" >
</div>

#### Description

The instabeam is an empowered electrobolt only available in [instagib](../gamemodes/instagib.md) that will oneshot enemies.

</div>