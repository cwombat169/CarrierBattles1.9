AIs
----
Rollo has made AIs!  Yeehaw.  Reccommended settings: High Difficulty, No Bonus.   Low bonus at most, if you're feeling masochistic ;)
Don't use EMPs to load the AIs, just let the game randomly generate them.  Feel free to add neutrals; particularily in high-density maps, the neutrals will be serious contenders and strong fighters.

Intelligence
------------
There is no intel defense.  However, the intel projects are more expensive, and less damaging than in stock SE4.  If you are under intel assault, it is a good idea strike back.  Destroying or capturing the enemy intel facilities is the best way to make them stop.
 - Sabotage projects can be disabled in game setup by turning off the tech area "Saboteurs"

Resources
---------
 - Don't neglect the organics and radioactives.  All races will need fairly large amounts of them.  Radioactives are required in large amounts for high tech shields and ammo-less weapons.

Ships and (Lack of) Movement
----------------------------
 - When designing a ship, the estimated speed does not take into account the possibility that you do not have enough engine ports.
You MUST have at least one movement point worth of engine ports, or your drive reactor will be useless.  The design editor does not take this fact into account, but any ships you actually build will most certainly require adequate engine ports.
 - In order to reduce the amount of clicking required on large ships, research propulsion.  This will give you the medium and large engine ports, which provide better fuel efficiency in addition to being larger and fewer.
 - Due to the fact that the mod uses leaky armor and shields, it is highly reccommended that you design your ships with an extra engine or two, since you will almost certainly take some damage to the engines early on in a battle.

Fighters
---------
 - Almost all fighters will have NO MOVEMENT points outside of combat.  This is normal.  You will need to build carriers to ferry them between combat zones.
 - ONLY ONE ENGINE per fighter is effective.  The larger engines provide more speed.  You may need to use a small engine on a bomber in order to fit the largest weapons on.
 - Research will provide Extended Range fighters capable of moving between sectors on their own, but they will naturally be less effective in combat compared to their short-range counterparts.

Point Defense
-------------
 - None of the available weapons will autofire like stock point defense.  You will NEED multiplex tracking (Gun Crews) in order to effectively defend yourself from multiple incoming missiles.  
 - Small-caliber guns on ships can target missiles, and though they hit immediately, they also require you to get dangerously close to the warheads.
 - Fighters are an effective form of point defense.  Try designing fast, lightly armored interceptors and give them a strategy with enemy missiles as their top priority.
 - NOTE!  Each single volley of fire from a fighter stack can kill ONLY ONE missile at a time.  For anti-missile duty, you will need to mix a wide variety of weapons and mountings in order to get more volleys per turn, and thus kill more missiles.  However, be sure not to spread the guns out so far that the fighters cannot do enough damage to KILL a missile in one volley.

Shields and Armor
-----------------
 - Shields and Armor are both "Leaky".  This means that your ships will take some damage to internals from the first hit.  Keep repair ships handy, and see the bottom of this file for tips on optimizing your defense strength.
 - Shields and armor together are more than the sum of their parts.  Use shields to reduce the incoming damage from each hit, and use armor to bulk up your hitpoints.

Pollution & Strip Mining
------------------------
 - Strip miners are available for all 3 resources.  They produce significant amounts of resources for very little investment, but reduce the planet's value as they work.  Value can be improved slowly with the use of system environmental agencies.
 - Heavy industries and cities all produce pollution, which compromises the conditions of your planets.  Polluted planets require more environmental facilities to be present before they will start to improve their conditions.

Ruins
-----
 - There are many types of artifacts to find in ruins.  After discovery, you will have to do some research on them before you gain the bonuses.
 - Racial traits of "Xenoarchaeologists" and "Ancient Scavengers" increase the effect of any artifacts you find by a large amount.

-----------
Tips&Tricks
-----------

Mount Usage
-----------
 - Armor mounts depend on the situation.  Smaller mounts provide more hitpoints, but larger ones can improve the absorption% of leaky shields.  Consider increasing your armor mount if you (1)Have more shield points than half the typical hit, and (2) Half the typical hit is greater than the hitpoints of a single (mounted) armor component.
 - Weapon mounts depend on the target.  Against ships, a larger mount is better.  You need the larger damage per hit to breach the shields.  Against fighters, the smaller mounts have accuracy bonuses at the expense of damage.
 - Missiles get mounts too!  You can reduce the tonnage size (external rack), or the supply use (launch tube).

Ship-Vs-Fighter Action
----------------------
 - Try to hold back enemy fighters with some heavily armored fighters of your own.   Your dogfighters can keep them busy while the capital ships lob missiles into the fray.
 - When choosing between regular and cluster missiles, consider the size and armoring of the targets.  Cluster missiles will kill any stack of fighters, but take more space and time to fire.  They are also slower moving.
Remember that the enemy fighters will have to group up in order to penetrate capital ship shields, which will leave them vulnerable to cluster missiles.  If they spread out, you will want to use regular anti-fighter missiles, since they can hit many small targets more often and with less wasted damage points.
 - Bring along support ships.  A few destroyers loaded with missiles and independent gun crews can really ease the pressure on your multiplexing.

Fighter-Vs-Ship Action
----------------------
 - You will be facing many missiles, so bring along a healthy complement of interceptors to pick off missiles and increase your survival time.
 - Bring your bombers in large groups for direct fire weapons.  You need the combined punch in order to penetrate a capital ship's shields.  
 - Missile bombers should be launched in smaller groups, since they will deal more than enough damage to a single target.  Having multiple groups allows you to bomb multiple targets.  Encourage them to target different ships with your targetting strategy.
 - Be prepared for dogfighters blocking your path.  Use some of your own to distract them long enough for the bombers to attack, or overwhelm them with long-range fire from your interceptors and direct-fire bombers.  Just don't let them pick off your lightly armored bombers!
 - Have a few ships providing fire support if possible.  A cover of anti-missile missiles protecting your bombers and some heavier missiles to distract the enemy interceptors from your attack fighters can be invaluable.

Shields and Armor
-----------------
 - Try starting with 2-3 shield generators and 15-20 armor, and adjust from there as tech allows.
How it works:
 - The incoming damage per hit is the most critical part of determining how well your defenses will work.  There are a number of possibilities:
1) You have no shields.
	- All damage accumulates.  Damage per hit has an insignificant effect.  Armor will absorb a percentage of the incoming damage slightly better than "the total armor hitpoints divided by the total ship hitpoints".  
2) The damage is MORE than twice your total shield capacity.
	- In this case, the shields will reduce the incoming damage of each hit by the total shield strength.  This effect looks very similar to emissive armor.
3) The damage is LESS than twice your total shield capacity.
	- the shields will absorb at least half of the incoming damage.
	- Armor can amplify the shield effect, causing them to absorb more than half the damage, as follows:
	3A) If the damage applied to your hull is not enough to destroy a leaky armor component, then you lose nothing, and the shields will get a second pass at blocking the partial "hull" damage during the next weapon hit.
Since the shields absorb half of this, and then half again and again, you never actually lose armor components, and the shields are thus absorbing up to 100% of the damage!
	3B) If the damage is enough to destroy an armor component, then the shield loop described above is cut short.  There is still some partial damage, since these things rarely come out to an even number, and thus, your shields will be absorbing somewhere between 50% and 100%, depending on the details.

Note:  Since the armor is also leaky, occasionally you will still lose components, even under situation 3A.  When you start losing too many shield generators, your defense will degrade to case 2, and then to case 1.

Given the above information, you will want to design your ships with enough shielding to reach situation 3.  This depends a LOT on the enemy you are facing, and their typical weapon loadouts.  Once you have adequate armor installed, you will want some backup shield generators in order to deal with damage, and unexpectedly powerful enemy weapons.
You need to have plenty of armor to avoid losing critical systems to damage.  Having armor provide at least 2/3rds of your ship's hitpoints is a good idea, and the more the merrier.  Armor thickness mounts will allow you to sacrifice hitpoints per tonnage in order to increase the hitpoints per component.  Thicker armor provides less total hitpoints, but also tends to take hits more often, and can push you from situation 3B up to situation 3A.  
However, you must also plut enough armor to prevent hits from destroying your shield generators.
An optimal balance of shields, armor and armor mountings will provide you with a ship that suffers absolutely no damage from most hits, and whose defenses degrade gracefully instead of collapsing suddenly.  This is a fine art, and will have to be balanced against the enemy's ever-changing weapon loadout and your economic situations.