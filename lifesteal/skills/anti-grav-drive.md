---
description: >-
  The art of graceful movement in combination with your gravity defying
  implants.
---

# Anti-Grav Drive

Experience with Anti-Grav Drive is gained by taking fall damage, successfully reversing fall damage on, or successfully dodging attacks.

120XP per half heart of damage is gained when taking fall damage. Assuming no damage is being reduced, it can also be calculated as `(b - 3) * 120` where `b` is the amount of blocks fallen before taking damage. Any reduction of damage by use of hay bales, potions, enchantments etc. will reduce the amount of experience gained. If a kinetic reversal or Alcubierre Drive activation has been executed, you will gain 80XP per half heart of damage instead of 120XP. This calculation uses the damage that would have been taken if you had not reversed the fall damage.

Feather falling will double the amount of XP you earn from falling, regardless of its enchantment level. Keep in mind that feather falling will also reduce the amount of base damage dealt when you fall.

Dodging an attack will give 120XP per half heart of damage dodged. So, if you dodged an attack that would have dealt you 3 damage, it would give you 360XP. This effect is called Flow State.

## Kinetic Reversal

Kinetic Reversal is an active sub-skill with a passive component. It provides a chance to negate fall damage based on the player's **Anti-Grav Drive** skill level. At level 50, the player has a 50% chance to negate damage, or 100% if **Alcubierre Drive** is activated. The chance for success is scaled against the Anti-Grav Drive skill level in a linear curve. Every level increases the chance to roll successfully by 1%. Therefore, it will always trigger at level 100.

A normal kinetic reversal can be transformed into activating the **Alcubierre Drive** by sneaking while falling. Doing so will double the odds to use kinetic reversal and the amount of damage prevented.

<table><thead><tr><th width="76">Level</th><th width="155">Kinetic Reversal</th><th width="171">Damage Absorbed</th><th>Alcubierre Drive</th><th>Alcubierre Damage Absorbed</th></tr></thead><tbody><tr><td>25</td><td>25%</td><td>7</td><td>50%</td><td>14</td></tr><tr><td>50</td><td>50%</td><td>7</td><td>100%</td><td>14</td></tr><tr><td>75</td><td>75%</td><td>7</td><td>100%</td><td>14</td></tr><tr><td>100</td><td>100%</td><td>7</td><td>100%</td><td>14</td></tr></tbody></table>

## Flow State

Entering Flow State will give you a chance of reducing incoming damage by half. For instance, if you are receiving 10 damage, you will only receive 5 damage when successfully flowing through the attack. You will never dodge an attack if the incoming damage would be lethal, this check is done before Flow State reduces incoming damage. Flow State also has a cooldown before it will award XP if the player recently respawned from a death.
