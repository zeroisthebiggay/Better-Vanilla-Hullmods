[0.96a-RC10] Better Vanilla Hullmods v0.5 - Last changed in 2023.12.17

Remove vanilla hullmod restrictions, restore hidden hullmods, and improve bad ones.

[Changes - v0.5] Siedge Invictus edition™

Modified 8 hullmods.

- Distributed Fire Control

	No longer blocks the installation of Integrated Targeting Unit or a Dedicated Targeting Core.
	However, the bonus to weapon damage reduction and EMP resistance is disabled if either of those hullmods are installed.

- Integration Suite

	Currently AI faction only hullmod that enables the S-mod bonuses of other hullmods. (5/10/15/25)
	This will allow the AI to use the new S-mod only effects(including built in mods like Heavy Balistics Integration) at an OP cost.
	Currently used in AI faction variants. If you want to test it out, use console commands allhullmods.

- Shielded Cargo Holds

	Now can be obtained during the campaign.

- Phase Anchor

	Removed incompatability with Adaptive Phase Coils, and vice versa.

- Reinforced Bulkhead

	OP adjusted to 5/10/15/25.
	S-modding provides an additional 5% hull bonus per D-mod.
	Reason for S-mod bonus on an expensive hullmod is that the "ship almost always recoverable if lost" portion gets invalidated since an S-modded player ship is almost always recoverable anyways.

- Blast Doors

	OP adjusted to 3/5/8/12.

- Experimental Phase Coils

	Added back into the game.
	OP adjusted to 5/10/15/25.

- Automated Ship

	S-mod effect temporarly disabled due to bug with Automated XIV variants. (looking at the s-mod menu would remove the automated ship hullmod)

Added 19 more variants to existing hulls from various factions. Modified some previous variants.

	These new vartiants use the new Integration Suite hullmod to utilize the S-mod effects.
	Include but not limited to: Rugged variants(Rugged Construction), Mobile Pargon(ATC), Mobile XIV(Fourteenth), Strike Monitor(Flux Shunt), Siedge Invictus(DTC) and more.
	Fixed Persean League not spawning custom variants of Monitor (Cancer class - Classic SO, Strike class - Flux Shunt S-mod variant).
	Slightly increased the chance for all modified variants to appear.

Misc.

	Compiled to JAR to avoid pre-compilation lag with Janino.
	Added version checker support.

[Changes - v0.4] Ill-Advised Modification edition™

Fixed potential crash with Heavy Balistics Integration when used with other mods.

Added 49 variants to existing hulls from various factions so that the AI can utilize the modified hullmods better. 

These range from simple changes like carriers using Nav Relay, to more radical and ill-advised ones like converted hanger phase ships to SO capitals.

These variants have around a ~30% chance to spawn over the original variants.

Energy Bolt Coherer is now known to the Sindrian Diktat and Tri-Tachyon.

Escort Package and Assult Package is now known to every faction.

Nerfed Escort Package and Assult Package. OP increased to (5/10/15/25).

Indirectly nerfed EP/AP by making Civilian grade hull no longer drop.

[Changes - v0.3]

[Vanilla Hullmods] - Hullmods that are currently obtainable but with restrictions removed and/or rebalanced.

- Safety Overrides

	Can now be applied on capital class ships (70 OP) and civilian ships.
	Can now be S-modded at the small "benefit" of applying ill-advised modifications. Praise Ludd.

- Shield Shunt

	Provides a 15% bonus to top speed in addition to the 15% armor. Basically the reverse of Makeshift Shield Generator.
	S-modding provides an additional 15% speed bonus & 15% armor.

- Converted Fighter Bay

	Can now be applied to regular carriers and not just drone carriers.
	Now provides a 1/1/2/2 DP reduction per bay removed.
	S-modding additionally increase hull integrity by 15% per bay removed.
	OP increased to 3/6/9/15.

- Converted Hanger

	Removed restrictions for ships with existing fighter bays and drone bays.
	Removed restrictions for frigates and phase ships.
	Increase DP increase threshold to 10.
	Cruiser/Capital ships and ships with existing fighter/drone bays will no longer suffer the DP penalty. All other penalties (refit, recovery, relaunch, crew) still apply.
	OP changed to 10/10/12/20.

- Makeshift Shield Generator

	Speed penalty reduced from 20% to 15%. Shield stat remains the same (90 degrees, 1.2 efficiency).
	Can now be applied to ships with existing shields.
	If the ship already possesses a shield, the top speed penalty is negated.
	Instead, the external emitter nodes are replaced with reinforced plating, increasing the ship's armor by 15%.
	Ships with omni shields will retain their ability use omni-directional shielding (60 degrees).

- IPDAI

	Reverted the strike weapon restriction. Antimatter blasters are now PD.
	S-modding is no longer required to make small non-missile weapons into PD.
	S-modding will cause ALL non-missile weapons to act as PD, with hilarious results.

- Defensive Targeting Array

	Also increases damage against ships by 10%.
	S-mod bonus increased to 200 range.
	S-modding will increase missile range as well.
	This will make DTA viable with bombers and other fighters, and not just Xyphos and Sarissa.

- Unstable Injector

	No longer decreases weapon range and fighter replacement times. Reduces CR by 10 instead.
	S-modding will boost the bonus by 3 times.
	However, doing so will cause the ship to not be able to decelerate.

- Dedicated Targeting Core

	Reduced OP cost to -/-/9/15 to make the S-mod bonus make sense.
	This will make the hullmod somewhat competitive in the late game, and buff factions using them.

- High Scatter Amplifier

	Reduce range penalty from above 200 to above 400. Should make 1000 range weapons competitive with ballistics like the storm needler.
	Now stacks with Advanced Optics.

- Shield Conversion - Front

	Restriction when used with Shield Conversion - Omni removed.
	S-modding now provides a 200% arc bonus instead of a 5% damage reduction.
	Stacking both front and omni shield will result in a 1.4x arc increase. S-modding both will result in a 3x arc increase.

- Armored Weapon Mount

	S-modding will now additionally reduce flux cost of weapons by 10%, (kinda) canceling out the flux increase due to fire rate change.

- Augmented Drive Field

	Reduced cost to 4/8/12/20 to make the S-mod bonus make sense.

- Neural Interface

	Adjusted cost to 3/6/9/15.

- Neural Integrator

	Adjusted cost to 4/8/12/20.

- ECM Package

	Lowered cost to 5/8/15/20 (Same as ECCM Package)
	Increase system range by 25% in addition to the usual ECM bonus
	S-modding provides 25% system regen and 20% system cool down bonus.

- Nav Relay

	Lowered cost to 5/8/15/20 (Same as ECCM Package)
	Now provides 15% top speed bonus to fighters launched from this ship, in addition to the nav rating bonus.
	S-modding provides 20% engagement range to fighters launched from this ship.

- Expanded Deck Crew

	Now reduces fighter relaunch time by 25% in addition to the regular bonuses.

- Recovery Shuttles

	Now reduces fighter replacement rate by 15% in addition to the regular bonuses.

[Restored Hullmods] - Vanilla hullmods that were not obtainable.

- Special Modifications

	The hullmod can now be obtained (rarity 3) and installed. Praise Supreme Executor Philip Andrada.
	Counts as a D-mod for derelict operations.

- Energy Bolt Coherer

	Now obtainable in the campaign.
	Combine with IPDAI + PD skill for 700 base range antimatter blaster.

- BDeck
	
	Now obtainable in the campaign.
	Added hanger requirement.
	OP changed to 5/10/15/25.

- Civilian Grade Hull

	Now obtainable in the campaign. Use to make ships not count towards certain skill calculation and for assault/escort packages.
	S-mod bonus negates the sensor range/strength penalty.

- Assault Package

	Added back into the game to provide a powerful tool for civilian grade hulls.
	No longer requires Militarized Subsystems. Now requires Civilian Grade Hull.
	Top speed and zero flux boost increased by 50%. However, can no longer decelerate.
	Weapon fire rate (including missiles) increased by 25%. Recoil increased by 100%.

- Escort Package

	Added back into the game to provide a powerful tool for civilian grade hulls.
	No longer requires Militarized Subsystems. Now requires Civilian Grade Hull.
	Bonus adjusted to 25% manuvability, 100 flat PD range and 25% damage against fighters and missiles.
	These bonuses also applies to any fighters launched by this ship.
	
[Built-in S-mod interactions] - Hullmods only featured in certain ships. Now can be S-modded to change the ship's role. Since it costs an S-mod, overall benefit should be similar to an officer's regular skill vs elite skill.

- Flux Shunt

	Can now be S-modded to provide the following effects:
	Bonus decreased to 25% of the normal rate while shields are on instead.
	The shunt is diverted to the weapon mounts. Weapons no longer generate flux.
	The intention is to provide an alternate viable monitor that leans towards offense.

- Fourteenth Battlegroup

	Can now be S-modded to provide the following effects:
	The heavier armor plating is completely removed. Negates the armor bonus and reduces it by 100.
	Increases top speed and maneuverability by 24% instead of decreasing it by 8%. Flux throughput and capacity remains the same.

- Advanced Targeting Core

	Can now be S-modded to provide the following effects:
	Zero-flux engine boost enabled regardless of flux level.
	Range bonus reduced to 60%.
	These bonuses makes the paragon behave more akin to a strike capital, such as the Radiant.

- Rugged Construction

	S-modding will now only reduce the effect of d-mods by 25%.
	Instead, each d-mod will increase hull by 20%, and armor by 20%.

- Heavy Ballistics Integration

	Can now be S-modded to provide a 1/5/5 OP reduction to all ballistics weapons instead. Better for downsizing and PD focus.

- Automated Ships

	Can now be S-modded to provide a -50% CR reduction instead of -100%.

[Installation]

	Copy the folder into /mods and enable it.

[Dependancy]
	
	Currently none.

[Compatability]

	Can be safely added and removed from existing games.
	May have issues with mods that interact or change these hullmods.

[ToDo]

- More S-mod interactions

	Add more S-mod bonuses to built-in only hullmods to drastically change the ship's role.
	Make D-mods S-moddable. Reduce penalty by half, does not count towards the S-mod limit and still counts towards Derelict Operations.
	Change Phase Anchor to have an interesting S-mod penalty.

- More balance

	Make makeshift shield generator apply to phase ships.
	Make shield shunt remove phase. (if you know how to do these, please contact me)

- More story?
	
	Figure out rules.csv and make certain hullmods only obtained by commission/raid.

- Mod interactions

	Lunalib integration to make changes to stats.
	Experimental Hull modification integration to act as a vanila-friendly frontend.

[Credit]

	Alex for the excellent comments.
