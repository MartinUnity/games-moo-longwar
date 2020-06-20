# Master of Orion - Mod

# Ideas for next release
- lategame missile
- early game beam + cannon?
- Torpedo base
- more tiered tech 

# 1.4.0
## Changes from 1.3.1
- Had many issues with multiple totalEmpireMultiplierBonus buildings
  - Changed some existing structure to system-unique buildings offering turn-based fixed amount
  - Others are now BC/pop, but much lowered (like 0.2 bc/pop - upgradable)
  - Reduced bc/pop for some of the existing money-generators, added more late-game
- Aligned created weapons to fall in between former-next weapon
- Antaran victory disabled; can now pick antaran event freely.
- Research Treaty: Lowered cost and reward
- Galactic Council: Upped frequency from 30 -> 60 turns
- Spies can now reach level 8 (expensive to maintain)
- Fixed required tag on all hydroponic farms
- Upped weapon + special slot for each ship +1
- Energy weapon bases (Upgradable x3)
- Cannon base (Upgradable x4)
- Mini star base - cheap, low spec, works as extra mini-starbase (upgradable x4)
- Made pirate ships slightly better (+5 space & hp, upped cost ~20%).
- Made pirate ships spawn 2x as many on each non-starting spawning turn
- Pirate destroyer+cruiser will spawn earlier and be much more powerful, but have no bombs; they can only blokade (but will amass)

Extra: 
- More pirates in each wave; make sure defenses are prepared for it.
- One also has to weave, flee and run from piratesat least initially - and again when pirate cruisers arrive
- Pirates can easily kill an outpost until early mid-game tech makes them strong enough.

# 1.3.1
## Changes from 1.3.0

### Highlights
* Reverted to original pirate spawn rate - several civs got wiped out by pirates in a play-through
* Kept pirate frigtate buff of 50% - and destroyer & cruiser 100%

---
# 1.3
## Changes from 1.2

### Highlights
- Added new upgrade paths to many existing fortifications - it will be much more difficult to assault a planet with all upgraded defences now.
- Added new planetary resources and mineral classifications
- Aligned costs of many new buildings to what they do
- Consolidated multiple techs into single techs
- Added a few low %-empire income unique buildings
- Pirates are now more of a threath - twice as many ships, frigate buffed +50%, destroyer+cruiser +100%
- Finally added a .csv file for better descriptions, will slowly fill out
- Added SuperHard difficulty - AI now gets +75% resources
- Slightly bumped silicoid prod on planets as they cannot benefit from all new building
- Created new names for many techs

### Details
* Added 2 new planetary Resource types
* Added 2 new miniral classifications (in each end of scala)
* Experimented with all types of bonusses from dotPeek colonystructuretype and have been creating buildings with these.
* Added Super_Hard Difficulty (+75%)
* New buildings - fortifications
  * Immovable Object (star fortress upgrade)
  * Missile base upgrades 1 -> 6 
  * Ground Batteries 1 -> 4
* New buildings - productivity
  * New poor/very poor/absurd poor - %-based buildings
* Miniaturization
  * Aligned with existing; added more mini for lowtech items so they could find a use again on smaller ships lategame
  * Added new mini for new techs

---
# 1.2
## Changes from 1.1

_Finally_ cracked the code open with dotpeek and found a lot of hardcoded settings, buildings, arch and stuff that I've built but is of no real use

* Trade treaty now runs 50 turns instead of 20: initial cost still 50%, but return is 100% total, not 200%

* Lowered Galactic Currencey Exchange to provide +50% empire credits instead of +100%

* Updated several odd %-based increased to better align and reduced cost for many new buildings by ~15-20%

* Armor / Weapon changes
    * More armor piercing for Pulse (always do min. dam, but can now do 2x dam on <10 armor)
    * Reduced Plasma beam damage 20% (4 steps instead of 5 at 30 dam)
* Used dotpeek to lookup all hardcoded values/techs and removed a bunch
    * All foodCarryOver buildings (UndergroundStorage, Foodie)
    * Ship (Mini Battle Pods (Battle Pods is hardcoded as single entity for > space))
* Small adjustmests / updated entities
    * Rifles (lazor, 0.2x rating (from 0.15))
    * Cut gravity generator cost by 50% - lowered maint 33%
    * Update toxic processor pollute removal from 7 -> 12
* New buildings
    * Biodome 2 (restricted planets, extra food) - tier 
    * New planetary shield - tier 15
* New Research
    * Deep sea Cooling 2
* Fixes
    * Moved biodome 2 to tier 3
    * Crust Prospecting 2 now properly unlocks building 2 and not 3
    * Many typos/fixed description

------
# 1.1
## More buildings, weapons & armor 

* Many new techs as pr. screenhost
* Many new buildings, weapons & armors. 
* Started to add Tier14 tech - will expand.

## Global
* Slightly tuned worlds for more moons (+10% chance) 
* Slightly larger planets (+2 pop on all planet-types)
* Buffed all ships (incl. pirates+monsters) with space and hp with a fixed +25% for a bit 
* Most new buildings are pretty expensive to maintain - been added as a money sink.

# Why create this mod?
Mod I started some years ago - spent a lot of time searching for again and decided just add here so I won't loose it again.

Wanted to have a much longer playing experience using Very Slow -- it still feels way too fast.

Feels like it is a race to money and then everything is dictated on that; trying to insert moneysinks into the game.

## Note
Works best on Very Slow or slower pacing for having time to utilizing any of the new tech.