# Core changes
Increased starter abilities: from 2 to 4
Increased ability tree size: from 28 to 42. The ability tree UI has been modified slightly to accomodate this.
Removed zones 6 and 7 access restrictions, they're now playable without achievements and in any difficulty. Enjoy the full experience without needing heroic difficulty!

# Mechanics changes
**NEW** Area of Effect abilities. Those abilities are able to target all enemies or all friendly units. Hit chance is determined by the main target, but crits are rolled for each target. Each target will be affected by dispels and can receive a buff.
**NEW** Combined buffs. Some (de)buffs can now be stacked together into a single big buff. Adding a new stack will refresh the duration of all stacks, allowing for great ramp-up of buff-based builds, like for example DoT effects as a primary source of damage. Each stack will be dispelled separately and such buffs expiring will remove all stacks at once.
**NEW** Buffs are now able to trigger abilities, each turn or when they expire. This will allow for new effects and synergies. For example, a delayed bomb that explodes a few turns, dealing damage to the whole enemy team.

New buff effect: lifesteal. Heal for a percentage of *direct* damage done. Does not proc on targets with a subversion effect.
Heals now scale fully with element piercing. Normally, piercing only increased crit chance on heals, but the bonus to healing was always a fixed +50%. Now, the healing bonus is based on piercing, but will always be at least +50%.
Non-crit heals will also heal for slightly more based on piercing, in the same way as damaging moves.
Damage over time effects are no longer affected by element defense. This brings defense to parity with piercing, and means piercing/defense only affect direct attacks (and direct heals for piercing).
Dispels will now skip undispellable buffs, instead of being consumed by them. Failing to dispel a buff with dispel resistance will still count as a dispel.

## Other changes
Removed sitelock
You can now see if an ability's rank-up would change its cost or cooldown without having to spend ability points.
Moves can now scale with current health. Focus modifying moves can now scale with focus and current health.
Applying heals on targets with subversion will now adapt the floating number color based on the heal's element instead of the Shadow color.
The buff bar now shows up to 9 buffs instead of 7. The buff numbers are smaller

## Bugfixes
You now start with 19 stat points without having to re-spec. This removes the need for a level 1 re-spec, which was an obscure mechanic.
Some effects such as the "dull senses" debuff now properly affect piercing/defense from multiple/all elements.
Fixed an issue where hit chance was 1% lower than intended and capped at 99%. 
Refreshing an unstackable shield buff will now grant a new shield instead of wasting it. Shields also are now reduced properly when expiring, when a target has multiple shields.
Buffs that modify maximum focus now stack together properly