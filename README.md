# Mayhem-3-Zero-Hour


Features:
- the ultimate 'Mayhem+' addon.
- adds strategic faction AI
- Xenon Crisis mechanic
- new 'Nomad' faction
- expanded Pirate behavior
- tons of Quality of Life improvements, fleet settings, reduced frustration, less micromanagement, etc.
- play a rogue nation / pirate empire!
- improved economy. Resources actually matter and the AI is able to handle it. NPCs build their ships with less discounts and cheats. Their costs are similar to yours. Factions can realistically be starved of ship components, but they also got the brains to fix shortages better.
- more customization


Installation:
- extract the download archive into your game directory (C:/games/x3 terran conflict/), override everything
- new game required
- creation of 1 galaxy required*


*(The Galaxy Generator needs to update certain textfiles. You need to run it once. Afterwards you could switch back to old galaxies.)


What you should know:
- there are no fundamentally different mechanics for the player. Most changes affect NPC behavior
- all ship & weapon stats are base Mayhem 3
- the OCV/Xenon can escalate pretty fast, but don't worry! Its completely intended that they eventually own about 30-50% of the galaxy. At this point the factions will panic and temporarily merge into the United Commonwealth (UNC) to take initiate extreme countermeasures. In my test games the UNC always won the Xenon war without my help. Afterwards there will be some time of relative peace and healing for the galaxy until the Xenon cycle repeats.
- better keep your starting territory away from the OCV portal sector !!! (i got a DLC planned which will allow you to setup kind of stealthy/hidden sectors close to the portal using a new Outpost perk)
- the old meta was to manage extremely long ship construction times & setting up multiple shipyards. The new meta is resource scarcity. You need much less shipyard Outposts! Every crafting project will be so fast that construction times should rarely be an issue anymore, but the resource costs are a bit higher for everyone. There will be times when the galaxy simply runs out of resources. This naturally lowers AI aggression and allows the universe to heal
- almost every unit in the game received at least some AI tweaks. In general the NPC ships behave much less like 'mindless killing machines' (attacking everything in sight like mad crazy). It makes the universe a lot more believable and less frutstrating. Almost every ship has a job and goals. And it won't get distracted so easily anymore. Capships don't chase after explorers or satellites, pirates don't mess with the military, even the Xenon don't really care about certain ships.
- pirates are more powerful and they come in groups now! The boss of a pirate gang is their weak spot. When he dies the group becomes very vulnerable because they have to flee and scatter.
- NPCs cannot claim unknown sectors until the player owns at least one. Just completing the Ascension quest is not enough. This is to your advantage, so take your sweet time with the starter TL and choose a good first sector!
- once you have claimed one the other empires can claim all the remaining empty sectors MUCH faster than you might be used to from stock Mayhem 3! This is also intended. Tip: use your beginner research station and maybe build some cheap factories to quickly expand into additional nearby sectors. (pre-Mayhem 3.15 the game was always trying to prevent these rush strategies, but now all restrictions are gone and Zero Hour keeps this philosophy). You can immediately go & grab whatever neutral sectors you can get! There is no real downside to this and it will not raise a hidden threat level or make your enemies stronger.
- in the Zero Hour mod it could be much more difficult to get enough initial station support slots to be fully self sufficient. But there are new ways to play your empire tall !!!
- take a very close look at trading stations! They have a completely different range of goods now. You can realistically supplement your economy with certain resources. The AI is also able to do this and will optimize their overall ship component production. Ship parts can be much more difficult to obtain, so maybe focus a bit more on producing them early because nobody will really be willing to sell much of them (if any at all). All lower tier resources which are required to produce ship parts are often available on trading stations.
###- your starter TL comes with a mobile factory kit and it is much more useful now because it can produce in a loop just like a real factory! Even on the fly! But keep in mind that it consumes double the resources and takes longer.
- in Zero Hour your freighters can safely travel through hostile sectors! Enemy stations might not allow them to dock or trade, but the other nations respect certain rules of war (which forbids them to attack innocent freighters). But the AI is basically just roleplaying here. If you destroy a freighter from the main factions there is no additional penalty besides the reputation loss
- you'll find completely neutral traders without a faction name. Those can be destroyed to steal their cargo. The reputation and cash penalties for doing this have been replaced by a new 'infamy' system, which is much more manageable than bad reputation. This makes a pirate playstyle actually viable since you can attack certain ships without trashing your reputation with the major factions (and them invading you)


Now go and play already!




Full Documentation:


General Changes/Fixes:
- M3/M4/M5 combat AI ported directly from SWM3 with a few adjustments -> proper dogfights -> fixes most friendly fire issues
 -> fancy maneuvers like speed dependent flanking positions and evasive flying during fallback to let shields recharge
- satellites and jump beacons are more stealthy and survivable. Loosing them is less frequent and  annoying. NPC empires generally have a larger selection of sector invasion targets from this. - NPC capships should never chase after satellites anymore. This was always a complete waste of time for them (excluding OCV defenders in the Maelstrom sector) - pirates almost always ignore all satellites - the main NPC empires only have 2 types of squadrons which can even detect satellites and jump beacons. The police, but it needs to pass a sensor check and often overlooks satellites - Task Forces will always detect them (but factions have very few of those squadrons). - small Xenon patrols still destroy satellites pretty consitently
- fixed ship self defense and sector defense command not working correctly, especially OOS. Moving to a new position had a higher priority than choosing targets or shooting back at attackers. This could cause major disadvantages for slow capships.
- small ships can follow each other at much closer distance
- cargo scanning without the correct license has no additional penalties anymore. You only loose a tiny bit of reputation if you scan a ship of a major NPC empire. Scanning neutrals is always free
- added a small cash and reputation reward for uncovering a smuggler, but only if you have the police license
- added some UI and flavor sounds
- Battlegroup sector claims get a bonus on duration depending on jump distance on the galaxy map (+10% per jump) 
- removed minimum duration between two claims of the same Battlegroup
- NPCs cannot claim unknown sectors until the player owns at least 1 sector
- partially fixed a nasty bug where an Outpost could lie to a squadron that he is currently building reinforcements for them, but actually he wasn't. Now he needs to be building something to even make that statement. So at the latest when he has finished building what he was building he must stop lying to the squadron.
This was only a serious problem when squadrons required to be at full strength before being able to leace retreat mode and head out again (which is only a thing in this mod. Vanilla Mayhem 3 just had a t-file option to activate this behavior globally). Squadrons could get stuck because they would believe that they were still getting reinforced by the lying Outpost, so they wouldn't order any more ships and never reach full strength
- total wars get paused during coalition wars. Defeating the shared enemy is more important.
- when NPC squadrons switch homebase there is a small chance that they can ignore all the usual homebase jump range restrictions. This helps to prevent that fleets can get stuck in some corner of the galaxy. The new homebase selection is also a bit smarter. For example it will avoid choosing distant enclave sectors when the faction is in trouble.
- loot drops from freighters (TS/TP) always include all resources they carried, but not all of the equipment
###- faction Looter Workers can pick up Waste now (to be able to clean up after Nomad Recyclers)
- the starting TL comes with the mobile factory kit


Quality of Life:

Miner Worker Unloading
- now Miners go and drop their cargo already at 3000 filled volume
- t-file setting. Many players want their Miners to head home more frequently to get constant access to the color crystals or to reduce the risk of loosing an entire cargo load. Others like me just buy those crystals elsewhere and want their Miners to stay in space as long as possible to maximize overall profit and mining time. Now you can tweak this yourself with a new setting. To disable this premature unloading set it to 0.
- only checked by Player Miners & only after switching to the next asteroid debris chunk

Whitelist for Explorer Workers:
- allows you to define sectors which should always be monitored with satellites, even when hostile or blacklisted.
- best used in combination with automatic Worker replacement

QuickTrade:
- modular trade presets. Unlike the stock presets they are actually useful
- optimized for passive income and balanced storage levels. You should have less cash issues. Also saves lots of time and could be useful to learn about trade settings in Mayhem 3 and how to set everything up.
- basically you just select a general role for your Outpost (like should it build ships or stations? with or without buying the missing parts? or should it just craft lasers to sell for profit?  Buy the required food and selling the others, etc.) After a few mouse clicks QuickTrade has automatically set up dozens of trade thresholds and auto-cash transfer for you. All in a way that immediately works and makes sense. You can still dive in to configure in detail.

Storage UI:
- the 6 important ship and station crafting materials simply get highlighted in the Outpost storage overview. At first glance you can see how balanced the total values of your stocks are. Saving up lots of Hull Plating is useless if you don't also have the required Computer Components and Quantum Tubes to back it up. Building ships and stations always consumes all 3 resources at an equal rate (average credit value).

Galaxy News Settings:
- greatly reduced on-screen notification clutter!
- ministry of war got 4 new toggles for each faction (at the bottom of the diplomacy tab). With those you can control which galaxy news are shown on screen for this faction. 1) their sector claims, 2) their claims expiring 3) them conquering sectors 4) their protectorates expiring.
For example you can disable everything but still get notified when an Argon protectorate times out, so you know when you can attack them again.
Also added a new t-file setting which controls how these message settings get first set on a new gamestart. Either showing everything (vanilla Mayhem), showing nothing, or hiding just the most useless info like claims, etc. and only notifying about actually conquered sectors (this is the new default).
- any messages concerning player sectors or the creation of new abandoned sectors will always be shown to you

Mobile Factory Loop Production:
- TLs with the mobile factory equipment can now be told to produce constantly on a loop!
- production will begin whenever the required resource is detected in the cargohold
- it only stops once you turn it off in this screen
- this works completely passive in the background. The TL itself can be flying, fighting, docking, even crafting another one time order like a jump beacon !!!
- when using Couriers to supply your TL with resources better use something like the 'Maintain' Courier command as the 'Unload' command would overfill him
- your TL warns you when he doesn't have enough free cargospace to finish his current batch of passive crafting
- stopping the loop production will still finish any current crafting. You won't loose those resources. But you cannot start a new loop production until its done.
- don't be impatient with this. The passive crafting always needs a minute or two before registering new wares in the cargohold.


Automatic station building - Architect Worker:
- lategame this was a pain. First you had to produce station construction kits at an Outpost, then wait until they were finished, then not forget about them, dock your TL, remember which factories you wanted, load them up (but not all because cargospace is limited!), tell the TL where to go, wait until its there, remember that you had sent him, now finally build the factories. This chore required to go through countless sub-menus and commands with lots of downtime in between. Its fine for the first 10 sectors, but then...jeez
- now you can queue up factories with a single click!
Each Outpost has a new 'Architect' backlog in the Administration section (where the perks are, not in the station crafting menu)
- the Architect is a TL Worker which automatically builds all stations that you request in each sector
- your empire can only have 1 Architect
- he doesn't have any jump range restrictions
- his homebase needs to be an Outpost (which should be good at station crafting and also well connected to your jump beacon network)
- the Architect can only build 1 station at a time. Doing it yourself will always be faster, but at some point you won't care anymore and want it automated
- he puts the stations close to the Outpost which ordered them. Mines get placed on the best yield asteroids
- he avoids to work in sectors with big or huge enemy ships inside and simply does them later when the danger is clear. Also tries to fly on a safe path (not perfect)
- he automatically orders a replacement station kit if he takes one from a stockpile that the player has crafted manually
- there is no Architect command for the TL itself. You just define a TL to be your Architect and from this point on he just is, even when you use him for something else. He will always resume with his Architect task whenever you tell him to dock at his homebase.
- he only needs a small portion of his cargospace to do the Architect work. You are completely free to use the rest. So you can still manually order him around to place jump beacons for you, transport goods, craft things with the mobile factory, etc. When you don't want him to do Architect work, either unassign him as Architect, unassign his Outpost homebase, or just park him in space or at a different Outpost.
- if there is any problem, like when you filled up his cargospace too much or want him to build a second research station, or he cannot find a matching asteroid for a mining station you ordered, etc. he will either fix the build order queue himself (and notify you), or request that you empty his cargo a bit more.


Fleets (Player):
- new fleet setting: monitor all sectors of a specific faction. Very useful on the player empire itself because it completely removes the need to update the monitored sectors list on every response fleet each time your territory grows. This works as an addition to the monitored sectors list. So for example you can tell a fleet to monitor the player faction + that Paranid sector XY at your border + another Unknown sector Z which has a pirate base
- new fleet setting: retreat from a specific enemy ship class. Your fleet will disregard just GTFOs once it detects that particular enemy ship class. Very useful to reduce small ship losses and keep those fleets away from bigger enemies. It works as an addition to the standard strength based retreat threshold. It also includes all larger ship classes. So for example if you set it at the lowest setting 'TM', then your fleet will not respond into monitored sectors which have an enemy TM, M8, M6, M7, M1 or M2 and it will also retreat from such enemy classes. If you set it to 'M7', then your fleet would avoid M7, M1 and M2
- added a new retreat threshold '1:1'. With this one your fleet only engages when it is definitely stronger than all enemies combined. Now you can setup very careful fighter response fleets to monitor your own sectors with almost zero losses. For enemy sectors this new 1:1 setting is often too sensitive because there are usually many smaller patrols roaming around which stack up quite some combat power. And your fleet could be too afraid to go there at all
- fixed bug where the retreat threshold was actually always 1 higher than displayed
- freighters are now always excluded from any military strength comparisons because they are never such a threat that any fleet should ever retreat from them (or refuse to enter these sectors)
- strength comparisons now always take all enemies into account. Even the ones that you have set to be ignored for sector monitoring (fighters, big ships or huge ships) Just because you don't want to attack these targets doesn't mean that your fleet should ignore them when considering enemy military presence.
- player fleets don't attack any freighters or satellites anymore and will never get distracted by them.
###- 3 new fleet targeting priorities have been added. 'Freighter' (you can use this to hit the supply lines of an enemy empire), 'Stationary Ship' (this targets enemy satellites), and 'Piracy' (this makes them hunt down only neutral company traders which carry something. Nobody cares much about these neutral guys, so this is safe & easy loot. But you will gain infamy.)


Strategic AI:

The NPC empires finally understand a couple of important things:

- how large their territory is
- how powerful their military
- how many resources they have stockpiled
- how dangerous the Xenon/OCV are for them
- how many freighters they are loosing lately
- if enemy capships are secretly roaming around and just endlessly killing all their smaller patrols

Each empire evaluates these parameters and might react to them, or solve certain problems in pretty creative ways.
Its definitely not perfect, but probably better than the faction AI that X4 had cooked up  :-)


AI reactions include:
blacklisting sectors or entire factions
telling ships to fly on safe paths
ordering the construction of additional squadrons (extra police to fix a local pirate problem, etc.)
invade important sectors with high station support or special strategic location on the galaxy map
peace agreements with other factions
manipulating own Xenon reports to work either towards or against the declaration of a Xenon Crisis
general usage and range of deep strike invasions
retreat & overmatch factors, including very cautious behavior with full fleet buildup before invasions
general usage and sector targets of synchronized overkill invasions from multiple jumpgates
abandoning the general area around the OCV portal sector & slowly migrating away from it
force concentration & fleet grouping
alternative squadron roles & behavior
sending raider fleets to hunt freighters of a deeply hated enemy (committing warcrimes)
trying harder to locate pirate bases
fixing strategic component shortages by building the required factories
recycling unnecessary factories to free up station support slots
deciding against self sufficiency and instead actively sourcing commonly available resources from nearby trading stations to save lots of station support slots and optimize own ship part output (to build more ships overall)
hiring mercenaries
activating the Lasertower perk on Outposts

Not all factions play smart
there are also sentimental motivations with reckless or stupid behavior
for example everyone wants to control his own dejure sectors, even if the sector stats are actually crap (its like an ancestral homeworld to them)
the general rule is: if a faction has problems it plays smarter (minMaxing). If they do well they can also pursue sentimental goals whithout any real gameplay advantage
galactic superpowers which have basically won the game and nothing really left to do will eventually develop a good vs. evil personality, which affects their entire behavior a lot
this depends mostly on the species at hand (Borons tend to become benevolent protectors, Split mostly become evil tyrants) You can customize the preferred ethos of each race in the t-file. This is only their chance to become good OR evil. It doesn't determine how good or evil they will be.




Terraformers:
- this mod is centered around the concept of a cyclic Xenon Armaggedon. Xenon and OCV will work together as the Xenon Empire. They can grow quite powerful and threaten the galaxy. This eventually leads to the 'Zero Hour'. All factions will unite to beat the machines back in a massive war. This cripples the Terraformers for a while, followed by a long period of peace and healing for the galaxy. Once everyone has rebuilt and saved up some resources the internal conflicts will start again. This also allows the Xenon to grow powerful again, and the cycle repeats.
One full Xenon crisis 'cycle' should last no longer than about 1 ingame week.
- i got a DLC planned which will allow you to permanently defeat the Terraformers. But right now its just an endless cycle of death and rebirth for them
- the OCV Maelstrom now always spawns in a more isolated Xenon sector (far away from the rest of the galaxy).
- the general area around this portal is more dangerous than before. The location of this sector is so important that it will get revealed to you just after gamestart (a new t-file setting can also hide it if you like)
- all Xenon forces have a maximum fleet limit. Their main job is the defense of the Terraformer territory with only little offensive action. The OCV is their primary way to gain new territory. OCV is always on the offense and doesn't have any top limit for their total navy size.
- most Terraformer fleets are a bit smaller and they have a new capship limit. Individual fleets should be a bit weaker
- they also tend to spread around the galaxy more. Its less likely that the Xenon or OCV can create undefeatable fleet stacks. A single Terraformer fleet is much easier to stop, even OCV. But the entire Terraformer faction will also spread much faster now.
- the OCV doesn't prefer sectors with higher abnormal signals anymore. Most often they will just expand 1 sector at a time, starting from their Maelstrom portal. But there is also a chance that an OCV invader fleet performs a deep strike which targets a distant sector up to 8 jumps away from the closest Xenon border! To prevent that this can wipe you out too early just because of bad luck these OCV deep strikes cannot target any player sectors until your empire is already well established. But it could still target the NPC sector next door and you afterwards, so be careful.
- on normal and hard difficulty the OCV starts the game with additional ships
- between station kills OCV invaders randomly hesitate a bit and just patrol the sector for a short while. This slows them down a bit.
- added a t-file setting to modify the general OCV ship construction speed. With this new setting you have great control over how much the Xenon/OCV and this entire 'Crisis' mechanic will be a factor for your playthrough. Mostly want only faction war? Then tone the OCV ship construction way down and they will probably never manage to threaten the galaxy.
- added a new t-file setting whether OCV production speed scales or not. On default this boosts their ship production when they are still weak compared to the main factions. But it also nerfs them once they are more powerful or after they have been defeated in a Xenon Crisis. If you don't like the idea of cyclic activity and long periods peace then you can disable this and the Terraformer threat will be less cyclic and appear at very steady rate.
- main factions will sometimes withdraw their sector claims against the Xenon after destroying their central station. This turns the sector abandoned and available for anyone to claim. Its much more likely to happen when the conqueror already has a very large empire or during a Xenon Crisis.
- the OCV honk sound effect only gets played once during each Xenon Crisis Cycle (Terraforming missions unaffected)
- the Xenon now slowly reinforce their territory, especially the area around the OCV Maelstrom sector. Their periphery sectors tend to get fewer and much weaker fleets. This will never be able to cover all their sectors but the Xenon territory should feel less barren and deserted than before.
- these extra Xenon fleets can become quite numerous once they have a big empire, but they are only defending. The Xenons have separate invader forces (both small and large). But overall their offensive capabilities are pretty limited compared to the OCV and they can only ever destroy sectors and not conquer them for the Xenon Empire.


Xenon Crisis - 'Zero Hour'
- Terracorp has the special ability to put sectors under a protectorate status. Now they can use this ability on a truly large scale and force everyone to fight not against each other, but together in a huge coalition against the Terraformers. This will create the United Commonwealth (UNC), consisting of the Argon, Boron, Paranid, Split, Teladi, Yaki and the Player. It temporarily overrides all coalitions, total wars, permanent wars and lets all NPC factions share resources.
- the combined UNC forces will usually completely steamroll the Xenon Empire and conquer the lost half of the galaxy back in less than a day.
- Terracorp will only bring the UNC to life when the Xenon Empire has become a serious threat for the galaxy (they don't do it just to save one faction from extinction). To estimate when it might be necessary to act Terracorp relies on feedback from all empires.
- each faction constantly sends special status reports, which tell Terracorp how dangerous the Xenon Empire has become. These sitreps always get manipulated to convey a certain undertone.
- weak factions with most of their sectors closer to the OCV portal or many Terraformer fleets roaming around tend to paint the situation very grim and urge Terracorp to pull the trigger and enforce the global ceasefire earlier
- strong factions with most sectors further away from the portal and fewer Terraformer fleets tend to downplay the Xenon issue because they want to continue their faction wars undisturbed
- the player also constantly and automatically sends his own status reports to Terracorp. You can toggle their special undertone in your personal journal
- on default you will downplay the progress of the machine empire, assuming that the player generally does a good job with his sector choices so that the Terraformers are often quite useful to him and hurt other empires much more.
- initially your influence over Terracorp is very low because they rank these reports based on relative military strength between the main factions.
- Terracorp listens much more carefully to what an absolute majority (of combined military power in the Commonwealth) has to say. This military majority gets controlled by the strongest factions, who generally don't want an alliance unless they already have a serious Xenon problem of their own. But there is some chance that Terracorp might also get swayed by a minority and enforce the alliance anyway.
- Terracorp has its own secret agenda and would like to see a certain level of Terraformer progress in the galaxy (measured by Terraformer territory size and fleet power). This goal is always hidden and a bit random. Before the Terraformers have not reached a progress kind of close to those goals, Terracorp will not even consider listening to what any faction report might have to say about their progress, whether its lying or not. The global Alliance just can't happen at this point. If the player is already working towards the creation of the alliance with his Xenon reports, he will 
occassionally get a hint message which just tells you that your efforts are useless right now. There is no penalty if you keep exaggerating your reports.
- added a new diplomatic favor action which allows you to write the Xenon reports for other empires. But first you must have some significance, aka military power. You can use this favor to help unite the galaxy earlier if you have trouble with the OCV. Or maybe delay it to see a certain faction get crushed by the Xenon first.
Note that this favor cannot be used on a superpower (AI with 'Tyrant' or 'Galactic Protector' personality)


Pirate Gangs:
- obviously a group of pirates is much more dangerous than a loner, but pirate gangs also have a unique weakness
- when their boss dies the entire gang will run for the hills and cannot attack anymore! Eventually the survivors will snap out of their panic and become loner pirates
- a pirate boss already starts his journey with a nice bounty on his head, which makes him an attractive high risk, high reward early game target. If you manage to assassinate this one guy you will rout his entire group and don't need to finish the fight. Gang leaders can be recognized by their unusual ship choice and the more intense paintjob

Pirate Carrier Tactics:
- pirates also use very fast TMs for tactical redeployment, mobile repairs and hot-drops
- their only job is to pick up pirate fighters and drop them close to a good victim
- they always perform hot-drops and will immediately abandon their fighters to offer a ride for others too
- if the local pirate density is too low he heads back to the nearest pirate base to get a fresh group of fighters + a repair/resupply for himself. Sometimes he also picks a completely random pirate base to switch general operation area.
- the extreme speed on these carriers makes them the ideal transport to pass through sectors with heavy military activity and hot-drop fighters on easy civilian targets
- unlike standard pirates the TM doesn't move completely random. He generally tries to transport pirate fighters a bit away from the more abandoned areas with lots of unknown/Xenon sectors and more towards the civilization (where their freighter targets are)
- he can pick up and evacuate pirates from dangerous sectors
- this TM tries to be very evasive and never stops moving for long. He actively approaches pirate fighters and quickly beams them inside with his docking teleporter.
- during travel he tries to cut a few corners, often outrunning any pursuers and generally flying a bit outside of the main traffic
- if this carrier does get attacked during transit he launches his docked fighters, but won't stop to fight with them. He just leaves to ensure his own survival and picks up other pirates somewhere else.
- slowly repairs docked pirate fighters on the fly
- has chaff and all CCDS systems
- each successful hot-drop will add a bounty to these carriers. It can get pretty high because they will never react to any attacks and always just keep flying away very fast. But their turrets shoot back.
- lucky bounty hunters can really score a jackpot here. But you cannot farm them too much. If their bounty gets higher than 500k there is a small chance that they clear it on each pirate base visit (Pay 'n' Spray style like in GTA)   :-)


Pirates General Changes:
- now they are the cowards they should've always been and will just focus a lot more on easy targets like freighters. Usually they won't risk their hide by provoking the military or wasting time to chase after satellites.
- more wandering. When a loner pirate or gang leader would search for a new victim there is a 50/50 chance that he aborts and heads to the next sector instead. This makes the pirates much less aggressive and also spreads them further across the galaxy.
- sometimes a pirate will stalk a freighter which managed to escape him and could safely dock at a station. The pirate will lay in wait near the station until his victim undocks again. But he usually gives up when the target manages to flee back to the same station again.
- the chance to spawn M5/M4 fighters is much lower (most freighters are too tough for them anyway). Most spawns are loner M3 or entire pirate gangs. Loner M6 are still quite rare but gangs can also have up to 3 M6 (rare).
- there can only exist up to 15 TM raid carrier gangs and 20 M6 gangs, but the spawn chances for these already get lowered well before they would reach these theoretical limits.
- loner pirate fighter waves can spawn with double ships, depending on the current pirate population
- pirates focus much more on freighter targets. The chance to target a military ship, satellite or mercenary group is extremely low (because why would they?)
- maximum pirate population limit is now 70/100/130% of the number of sectors in the galaxy, depending on difficulty level. Also dded a new t-file multiplier to further  tweak this. If you set it to 0 the game will use the fixed vanilla Mayhem pirate limit (the default 50 pirates will be way too low!)
- pirate respawn cycle is now soft trending and wants to keep their ship population at around half the allowed maximum. Less competition makes a criminal career more attractive, while more pirates would lead to less booty for everyone so many pilots would rather like to do something else. Usually the factions do a good job so that the pirates never even reach half their pop limit. But theoretically they can escalate more.
- a new t-file setting controls the intensity of this trending effect. If there are too few pirates in the galaxy they will appear at a higher frequency, if there are too many they will respawn slower. Reducing or disabling the scaling effect makes pirates appear at a more steady rate like before.
- the default scaling factor is only 2. If you increase it to 3 or even 4 the global pirate activity will feel like they're coming in big waves. Sometimes all at once, sometimes almost none for 1-2h.

Pirate Bases:
- pirate bases are better hidden from the NPC empires. Only Border Patrols and Rearguard squadrons can find and engage them. Both need to pass a sensor check first and the Border Patrols are much better at this. For a more defensive oriented faction AI its also much easier to find the pirate bases in its territory
- you can still annihilate the pirate faction but this is more difficult. Earlygame all you can do is to destroy nearby pirate bases to hopefully push them a bit away from your local corner of the galaxy. But this is also less effective because the pirates from other bases wander more and might still reach you from time to time. Especially the TMs will hang out where there are no big or huge ships.
- additional pirate bases can spawn until the pirates and  Yaki are completely annihilated. Their station respawn rate is very slow (on average it takes 1-2 days to spawn 1 base) so it remains possible to wipe them out before their next base can respawn. But it requires a concentrated action by the player. The AI usually won't be able to do it for you. New pirate base locations are mostly random, but they tend to keep greater distance to already existing bases and Yaki sectors in order to spread pirates across a larger area of the galaxy. And they are more likely to spawn inside the territory of a faction which is currently using a more offensive oriented AI (that makes their bases more difficult to detect for the NPCs). The top limit for pirate bases gets reduced when the Xenon territory is larger (Example: the standard limit from the base Mayhem t-file allows for 8 bases. If the Xenon own 36% of the galaxy, then only up to 5 bases could spawn).
- the pirate base respawn rate is getting faster when there are less than 4 bases left. But not once there is only 1 base left. This should give you enough time to find it and finish the pirate faction off. Yaki Outposts are not counting towards pirate bases, even if they will also spawn pirates.
- added new t-file setting: chance to spawn a pirate base every 10h (default 50%) Set this to 0 if you don't want any bases to respawn
- added t-file setting whether pirate bases can also respawn in player sectors (default no)
- when a base gets destroyed there is a 50/50 chance that an angry pirate Warlord spawns in a lone M7



Economy Overview:
- NPC empires will start the game with only half their usual resource stockpile
- resource shortages in factories should be much less common. The production rates are unchanged but the resource distribution in the galaxy just works better and more balanced
- population is more significant for the player because your ships can get built so quickly


Corporations:
- trading stations are now a vital part of the global economy. They serve as major resource distributors but they don't cheat additional wares or consume them magically like in vanilla X3.
- neutral traders are no longer owned by the companies (technically they are, but the corps won't care if you shoot them down. The idea is that they are all just freelancers that nobody really cares about.)
- the range of goods has been greatly expanded and also mostly harmonized between all 5 companies
- both tier 1 resources (Waste & Energy Cells) and all final Outpost crafting resources will never be available on any trading station. All intermediate resources will (everything which comes from a factory and goes into another factory).
- every corp also trades all shields & all general weapons (commonwealth lasers + missles) and the weapons of their aligned race (Markus corp has all Argon lasers and missles, Oceania inc. has Boron gear, etc.) You can craft weapons or shields and sell them almost everywhere now (previously this only worked with certain companies) Your margin will be a bit lower due to the rather limited crafting spec growth on your Outposts. But it should never run at a loss.
- all corps trade in 1 specific type of food, except Salecrest which always trades in 2 completely random food types on each trading station
- every corp trades in all colored crystals + minerals
- trading stations have their own separate closed market with each other. They use Terracorp Interorbital Storage to move freight around.
This ware teleport is a bit cheaty, but it helps the entire economy to remain stable even during lots of Xenon activity. Factories which got cut off from their supply chains in some remote corner of the galaxy can still get a few external supplies through neutral corporations and traders (which are still always cloaked/safe from Pirates and Terraformers).
- trading stations occasionally eject all goods into space that they are never supposed to trade. These could sometimes end up in their cargohold (its not really a bug but still completely unintended because it also created an indefinite further demand on that trading station. Energy Cells were most affected by this)
- trading stations get destroyed when Xenon conquer the sector. All resources will be lost.


Evolving Factory Layout:
- factions occasionally recycle a factory in their core sectors. This stimulates the stock Mayhem 3 station construction routine and allows them to build something else that they maybe need more (but it could also be the same type of factory again)
- this makes them slightly less reliant on war and destruction because they can get free up station support slots even if nobody blows their factories up. Previously the economy could clog up in certain peaceful areas of the galaxy because of a lack of free station support slots and unable to change anything.
- for the most part this recycling process is random, but if the galaxy really needs the product of a factory it won't get recycled.
- recycling mining stations will always return the asteroid back to the sector


Optimized ship component production:
- previously the AI would only check what resources their current factories would need to keep running and then build those required lower tier factories if possible. Once these needs were satisfied they would just pick additional factories from a pretty arbitrary list. This always completely ignored the most important consumer -> Outposts which need a fairly balanced stock of all 3 ship components to produce the ships which keep everything going. And it always lead to huge resource imbalances across the entire galaxy. For example Ore was always in oversupply and C-Rations were always short. Freighters started to ship more and more useless stuff around and the economy could never reach good efficiency. The game still worked because the NPC ships were so cheap that their resources didn't actually matter much.
- now the AI ship construction is actually limited by their resources reserve. If they have all 3 components they can just crank out ships super quickly. And the AI generally knows how important those 3 resources are, so they carefully try to avoid shortages. When they can't produce more ships because they need more Hull Plating they will now actually build more Hull Plating productions (crazy right?)
- for this purpose the AI can recycle factories which are unnecessary at this moment and which will free up station support slots for the more important factories
- the AI also knows if it could buy any intermediate resources from trading stations and is able to decide against building those factories in order to save a lot of station support slots. This will get way more ship part factories going for them and they can crank out more ships overall. Only the weaker factions can act smart like this (they are essentially trying to MinMax their component stockpile)
- the vanilla Mayhem 3 station construction routine for the NPCs will not build any more factories for the 1 intermediate product which is already the most common in the entire galaxy.
- then the AI can specifically decide to source certain external resources from trading stations (see under AI details). Those factions will not build any more factories for the top 3 most available intermediate products in the galaxy. They will just buy those externally. For the NPCs this is always extremely efficient and smart because they are not actually limited by money.


Outposts:
- reduced default production specialization limit from 50% to 20% for NPCs and the player (crafting is just more resource intensive)
- all Outpost crafting is 4 times faster. This might seem extreme but its necessary for various reasons. New ships can roll out quickly as long as resources are still available. The AI knows how many resources it has left and tries to prevent excessive ship losses when it starts to run low.
- crafting speed scales much more on higher specialization levels
- advanced engineering perk increases build times by 600% instead of 150%
- improved the way how the AI orders ship reinforcements. They can order them in larger batches and will spread the various construction requests and replacement classes over multiple nearby Outposts. Mayhem 3.15 already improved this a bit, but my new method seems to work even better


Crafting Efficiency Booster:

- this allows weak factions to actually swing around and pull a comeback off for real. It dynamically adjusts their Outpost crafting efficiency based on actual gameplay situation.
- it introduces soft economic 'rubberbanding' between factions to prevent that they fall apart too quickly. Basically a cheat, but you can also think of it as nations who live at tough conditions will start working harder
- weak factions just build their ships more efficient (faster & with less resources)
- Player Outposts always just level up like usual. (learning by doing)

Modifiers:
- highly customizable with 19 t-file settings
- all modifiers get applied gradually and equally on all NPC Outposts of each faction. Different modifiers can stack
- the final production specialization with all modifiers combined must remain between 0% and 90%.
- the new baseline for an average faction is 20%. With default settings it will go up to about 60%-70% for a very beat up faction. The player can only reach 20% +10% terraforming bonus.

1) general catch up intensity multiplier (can tone the entire effect up or down or disable it with 0)
2) large empire nerf limit (default 15 spec points)
3) large empire sensitivity: how much % of average main faction territory is needed to get max nerf (default 200%)
4) strong empires nerf limit (default 10 spec points)
5) strong empire sensitivity: how much % of average main faction military power is needed to get max nerf (default 200%)
6) small empire buff limit (default 15 spec points)
7) small empire buff sensitivity: how little % of average main faction territory is needed to get max buff (default 30%)
8) weak empire buff limit (default 10 spec points)
9) weak empire sensitivity: how little % of average main faction military power is needed to get max buff (default 30%)
10) Xenon buff limit: extra spec points that every main faction gets based on Xenon territory vs. the territory of all main factions combined (default 15 spec points)
11) Xenon sensitivity: how much % of Xenon territory is needed to give max buff (default 30%)
12) OCV buff limit: extra spec that every main faction gets based on OCV fleet power vs. the power of all main factions combined (default 30 spec points)
13) OCV sensitivity: how much % of OCV power is needed to give max buff (default 80%)
14-19) additional racial settings to boost/nerf spec points of a specific empire (all disabled on default)



Non-aggression pacts:
- factions who think they have some sort of problem will agree to peace and sign treaties with each other
- technically this is just a standard Truce, but it gets constantly refreshed as long as both partners are still having their invdividual problems and therefore are still willing to keep the peace.
- these non aggression pacts are also available to the player in the ministry of war, but for you they work a tiny bit different. The player doesn't really need a separate  treaty because even just neutral empires can never attack you anyway
- so for the player this only works as an instant full reputation repair (from the AI's perspective its basically an infinite truce with the player)
- but in return the other empire will also want a temporary protection against YOU.
- the duration of a non-aggression pact with the player is based on territory size difference and can last between 12-72 ingame hours. Smaller nations want a longer protection against your future aggression.
- any betrayal by the player will slowly be forgotten, but this often takes very long. You can still always repair your reputation the usual way by killing Xenon for them, etc.
- if you honor your promise (to not attack them again) all the way to the end you will get a favor point if your empire was bigger than theirs
- because of the new infamy penalty you can no longer break a truce by accident after damaging an NPC ship. Only when you fully destroy it.
- breaking a truce by destroying a station does no longer cost you additional reputation with all other factions
- during Terracorp's global alliance you get forced into automatically truces with everyone. Breaking one of those has very severe consequences. You gain lots of infamy (no further truces possible) and there is a 50/50 chance for each faction to start a war against you after the Xenon crisis event is over.


Infamy
- the player can do evil things and become known as a criminal/rogue nation. This is just meant to be an alternative way to play Mayhem 3.
- as long as you don't have any infamy you are considered honorable. Even just 1 point of infamy will immediately give you most of the bad effects, but they are not too severe
- infamy slowly decays over time, faster if you have more (t-file settings)
- infamy has certain benefits and they usually get better with more infamy.
- you can only sign truces if you are honrorable. This includes the standard truce from stock Mayhem 3 which you would always get offered after loosing a sector. And also the new non-aggression pacts that you can now actively propose in the ministry of war.
- you can only buy sectors or activate diplomatic favor actions if you are honorable
- the neutral Traders in the galaxy are organized in a Trade Union. This organization bribes you with money so that you let them live. You'll get frequent payments as long as you stay honorable.
- during the global Xenon Crisis when the United Commonwealth starts to steamroll the Xenon there will be lots of conquered sectors to hand out to random member states. If you are honorable you will be included in this lottery and can gain entire sectors for free.
- infamy slightly increases the risk that a superpower with 'Tyrant' AI personality decides to punish you with dedicated anti-player strategies (those will smart select one of your most important Outposts and then send overkill invasion fleets even at long range)
- if you have infamy all pirates will be much less likely to attack you. Their TM raid carriers will not perform any hot-drops in your sectors and you get a decent chance that a loner pirate or gang leader moves away from your sectors and also any sectors where your freighters are flying around. This benefit will cap out at 80 infamy and it can never fully protect you like the Pirate Contract perk. But having more infamy improves the protection.
- infamy also increases the yield of the spaceweed Outpost perk by 50%. This bonus doubles if you have more than 50 infamy and triples at 100 infamy.
- depending on your infamy the Nomads might send traders to buy your spaceweed. It boosts their ship production.
- you gain infamy if you break your truce (non-aggression pact) before it times out.
- it also increases massively if you violate the global peace during a Xenon Crisis
- you gain 1 infamy for destroying a neutral trader. This doesn't have any other penalties anymore! Your relations with companies, nomads and freelancers are fixed at neutral. Nobody will protect them.
- but neutral traders will start to hire bodyguards if you harass them too much
- when a Xenon Crisis ends there will be a general amnesty and 90% of your infamy gets cleared for free. So you could start the game as a pirate with fully automated fleets to hunt innocent freighters and automated Looters to get their resources for your war machine, but a few days later after the amnesty you could switch and become mr. nice guy who will earn lots of bribe money from the Trade Union because of his suddenly powerful military fleet.


Refugee Ships
- lucky survivors of a station which got destroyed by the Terraformers. They have a TP which is cloaked & protected against the Pirates/Xenon (like neutral traders). The more Terraformer chaos in the galaxy, the more refugees tend to exist.
- in the end all refugees will join the new Nomad faction on their flagship. They are the 'Nomad resource' if you will.
- the TP always carries a random ware that it could save from the destroyed station and the Refugees want to sell it at a trading station.
- but first they head off to a random Outpost to drop off a few passengers and join the local population
- refugees will not come to your Outposts if you have infamy. This extra influx of people allows you to exceed your standard sector population limit by up to double.
- once you're above your natural limit your pop growth will stagnate. All these extra people will still get consumed if you produce any ships in this Outpost. If you don't build ships and no deadly desease or famine wipes them out, then you can profit from a permanently increased population (higher taxes and waste generation).
- should you actually desire the benefits of having infamy you can hunt down refugee ships



Nomad Faction
- specialized on intergalactic migration (they call it their "Eternal Journey"). Nomads have access to exotic tech like Maelstrom navigation, OCV cloaking, advanced construction methods and cargo compression. They follow the Terraformers into other galaxies and recruit from the constant stream of refugees that gets left behind in the chaos. Only the higher ranking Nomads have actually been to other galaxies. They live pretty comfy inside the Nomad Flagship. New refugee arrivals from the local galaxy usually become their slaves & cannon fodder. The deal is very simple: Give us everything you have left, including your family to work in our grease pits and we'll have them build a new ship for you, so you can earn money and pay off your debt to us.
- similar to neutral freelancers and companies, Nomads don't have a reputation system. You can attack one of them and the rest won't care. But attacking their non-military targets will cause infamy.
- the Nomad Flagship (Aran) has an internal ship factory and produces Nomad ships on the fly.
- these are given to refugee arrivals who get sent back into the galaxy to be productive.
- the Nomad economy works a bit simplified and is not fully simulated, but their ship construction is still somewhat limited by the amount of refugees they get.
- most Nomad ships migrate far across the entire galaxy. On each trip they must visit a different faction and they also have to fly at a minimum jump distance.
- you can wipe the entire Nomad faction out by killing their flagship which builds all their stuff, but there is no reward for this and it will respawn after a few hours. (i might do more with them in the future)
- a secondary job of the Nomad flagship is to declutter any container overflow in the universe. Sometimes thousands of loot crates can end up floating in certain Xenon sectors and the faction Looters cannot go there due to Blacklist. The Nomad flagship can pick these wares up and will feed any resources back into the economy cycle. All non-resources get recycled and converted into tiny bits of their special 'nomad resource'. You can tweak or disable this clean-up looting behavior of the Nomad flagship in the t-file setting.


Recycler Ships & Traders:
- the Nomad flagship builds other mobile factory ships (TL) and traders (TS) to supply them with resources
- Recycler TLs are basically a flexible factory reserve for the galactic economy. They have very low speed speed but high-tech cargo compression and efficient production modules
- their internal factory actually consumes the required lower tier resources and works just like the player's mobile factory TLs, only much more advanced. Compared to the player Nomad TLs produce 8 times faster at 45% less resource cost (with default settings 1 Nomad TL Recycler produces as much as 4 standard factories, but at 110% resource cost)
- recyclers cannot craft any high end ship parts. They focus on producing intermediate resources which are in high demand in the galaxy. Once they have selected their product they have to stick with it for a while and will only produce that. After a few hours they check if something else is in higher demand.
- Nomad TS traders will pick up nearby opportunities to buy what the recyclers need or sell what they have produced. Their trade range is rather short so that they can catch up with their TL again. They prefer to buy in large quantity from trading stations and for that they won't use Mayhem's trade lock system. This means that multiple Nomad traders can buy from the same trading station at the same time, also without blocking any trades for other traders.
- there is no way to actively trade with the Nomads, but they can trade with you (maybe even buy your Waste or Energy Cells).
- you can attack Nomad TL recyclers or TS traders. This only causes an infamy penalty. So maybe go and hunt one of them down when it's travelling through an area that your Outpost Looter Workers can reach! Recyclers often carry lots of resource loot, but they might also have a small escort
- since Nomad recyclers are so wasteful they sometimes drop a loot crate and won't care to pick it up again


Nomad Mercs:
- these are the former refugees who accepted huge debt and sold out their families to receive new ships from the Nomad Flagship
- they're different from standard mercenaries. More desperate, angry face, powerful and cheap. But also less disciplined and unreliable.
- they come in larger groups than standard mercs and can even field M7 frigates
- all merc costs are 50% lower, but there is the risk that they run away pretty quickly (and steal most of your upfront hiring fee)
- these poor guys don't have the kind of connections that you need to smuggle illegal goods like standard mercs do. They just travel long distances on the galaxy map to visit different factions in search of work.
- there is no top limit for the amount of Nomad mercs which can exist in the entire galaxy (like there is for standard mercs). More refugees just leads to more Nomad mercs.
- but the more Nomad mercs exist, the greater the risk that they might decide to attack the core sectors of the Xenon Empire on their own. This will be foolish and should always fail. But blinded by revenge they simply couldn't help themselves. They will break their current merc contracts for this.
- there is always a chance that Nomad mercs just decide to leave or even go completely rogue and turn into a pirate gang! This also happens to other NPC empires who hire them.
- having infamy makes them fear you somewhat. And they will be less likely to just randomly leave. Having at least 1 point of infamy also completely prevents that they can betray you and turn into pirates (the base chance for this usually increases when more Nomad mercs exist in the galaxy)
- Nomad mercs excel in the more short term contracts. When you just want to make good use of some extra firepower to defeat only a single hostile fleet, stop an OCV advance or take out some pirate base. For any longer term contracts they could be too unreliable.
- but during the Xenon Crisis these guys are going up against their preferred enemy which makes them completely dependable. But most Nomad mercs immediately get hired by the UNC and you'd need to double on their pay to hire them for yourself.




Faction AI Details
(includes Spoilers & Tech Babble):

- the vast majority of AI features only concern strategic considerations. Things like which factories to build, blacklisting sectors, getting extra squadrons, making peace with other empires, hiring mercs, etc. The tactical AI during in sector battles is still pretty much stock Mayhem 3 with only a few changes (except fighters which behave completely different)
- the NPC empires only analyze the global situation about every 8 hours. So it might take some time before they react. Economic adjustments can take even longer than that. Also don't expect any super smart AI which plays better than you. This is still just good old X3.
- gathering the global data and deciding what to do with it happens completely in the background. It takes about 15 min to complete, but during full SETA also up to 1 ingame hour! Which is not ideal but it should still be fine. This process doesn't need to be fast and doing it more slowly should prevent any performance hogs.
- there is a dev-mode t-file option which will activate certain stats and testing options in the ministry of war and special debug messages and reports. The typical end user should never need it.


Lets get some often used terms straight:

'Additional Squadron'
- overall the factions have fewer starting fleets
- the AI can build extra ships beyond stock Mayhem 3 limitations. But this always has certain requirements like having a certain amount of resources stockpiled or all other squadrons of that same type already need to be built up to decent strength. 
- these extra ships beyond the vanilla limit will not get replaced automatically. Once destroyed the AI needs to meet the requirements to build additional squadrons again. Otherwise they only rebuild up to the vanilla Mayhem limit (which is 100% based on territory size)
- building additional squadrons of a certain type (Battlegroup, Police, etc.) always has its own individual cause why the AI wants it and it also has an individual top limit attached to it. This defines how far this specific cause allows the AI to exceed the vanilla limit. For example an AI in panic mode will use its Battlegroups for defense and also tries to slowly build more so that it eventually has a powerful offensive punch to expand again. This desire to build more Battlegroups because you want to prepare a counterattack is different from the desire to build the same but because you are simply rich and can afford it.
- of course all these different desires have their own final limit to prevent asset overflow in the universe.

'Average Power Comparison'
- military power ranking. Relevant for most AI decisions.
- total military strength of a faction divided by total strength of all main factions, divided by the number of main factions   x 100%

'Average Territory Comparison'
- ranking for the amount of sectors owned. Relevant for the AI, but mostly to determine their 'overextension'
- total amount of sectors owned by a faction divided by total amount of sectors of all main factions, divided by the number of main factions   x 100%

'Bottleneck Sector'
- any sector with exactly 2 jumpgates which must be opposite to each other (North/South or East/West)
- NPCs are aware that the most important traffic routes (on the galaxy map) often have to pass through these sectors.

'Coordinated Invasion' (CI)
- major fleet operation which tries to capture a very specific sector at all cost.
- this special invasion strategy is smarter and not random like usual

'Enclave'
- isolated faction sector
- the opposite from this are cluster sectors. Those are sectors which are adjacent to at least 1 other sector of the same faction.
- Enclaves are often difficult or dangerous to defend and pretty inefficient to own, at least for weak factions, especially if the sector is very far away from their main clusters. The AI knows all of this and gives these sectors up if need be (without abandoning them completely)

'Exodus'
- long term survival strategy
- factions which are very close to the OCV portal might declare an Exodus to try get away from there. Its basically a slow migration
- the only public AI reaction. You will be notified
- the AI has two major goals with this strategy 1) conquering new living space further away from the OCV portal 2) conserving its valuable offensive forces (Battlegroups) and not waste them against the endless machine onslaught

'Freighter Losses'
- a warning sign for the AI about the pressure on its economic foundation
- every 8h the freighter population gets saved for each faction
- the game keeps track of all freighter kills
- the kills from last cycle get compared with the freighter population at the beginning of that cycle
- kills vs. starting population = 'Freighter Losses' in percent
Example:
8h ago the Boron owned 56 freighters. Now they own 62 and they lost 12.
12 / 56 = 21% freighter losses
- if there is an unusual spike in losses the AI has a few options to try fix it. But this usually requires that they already suffered for quite some time. All countermeasures have a delay.

'Main Faction'
- Argon, Boron, Split, Paranid, Teladi, Yaki, Player
- excludes anyone who doesn't own at least 1 sector (not existing or dead factions, like the Yaki before their revolution and the Player before his Ascension)

'OCV Power'
- combined military strength of all roaming OCV invaders (not portal defenders), divided by the total strength of all main factions   x 100%

'Overextension'
- another signal/warning for the AI that tells them if they have sufficient military
- the military population in this mod can fluctuate much more than in base Mayhem 3. The amount of squadrons that the AI wants to build is no longer based only on territory size, but also on their current strategy. And to a very large degree that strategy also depends on their military power.
- whenever major battles are lost or many new sectors are gained too quickly, a faction can quickly get into 'overextension' because their military is suddenly considered too small and not sufficient to cover their large territory size anymore. This will make them become less aggressive and try to consolidate.
- having negative overextension usually (not always) means to have more military power than what base vanilla Mayhem would've allowed to build. Negative overextension is used to tell the AI that it has successfully militarized and that it is ready to be more aggressive again after certain problems had previously  forced it to take a defensive posture
- the AI of the strongest main faction doesn't care about being overextended. 
- the basic formula is: our territory size relative to others minus our military strength relative to others
Example:
The Argon own 26 sectors which is 167% compared to the average territory size of all other main factions. They have a total military power of 142% compared to others.
167% territory - 142% military = 25% overextension

'Pirate Density'
- each faction has a certain amount of pirates that they always tolerate without any problem
- this takes the maximum allowed galaxy pirate limit and checks how many of them would need to be expected inside the territory of that faction, assuming that the pirates were perfectly distributed across the galaxy. The factions want to have no more than 1/3 of that theoretical amount of pirates.
- Pirate Density is actual pirates in their sectors vs. desired pirates x 100%
- so if many pirates exist overall or if they mostly concentrate only on a few factions those NPCs will think that they got a pirate problem

Raiding:
- NPCs usually leave freighters alone because they are innocent civilians
- that means you can send your traders safely into enemy territory, to cross it or get to a trading station! Just don't give them any military escorts.
- but the AI can decide that it wants to commit war crimes and starts hunting freighters with special raids
- a raid is an operation exclusively for Task Force squadrons only.

'Resource Level'
- signals the AI if it is poor or rich
- checks the average credit value of the 3 main ship crafting resouces (Computers, Hull Parts, Quantum Tubes) that a faction has stored across all its Outposts
- if each of the 3 ware stockpiles is still worth over 45 million the faction is considered to be 'rich' and can afford to use more wasteful strategies. Above 12 million is 'medium' and only above 3 million is 'poor'. Anything below that is 'starving'.
- the AI takes its current Outpost specialization bonus into account and reduces those requirements accordingly

'Secondary Threat'
- some enemies like Xenon or Khaak don't publicly claim sectors. In vanilla Mayhem 3 these enemies were often ignored by most defense fleets and constant ship losses could bleed a faction out from the inside
- Zero Hour fixes this by making the AI aware of the enemies which operate outside of the primary faction war. If those enemies become a major issue the heavy defense fleets will stop being blind about them, and will now rather go blind against the main faction war. Their priorities get reversed (temporarily)
- this only scans for enemies in sectors which have issued a combat alert, but which are specifically NOT claimed by an empire (secondary threat sectors). The defense of properly claimed sectors is already handled very well on default.
- these secondary enemies are often Xenon, OCV, Khaak, Pirates or sometimes the Player.
- the combined enemy military power just in those not claimed sectors is the 'secondary threat' which gets compared with the faction's own military score

'Secondary Threat Average Ship Strength'
- this tells the AI if the ships of the secondary threat are only small in size, or if there are also powerful capships roaming around
- against weaker enemies like pirates its enough to continue sending smaller squadrons like the police
- but against OCV capships or Khaak queens the police would only die all the time, so then its required to call in the heavy cavalry. The AI might also temporarily blacklist that sector for all its weaker squadrons

'Secondary Threat Sector'
- any sector with a HOT combat alert on the galaxy map,  but no claim of a main faction

Strongest faction:
- simply the main faction with the most military power
- it generally cares a lot less about being threatened or running out of resources and will overall use less of the more defensive strategy adjustments
- once the player is the most powerful there is no 'strongest faction' anymore

UNC:
- UNited Commonwealth
- Argon, Boron, Paranid, Split, Teladi, Yaki and the Player
- all factions allied. NPCs share resources with each other
- all total wars temporarily supressed
- created and dissolved only by authority of Terracorp
- needs to blockade the OCV portal to defeat the Xenon Empire
- takes control of all NPC member state defense fleets and reforms them into joint operation fleetstacks. When they conquer a Xenon sector they transfer control to a random UNC member faction
- all NPC members retain control over their national offensive forces (Battlegroups)








Full List of AI Reactions:

Superpower Personality:
- exclusively available to the strongest faction only
- they must first get a significant power advantage against everyone else and also must not fear the Terraformers yet (no desire for a global coalition)
- the 'Galactic Protector' AI goes much easier on the main factions and focusses on fighting the Terraformers. But he wants to do this by himself like a good daddy
- the 'Tyrant' AI is focussed on projecting power and wants to hurt other empires, even if that would be bad for himself or stupid. What he does not actively desire is to wipe other factions out. It can still happen though.
- when a faction could grow super powerful it will eventually develop one of the 2 personality types (good vs. evil). This will be a permanent decision as long as the faction remains the most powerful in the galaxy. If their strength falls behind too much they will loose the personality again (and could later get the other one!)
- different races lean more towards good or evil ethics. Borons are more likely to become a Galactic Protector, Split often become Tyrant, etc. Each race has a t-file setting where you can change their general ethos preference.
- the Tyrant AI is usually most likely to emerge when a Split empire completely dominates the galaxy and also has some decent distance to the OCV portal


Galactic Protector Strategy:
- immediately dissolves all his total wars (but not any permanent war against the player)
- you cannot use the 'Xenon report' or 'Chaos' favor action on him
- he generally offers truces to other factions and also accepts a hostile player's offers for a non-aggression pact  (strong empires usually don't do that) but he always demands the maximum protection duration from the player (3 days) so that you cannot exploit his generosity too much
- his Battlegroups are generally less likely to invade other main factions and will focus more on the Xenon
- invasions against the Xenon have unlimited range
- sometimes he retreats his Battlegroups to built them up to full strength
- full strength Battlegroups usually get used to hunt down large Terraformer hosts across the entire galaxy or to invade a Xenon sector. Only very rarely he attacks another empire with them.


Tyrant Strategy:
- immediately dissolves all his unbreakable alliances (guess they aren't unbreakable anymore, lol)
- you cannot use any favor actions on him
- he raids the freighters of all his enemies (not just his total war enemies)
- can use special coordinated invasions which know where your most important sectors are and uses overkill force to take 1 of them away, even at long range.


Stance:
- there are 5 different basic strategies which determine a faction's general orientation regarding offense vs. defense
- only 1 can be active at a time
- stance has the biggest impact on overall behavior of the faction and all its squadrons

Neutral:
- this is probably closest to vanilla Mayhem 3
- neutral AI generally doesn't use any CIs and invades mostly randomly like before
- when resource starved they optimize their ship component industry, but without sourcing external resources

Full Defense:
- Panic mode. The faction thinks that it is dying.
- tries to avoid any unnecessary ship losses
- isolates itself to grind for additional squadrons (being more or less successful with this depending on how much the catch up mechanic already helps their production. Usually a lot unless you tone it down in the t-file)
- always optimizes own ship component industry, also sourcing external resources
- squadrons don't switch homebase to enclave sectors anymore (the faction essentially gives these sectors up)
- going into this stance locks it permanently. The chance to leave again is based on negative overextension every 6h (they can only stop being defensive once they have built up their military)

When to use:
- resource starvation + less than average territory size + some overextension + less than 10 sectors
- well below average territory size or less than 8 sectors + medium overextension
- high overextension + less than average territory size
- very high secondary threat + not the strongest faction + less than average territory size

Cautious Offense:
- the faction knows that it is getting weaker and should probably stop to send more ships into the meatgrinder.
- the AI concentrates its fleets more and stays closer to its borders
- gets access to CIs with the goal of reducing overall ship losses and conquering the best nearby sectors
- fleets will retreat earlier, from less than usual enemy power advantage and they want more power advantage for themselves before deciding to attack
- optimizes own ship component industry if resources are low, also sourcing external resources

When to use:
- resource starvation + not the strongest faction
- low resources + less than high fleet power
- very weak + not rich
- little overextension + a bit below average territory size
- medium overextension + medium resources
- little overextension + low resources
- high overextension
- extreme pirate density + very high freighter losses + at least low secondary threat + not the strongest faction
- medium secondary threat + not the strongest faction


Confident Offense:
- faction believes that it is quite powerful. It begins to increase invasion range (deep strikes) and cares less about its own defense in certain areas
- enables CIs with medium range. Their goal is to capture special target sectors. It cares less if this is actually smart or efficient. It primarily wants to conquer those specific sectors.
- fleets retreat only from stronger than usual enemy power advantage and need less power advantage for themselves before attacking


When to use:
- large faction + medium resources + not too high overextension
- well above average power + medium resources
- strong faction + rich resources
- strongest faction + medium resources
- low secondary threat + low average secondary threat ship strength + medium resources + stronger than average
- coalition/unbreakable alliance member + only slightly below average strength + at least low resources + no more than medium overextension


Reckless Offense:
- faction thinks it already owns the galaxy. Neglects defense and starts to show off more rather than getting things done.
- enables CIs at very long range. The goal is always just to capture a very specific target sector. They want it at all costs and don't care if this is too daring or if committing so many fleets to one operation would reduce their power elsewhere
- fleets retreat only from much stronger than usual enemy power advantage and they will attack same strength enemy fleets
- deep strikes get +1 jump range

When to use:
- strongest faction + rich resources



Squadron Changes:

Battlegroup: 
- primary invader for the territory war. Works almost the same as before but much more efficient and with certain dynamic AI adjustments which were prevously only available as global t-file settings
- the only type of squadron which takes part in Coordinated Invasions
- always ignores the blacklist (they're usually powerful enough to deal with the danger)
- removed the artificial delay between 2 sector claims by the same Battlegroup. Now they don't waste so much time. They will only defend a sector in 2 cases. Either they're currently actually getting reinforcements from the local Outpost, or the faction AI has actively decided to use them for defensive purposes.
- when defending sectors Battlegroups with huge capships will only chase after hostile capships, not big ships, not fighters, not satellites.
- Battlegroups can decide to get reinforcements without first having to suffer heavy combat losses. If the AI is cautious or generally wants more powerful fleets it seeks to create powerful defensive fleet stacks with potentially all 3 main fleets (Battlegroups, Rearguards and Border Patrols) combined, to protect the Battlegroups during buildup
- resource rich factions can build additional Battlegroup squadrons as a resource sink if all their existing squadrons already have decent power

Full Defense AI:
- disables retreat
- doesn't invade and instead forms up with the strongest remaining rearguard squadron to create a single, very powerful defense fleet
- if the strongest rearguard is more than 5 sectors away they just go escort the closest Rearguard instead
- the AI can build up to 4 extra Battlegroups in preparation for leaving full defense mode with potent invasion force for a good counterattack. Can order 2 new squadrons at once (every 6h) and this doesn't require the already existing Battlegroups to be built up so much

Cautious AI:
- can only claim adjacent sectors
- needs to be at full strength before invading

Confident AI: 
- activates deep strike invasions (2 jump range)
- doesn't go to help defend own sectors anymore

Protector AI:
- when at full strength Battlegroups go hunt Terraformer capships in the entire galaxy

During a global Xenon crisis:
- they try to to clear Xenon sectors with unlimited deep strike range
- the fleets can operate deep inside Xenon territory and push ahead very fast. They don't need to return to a safe sector after each invasion
- supported by numerous volunteers and mercenaries
- multiple strong Battlegroups of all factions will blockade the OCV portal using a special type of CI
- they won't go help defend sectors anymore
- all factions can build more Battlegroups even when their resource reserves are low (because everyone shares resources)



Border Patrol:
- response sweepers against medium secondary threat like pirate M6 or small Xenon raids.
- monitors secondary threat sectors first
- if no secondary threat sectors exist (unlikely), then Border Patrols will act like Rearguards
- can now go everywhere, not just border sectors
- uses up to M7 ships (faster than Rearguards) 
- when the AI decides to fight the secondary threat, it sends Border Patrols to escort the closest Rearguards (unlimited range)
- factions start with less Border Patrols, but will build more when the secondary threat is high. If that threat consists of many capships they'll build an additional Rearguard instead.
- the most efficient type of fleet when it comes to locating pirate bases, but still needs a successful sensor check (AI stance dependent)

During global Xenon crisis:
- all Border Patrols will go join the closest OCV hunter group


Rearguard:
- primary defender in the main territory war
- on default they focus on alerted sectors which are also claimed by an hostile empire
- when the strategic AI feels that it has too powerful secondary threats like OCV or Xenon capships and gets eaten up from the inside, then it can dynamically use Rearguards like if they were superheavy Border Patrols. Additionally this gives them much higher operational range and calls nearby Border Patrols for aid and escort. This strategy tends to create effective large defensive fleet stacks, but all those forces have to be pulled away from the main battlefields of the primary faction war and this could cause sector losses.
- Rearguards ignore the blacklist
- can now go everywhere, not just in core sectors
- squadron is much stronger than before. Now they also use large capitals (slow)
- can locate pirate bases, but is pretty bad at this. Requires a difficult sensor check (AI stance dependent)
- reduced overall amount of these squadrons, but factions can build more to counter roaming secondary threat capships.

Full Defense AI:
- disables retreat
- the AI tries to build 1 additional squadron to secure its own survival

OCV Hunter Groups:
- during a Xenon Crisis the strongest Rearguard squadrons across all factions will become leaders for the most powerful fleets that the galaxy has ever seen. They combine many different types of squadrons from multiple species and also include volunteers and mercenaries.
- Hunter Groups search the galaxy for Terraformer capships and take them out
- only a few of the strongest Rearguards can become OCV hunters. All weaker Rearguard squadrons will just join the closest Hunter Group
- these fleets will opportunistically claim Xenon sectors and gift them to a random faction (since its a joint effort).
- the player can also get sectors gifted (!!!) But only if he already owns at least 1 and doesn't have any infamy.
- there is a t-file option whether this could also revive dead or non existing factions (default: yes)
- the Yaki cannot get revived by this and can only get sectors gifted if they already exist


Task Force:
- raiding & joker defense
- this squadron works completely different from before. It can be described as an unpredictable wildcard which tries to stay ahead of major trouble by utilizing intelligence data about enemy fleet movement.
- now they only use fast TMs with docked fighters. Their leader should always be a TM. Please report if you see any Task Force TMs following an M3 leader (unintended)
- factions start the game with a lot less Task Forces (often just 1 squadron). But they can build a few more, especially if they want to raid the economy of other empires. But overall these guys should always be pretty limited in numbers.
- their baseline behavior is defensive. But they go in sectors that other defenders would ignore. HOT alerts on the galaxy map can never distract them.
- they are the most efficient squadron when it comes to detecting and clearing hostile satellites & jump beacons. Much better than the police. NPCs cannot claim sectors if they don't see whats inside, so Task Forces sometimes prevent a new invasion from happening.
- their only offensive task is to avoid most military forces and hunt freighters of a total war enemy (including coalition enemies, or the player when he declared a permanent war)
- when Task Forces search for a good sector to raid they don't need satellite vision to see enemy fleet movement. But they won't know the amount of freighter targets they would find. So they cannot magically home in on the best raiding zones immediately and have to find them first.
- no raid can target claimed or alerted sectors (these tend to have too much military attention)
- before going on a raid the Task Force needs to be at full strength and must have a TM leader
- raids into enemy territory must start by sneaking across a shared border. But once there the Task Force can try to push deeper into enemy core sectors if undisturbed
- raids don't have any of the usual jump range restrictions, but they can only advance 1 sector at a time. The Task Force is not able to continue until it has either decimated a couple of freighters which had cargo, or when they don't have many of those targets left, or if an enemy capship has arrived (and is not just passing through the sector).
- the raiders will only focus on TS which actually carry important resources (scanning their cargo)
- after each freighter kill the raiders will check for hostile military response. They are cowards and don't want to fight against a real opponent. But they also don't want to abort their raid too easily. So they use their speed to skirmish and evade to a different sector. If an enemy capship has arrived they try to avoid flying to the jumpgate behind it and evade in a different direction. But before heading off they also check that they're not getting trapped in the new sector. They want to keep exit options alive and prefer to have multiple jumpgates available. From their intelligence date they also know where the military is and choose their escape route based on all this info.
- if the raiders get trapped or decide that their escape options are not good enough they will perform a last stand and fight to the death
- a raid inside enemy territory is generally over when all adjacent sectors are not suited to continue (too much military presence or no good way to escape)
- when a Task Force commits to a raid they can be difficult to stop. Their TM leader tries to avoid the major battlegrounds and often sneaks up from an unusual angle on the galaxy map. But even if that's not possible he can still break through the frontlines pretty easily because on his way to the raid zone he won't react to any attacks (like a pirate TM raid carrier).
- when aborting a raid inside enemy territory the raiders won't just fly straight to their homebase, because this could be a long journey which would often lead them back through many hostile sectors again. The chances to survive are usually low, so they try to perform a special extraction move. First they will head to any nearby sector outside the enemy territory which is safe enough and afterwards they switch homebase to their closest safe Outpost to get repairs.
- Task Forces will never defend blacklisted sectors of their own faction, but they can raid blacklisted enemy sectors (total war enemies blacklist each other to protect their freighters)

 
During a total/permanent/coalition war:
- raids their total war enemy
- the AI builds up to 4 additional Task Forces (orders 2 new squadrons at once every 8h)

Cautious AI:
- cannot raid at all
- can conquer empty border sectors (to replace Battlegroups which might be unavailable)
- the AI can build up to 2 additional squadrons to defend against raiding. It only does this when it is losing many freighters but the pirate density and the secondary threat are both quite low (that means it is probably getting raided)

Tyrant AI:
- raids all enemies

During global Xenon crisis:
- all Task Forces will go join the closest OCV hunter group


Police:
- these squadrons are bit more varied and slightly weaker (now also using TMs)
- the AI only uses about half the usual amount of Police squadrons on default, but orders more if the pirate density gets too high. This requires to have either some spare resources left or having a serious pirate issue.
- can sometimes detect satellites and jump beacons. This is more successful when their faction is using a more defensive type of AI

Full Defense AI:
- only defends owned sectors, no more patrolling beyond the borders

Cautious AI:
- reduces patrolling range from 3 to 2 jumps

Escort:
- the AI uses only half the usual amount of Escorts but orders more to counter the pirates. This requires nothing else and it can build up to 3 new squadrons at once


Blacklisting:
- blacklisting a sectir stops faction workers from doing jobs in there and smaller military fleets won't try to defend it
- the goal is to prevent excessive ship losses
- this reduces total traffic a lot. Factories will still be able to get at least some resources from neutral traders
- strong fleets like Battlegroups and Rearguards ignore the blacklist and will eventually clear the danger
- blacklisting can work in tandem with safe flight pathing or without it
- each faction resets and then re-applies its own blacklist every 6h during the main AI cycle

Safe flight pathing:
- makes NPC workers and smaller military squadrons like the police also fly around hostile and blacklisted sectors
- can only be used by smaller factions which have some sort of trouble and need such efficiency the most (also for performance reasons).
- safe pathing does not affect squadrons which are lead by huge ships (Battlegroups & Rearguards)
- any faction that owns less than 5 sectors will always start to use safe flight pathing
- otherwise it requires all of the following:
below average territory size or less than 8 sectors
less than 15 sectors
high freighter losses
low resources
cautious offense or fully defensive stance
- once a faction has activated safe pathing it does not want to turn it off. They only stop using it under one of those conditions:
once it would be viable to use the neutral AI stance again
if they manage to own 15 sectors
if they get some decent negative overextension going (having much more military than they need) but also with at least medium resources stockpiled and using at least cautious AI

Outpost trade range:
- gets dynamically adjusted to account for blacklisting and safe pathing
- the local Outpost in a blacklisted sector sets it to 0 so that all workers stay safe and docked
- adjacent Outposts in a cluster will increase it by 4 jumps so that their workers can fly around the blacklisted sector
- if more than one adjacent sector is blacklisted the trade range gets increased by an additional +2
- border sectors always get +1 trade range and small factions also +1 on all Outposts (vanilla Mayhem feature)
- trade range always caps out at 8 jumps max

Blacklisting Enclaves:
- factions can blacklist their own enclave sectors when they are too isolated and not really worth defending or investing anything into. The requirements for this type of blacklisting are pretty low.
- the faction needs to have low resources or be weaker than average. And it needs to use cautious or fully defensive AI 
- then it can start blacklisting the most isolated, furthest away enclaves. They can never exceed 20% of their total territory size. Each sector must also currently have an enemy power rating of at least 1 M6 or a faction claim

Blacklisting cluster sectors:
- clusters are more tricky because blacklisting them is likely to affect workers from adjacent sectors or even block access to certain areas of space. Therefore the requirements for this type of blacklisting are higher and it is generally used less.
- the faction's own sectors need a roaming secondary threat of at least 30% compared to their own power, this secondary threat must have capships and the faction needs to be able to use safe flight pathing (must be one of the smaller factions)
- it starts to blacklist all own secondary threat sectors, up to 20% of its total territory size. The local secondary threat in each sector must have a power of 1 M2 or similar.
- blacklisting cluster sectors will always switch the Rearguard focus on secondary threat sectors to clear the danger and they temporarily ignore the faction war.

Blacklisting Khaak Queens:
- when a Khaak Queen raid appears all factions immediately blacklist that sector. This doesn't have any other requirements
- the goal is to reduce unnecessary ship losses immediately after. Local workers stay docked, other workers don't go to these stations anymore and the police is less likely to play the hero and get killed. It gives heavy squadrons a chance to maybe take the Queen out before it can cause major damage.
- this works independent from the AI main cycle and it will only last until the next update (so anything from a few minutes up to about 6h)
- on its own this does not activate safe flight pathing. Workers and squadrons are free to fly through this sector and the Khaak Queen unless their faction was already using safe pathing before.

Blacklisting entire factions:
- factions can blacklist their total/coalition/permanent war enemies because those would raid and kill their workers. Reckless AI cannot do this unless it has only medium or lower resources left.
- once a faction is using fully defensive AI and its resources are running low it will blacklist all other factions, including neutrals and friends. At this point something obviously went very wrong and in order to survive they'll turtle up as much as possible. But they will only do this if they have at least 1 company trading station in their own territory.



Exodus:
- can only be declared by factions who have their sectors at an average distance to the OCV portal of less than 90% compared to other factions
- the Exodus is basically a very long lasting event (ingame days or even weeks).
- beginning and end of an Exodus are chance based, using the OCV portal distance comparison between factions. The strongest main faction can never do an Exodus and if a faction becomes the strongest during an Exodus it will also end it immediately.
- during Exodus that faction tries to slowly 'migrate' away from the OCV portal. They cease all offensive efforts near the portal and try to expand into the opposite direction
- the Exodus only affects their Battlegroups and it has the following effects on them:
- when they choose invasion targets they prefer sectors which are furthest away from the OCV portal. This doesn't inrease their actual invasion range like deep strikes or anything. So they cannot immediately fly to conquer sectors at the other edge of the galaxy map. But from their available invasion targets they'll choose the furthest away. So in time their territory likely shifts and gets some distance to the OCV portal.
- they can only invade Xenon sectors which are further away from the OCV portal than their own homebase sector.
- they won't turn back to help defend their own sectors against Terraformer capships anymore. Other empires might come to take advantage of this, but it will only put those factions closer to the OCV portal (which is exactly what the faction with the Exodus wants. A buffer zone owned by somebody else inbetween them and the OCV Maelstrom.)
- when a Battlegroup switches homebase it will prefer those Outposts which are further away from the OCV portal (again without increasing the actual max range for this.)


Example:
- the Argon sectors have 87% average distance to the OCV portal, compared to the other factions. That means their sectors are 13% closer
- every 6h the chance that the Argons initiate an Exodus is 100% - 87% = 13%
- during Exodus the Argon Battlegroups will slowly migrate into the more distant Argon sectors and will choose their invasion targets near them
- Lets say the Argons manage to increase their average distance to the OCV portal to 103%, maybe because their sectors close to the Maelstrom are now Xenon
- every 6h they now got a chance to stop the Exodus: 103% - 100% = 3%
- an Exodus always allows Task Forces to conquer empty border sectors like if they were Battlegroups




Coordinated Invasions (CI):
- multiple Battlegroups move close to a target sector but don't invade it immediately. They synchronize their invasion with each other to get an overwhelming numbers advantage. They also often attack from multiple angles (through different jump gates).
- CIs are generally slower than standard invasions, but they will select the sector target in a much smarter way than standard invasions.
- they can also have much longer invasion range
- squadrons which take part in a CI cannot retreat anymore and the sector claim won't expire (its always win or die)
- each faction can only have one CI active at any time
- there are many different types of CIs with different sector targets, invasion ranges and fleet power
- CIs are never used randomly. There is always a certain strategic reason and a specific range of target sectors.
- these operations are mostly used by the weaker AND by the most powerful factions (but both for different reasons). Factions with average strength use neutral AI which invades mostly random like in vanilla Mayhem
- weaker factions tend to use smart CIs which are pretty safe bets at very short range. Their goal is to capture high station support sectors with minimal ship losses to improve their industry.
- the more powerful empires tend to use much more risky CIs with longer range. They mostly want to do impressive or sentimental things which are not too effective from a pure MinMaxing powerplay point of view. But they should bring more variety and flavor into the game.
- just because a faction attempts a CI doesn't mean that they can actually launch it. The different CI types have different requirements regarding the minimum strength of individual fleets, the minimum strength of the entire operation, the jump distance to the target sector and also if the Battlegroups which should take part in the operation are roughly at the same jump distance to the target or not. If the faction cannot muster enough total power, or if the individual fleets are too weak, or too far apart, then the faction just cannot do the CI at this moment. Usually its extremely efficient for the NPCs to concentrate their forces with a CI, but not all the time. For example if they have a fleet 2 jumps away from the target sector and another 20 jumps away, then the first fleet would quickly be in standby position and then needs to wait literally hours before the other fleet arrives. That would be stupid.



Types of Coordinated Invasions:

During a Xenon Crisis:
- everyone can target  Xenon sectors which are directly adjacent to the OCV portal
- the united alliance wants to establish a secure perimeter of sectors around the OCV portal and cut them off from the rest of the galaxy.
- the portal is successfully blockaded if there are no more Xenon sectors adjacent to it. This will reduce the OCV's ship construction speed by half and allow all NPC fleets to go into sectors in general proximity of the portal sector.
- this blockading CI operation wants to achieve a higher than usual total fleet power and it can combine many weaker Battlegroups to create a bigger fleet

Galactic Protector:
- with at least confident AI stance this CI will target Xenon sectors at unlimited range
- with neutral stance he needs to stay in relative proximity of his own empre (thats when he starts to run out of resources)
- the long range variant can only recruit strong Battlegroups
- the entire operation tries to have high power


Tyrant:
- wants to troll and humiliate other empires. Therefore it has the smartest target selection and uses overkill forces to capture sectors which are of great importance to their victim.
- Tyrant CIs are not particulary effective to wipe a faction out, because they are so overkill that they bind a lot of Battlegroups, which basically prevents the Tyrant navy from carpet sieging many sectors quickly to finish factions off. It might be spectacular to send half your fleet across the galaxy to teabag someone, but its definitely not efficient.
- all Tyrant CIs can only recruit strong Battlegroups
- the entire operation tries to have very high power
- this concentration of force makes it especially dangerous against the player because they always target one of your more valuable sectors and the galaxy range is also pretty high (but not unlimited)

Tyrant AI can use the following CIs:
1) Steal someone's dejure sector. To mock them and assert dominance
2) Ripping a faction apart:
targeting a sector which is a strategic bottleneck on the galaxy map, with the special twist that both adjacent sectors must also be owned by the same faction. With this strategy the Tyrant tries to fracture a consolidated territory into smaller pieces. Confident or reckless AI does something similar but only because they want to control that traffic bottleneck sector. The Tyrant specifically wants to hurt and split the other empire.
3) Punish Player:
- a Tyrant AI which is actively going after the player is a  difficult situation because you can easily loose a very important sector even deep inside your empire
- but you can only get targeted when you have negative reputation
- when such a dedicated anti-player CI gets launched, then it can be very difficult to defend against it (or not even worth trying)
- at least the Tyrant still offers a truce so you can generally not loose more than this one sector.
- the % chance every 8h for an anti-player CI to get attempted is equal to ### half the amount of player sectors.
Example:
you got 12 sectors and negative reputation with the strongest faction. So they can generally target you. But this has to pass the following:
Every 6h there is always a flat chance that a faction doesn't even attempt any new CI (t-file setting). Then, depending on how much the faction dominates all others, there is always at least 20% chance that none of the 2 special AIs (Tyrant or Galactic Protector) takes over during the next 6h. Then, depending on OCV power, there is up to 70% chance that its the Galactic Protector AI rather than the Tyrant AI which takes over.
Only when all of this fails you can finally end up with a Tyrant AI. And with 12 player sectors you have 12% chance that the he decides to specifically target the player empire. Otherwise he might just target anyone (this could also be you again, but by chance and with less power and probably against a less important sector)
- permanent war with the Tyrant adds +15% chance to target the player empire
- a ###15% of the player's current infamy is also added

High priority player sectors are:
- outposts which have levelled up at least half of their maximum ship or station crafting specialization
- outposts with at least 30.000 Hull Plating on stock
- outposts with at least 3 extra perks from adjacency bonus connections
- sectors with at least 8 solar power plants
- sectors with at least 4 mining stations
- sectors with at least 14 station support or 120 manpower or 90 research
- galaxy map bottleneck sectors inside your territory


Getting targeted by a dedicated anti-player CI repairs all your infamy because all factions will pity you and think that you might've learned your lessons. This allows you to get truces offered again. Also by the Tyrant (but only after losing your sector to him ofc).




CIs of factions who desire peace:
- factions who have internal problems and want peace often try to pull some Battlegroups away from the faction war and be less aggressive to other empires
- they focus on Xenon sectors with decent station support to bolster their economy. These must be adjacent to one of their clusters (not their enclaves)
- they can only do this CI when not already using full defense AI
- this CI can also combine many weak Battlegroups into one big fleet
- not available when the faction perfoms an Exodus

CIs for cautious AI:
- careful factions mostly try to gain valuable industry sectors with minimal losses. They use CIs to perform focussed attacks at short range
- targeting good station support sectors adjacent to one of their clusters.
- also any adjacent enclaves from other factions because those are often poorly defended
- and any sector with a trading station (access to external resources)
- tries to concentrate fleet power more to get a better advantage and to reduce overall losses
- this CI can also combine many weak Battlegroups into one big fleet
- the entire operation tries to have high fleet power

CIs for confident AI:
- this AI doesn't need to be super efficient and can focus on more symbolic victories
- it uses longer range CIs to try and collect its own missing dejure sectors in relative proximity to its empire
- tries to further develop its own enclaves by conquering  sectors adjacent to them, but this must be in relative proximity to their rest of the empire.
- then tries to capture strategic bottleneck sectors but they must also be in relative proximity

CIs for reckless AI:
- very powerful factions try to project their power across the entire galaxy. Their CIs often choose risky sector targets at unlimited range:
- collecting all their missing dejure sectors
- expanding all of their enclave sectors and smaller clusters by conquering sectors adjacent to them
- going for any strategic bottleneck sectors at higher range than other AIs
- reckless CIs can only combine medium to strong Battlegroups. The high range makes them often operate behind enemy lines and they cannot afford to use weak fleets for this.
- the entire operation tries to have a bit higher fleet power




########
########

Switching Rearguard focus away from the faction war:
- medium secondary threat + high average secondary threat ship strength + not the most powerful main faction

Fixing a strategic ship part shortage:
- this has three components. 1) whether the AIs want to optimize their economies at all 2) how many missing ship part factories they can build 3) whether the AI is smart enough to check if they could also source the required intermediate resources from trading stations to save station support slots. A faction that is not smart like this always needs to recycle enough unnecessary factories for the entire product chain. That makes them less efficient with their station support slots and they will crank out fewer of the missing ship part.
- the extra final-tier ship part factories (Computer Plant, Hull Plating facility, etc.) get built instantly (but the AI will actually pay them like usual).
- the missing lower tier factories (Chip Plant, Teladianium Foundry, etc.) can only get built like usual over time, into the station support slots that the AI will free up for this. It just uses the standard Mayhem 3 Station building routine and won't always build exactly those required factories next, but overall it should be good enough.
- the AI can optimize its economy every 8 hours. They can build a certain amount of the missing factories, but checking the requirements for this always uses their Offensive AI Stance from the last AI cycle, so the decision making to optimize can be up to 16 hours delayed. This should be fine since its a more long term project anyway.

When to optimize NPC ship part production:
- neutral AI stance + starving resources -> 1 factory
- cautious offense + low resources -> 1 factory
- cautious offense + starving resources -> 2 factories
- fully defensive + low resources -> 2 factories
- fully defensive + starving resources -> 4 factories
- coalition member + low resources -> 1 factory
- coalition member + starving resources -> 2 factories
- if two requirements are met only the higher factory limit get used
- during a Xenon Crisis there will be no economy optimization at all (because it generally doesn't last long enough and we actually want the galaxy to run out of most resources to feel the impact)


Sourcing resources from trading stations
- only for cautious or fully defensive AI and for members in a coalition
- when optimizing their economy they will only free up as many station support slots as they need for the actual end-tier ship component factories (Computer Plant, Hull Plating factory, etc.). For lower tier factories (Teladianium Foundry, Chemical Lab, etc.) they will only free up a support slot if trading stations cannot supply that product to them.
- they will also try to optimize first in sectors which have a trading station or are adjacent to one, so that the new factories are actually in range to buy the resources -> tip: you will often find the majority of critical ship part industry from weak factions very close to trading stations
- factions which cannot source resources externally always have to free up as many support slots as the entire product chain for that missing ship component requires. This is less efficent and it won't help as much to fix their strategic component shortage. (just to be clear: Factions who cannot source external resources will still buy stuff from trading stations and get visited by neutral traders, etc. They just won't build their economy with trading stations in mind)


Truce Desire:
- factions which feel pressured generally want peace. Likeminded partners will sign truces with each other and constantly refresh them. They also offer a truce to the player in the ministry of war
- after a Xenon Crisis there will be a long period where factions want peace much more unless they have many resources stockpiled
- as a secondary effect when the AI wants peace it is much less likely to start any new invasions. This also affects them during Total or Permanent Wars, but not when they are invading a shared enemy during a Coalition war.

Alternative Requirements:
- fully defensive AI stance
- being in a coalition
- resource starvation + below average fleet power
- very weak fleet power + low resources
- a bit of overextension + well below average territory size or less than 7 sectors
- high overextension + below average territory size
- medium overextension + low resources
- extreme overextension
- extreme pirate density + very high freighter losses + some secondary threat
- very high secondary threat
- first day after a Xenon Crisis + no more than medium resources stockpiled
- second day after a Xenon Crisis + no more than low resources stockpiled


Hiring Mercenaries:
- weaker factions can recruit mercs like a player.
- the AI always recruits them permanently for their Battlegroups but the player can still hire them away for double upfront cost. The AI cannot hire your mercs away.
- AI merc recruiting requires a dice roll and has an 8 hour cooldown
- NPCs can only recruit mercs in their own sectors
- chance to hire is 100 minus average faction power comparison (example: Argon have 73% fleet strength compared to the others. > 27% chance to hire mercs every 8h)
- fully defensive AI gets its chance doubled (usually an almost guaranteed attempt)
- neutral AI can hire up to 2 merc squads every 8h, cautious AI up to 5 and fully defensive AI can hire all available mercs
- ###testing! the merc contract will end when the NPC client ship dies (but its often a huge capship Battlegroup leader)
- at the beginning of a Xenon Crisis all factions will hire all available mercs and use them for their joint-operation OCV hunter fleets

Ring of Fire Perk:
- the AI can activate the Lasertower perk on its Outposts
- this requires the same dice roll as merc recruiting
- but it also requires having a free perk slot. The NPCs already use all default 3 slots, so for this purpose it is assumed that the AI can always unlock the Adjacency Bonus Connection perk. And if that would give them at least 2 bonus perks from having enough sector connections, then they can unlock it together with the Ring of Fire perk
- cautious AI can only activate it on 1 Outpost every 8h (only with successful dice roll). In this case it must be in a border or bottleneck sector
- fully defensive AI can activate the perk randomly in one third of their Outposts at once (where they have at least 2 adjacencies)
- Ring of Fire is always a one time action. Like the player the AI cannot replace these Lasertowers and would need a completely new Outpost to unlock them again.
- conquering a sector immediately destroys all Lasertowers


Desire for the Anti-Terraformer Coalition:
- each faction manipulates its reports to Terracorp just like the player (downplaying vs. exaggerating the Xenon threat)
- the AI checks the total Terraformer military power which is currently roaming through their sectors
- on average it will tolerate Terraformers up to 50% of its own military fleet strength
- but this baseline tolerance gets further modified based on:
- distance to OCV portal > tolerance gets multiplied twice by the average distance of all their sectors compared to the average of all other main factions (excluding player sectors here)
- relative strength > tolerance gets multiplied once by their own strength vs. the average of all other main factions
- resource level > being low on resources reduces tolerance by 1/5, starvation reduces it by half!
- freighter losses in % > one third gets subtracted from their tolerance
- having the highest military score of all main factions > increases tolerance by 50%
- regardless of actual Xenon progress an AI will also work towards the global Alliance when it seeks peace in general
- the player can override the AI decision with the 'Xenon Report' favor action







Triggers for the Xenon Crisis
- Terracorp has two slightly randomized hidden goals which determine at which point they are planning to start the global alliance in order to save the galaxy. Once either one of those goals gets reached the event will happen no matter what. In this case the faction reports are completely irrelevant. But they can reduce those Terracorp goals. Both goals get reset after a global Xenon crisis event is over.

Xenon trigger: 40-60% of Xenon territory size compared to total main faction size (t-file settings)
OCV trigger: 40-60% of total OCV military power compared to total main faction power (t-file settings)

- faction reports can sway Terracorp to declare the event up to 20% below their originally planned thresholds. There is also a t-file setting for this influence on Terracorp.
- so if Terracorp was planning to trigger Zero Hour at 57% Xenon sectors or 52% OCV power, but all factions including the player want the alliance, then it could already get triggered at 37% Xenon sectors or 32% OCV power)
- the chance for Terracorp to declare Zero Hour prematurely because of such faction votes depends on how much relative faction power is voting for the alliance. As long as the supporters don't have the absolute voting majority (more than 50%) Terracorp is much less likely to care at all about voting.
Example 1:
40% of all main faction power is voting pro alliance, gets divided by 25 = 1,6% alliance chance (every 6h)
Example 2:
60% of power voting pro alliance, gets divided by 2 = 30% alliance chance
- but this alliance chance gets further reduced based on how far away the Terraformer progress still is from the goals that Terracorp originally planned for the galaxy
Example 3:
Current OCV power is 47%, but Terracorp intended to trigger the alliance only at 52% OCV power. So 5 percent points are still missing to reach the threshold. 5 points is 1/4 of the entire potential 20 point range that the factions can influence with their voting power. So with 60% of all faction power voting pro alliance the previous 30% final chance would get further reduced by 1/4 down to 22,5%


Crisis Effects:
- cancels all active sector claims
- every sector in the galaxy becomes a Terracorp protectorate (except Xenon/Unknown sectors)
- protectorates don't expire during the crisis
- breaking a protectorate (by destroying a station) gets punished with 10 times higher cash penalty and each time every faction has a 1% chance to remember this and declare a permanent war against you when the Xenon crisis is over!
- removes active coalitions
- stops active CIs
- every faction enters one huge alliance with shared resources (temporarily overrides all total wars)
- player's negative reputation with everyone gets repaired for free and you get forced into permanent truces with everyone (temporarily supresses your permanent wars)
- everyone needs much less extra resources stockpiled to be able to start building additional Battlegroups (they still cost the same but small factions benefit from the resource sharing)
- everyone immediately starts the construction of 1 extra Battlegroup
- no squadron can retreat until the crisis ends
- NPCs can claim Xenon sectors unrestricted and with unlimited deep strike range
- Xenon sectors can always be claimed until only the OCV portal sector is left
- the factions start to create massive joint-operation fleet doomstacks and send them into the machine empire
- the most powerful Rearguards will go hunt large OCV/Xenon fleets across the entire galaxy
- all weaker Rearguards and all Task Forces will join these hunter fleets (mixed species fleets)
- all Battlegroups focus on destroying Xenon sectors while the OCV hunters keep their backs safe
- enables a special type of CI to blockade the OCV Maelstrom and prevent more OCV from entering the galaxy
- lots of extra mercenaries appear and immediately get hired by the main factions
- Terracorp covers 75% of all merc costs for everyone! (running upkeep and the single upfront fee). You also don't have to pay double to hire them away from another client anymore
- Terracorp rewards bonus cash for destroying OCV ships
- you cannot activate 'Pacifism', 'Chaos', or 'Federation' diplomatic favor actions



End of a Xenon Crisis:
- the United Commonwealth has to blockade the OCV Maelstrom sector by making sure that all adjacent sectors are not owned by the Xenon. This will reduce the OCVs reinforcement rate by half.
- to win this war UNC forces often have to conquer all Xenon sectors in the galaxy (except the portal sector)
- but there is a minimal chance to end the Crisis prematurely if the Xenon territory size and the Terraformer fleet power have both dropped below 1/3 of Terracorp's originally desired thresholds
- once both Terraformer progress parameters have dropped below 1/6 of the original Terracorp goals this chance will be much higher (but overall it's still pretty unlikely).

After a Crisis:
- immediately after it's over Terracorp will choose their secret Terraformer goals for the next cycle
- all faction relations get reset back to their original status (how you had set them in the Galaxy Generator)
- reactivates the player's permanent wars
- signs 1 additional standard truce where possible so that everyone can get his fleets safely back home before the main faction war can continue
- refreshes all protectorates one last time. They all expire a couple hours later
- in my testing games the entire Crisis event usually lasted about 1 ingame day. Afterwards the old Xenon corner of the galaxy is under proper faction control again, but this area will be patchy and mixed. You got many small clusters, isolated enclave sectors, dejure sectors with the wrong owner, some unintentional player sectors sprinkled in (which the OCV hunter groups conquered for you). Its a very interesting setup for future conflict.
- but the galaxy will be pretty burned out. Nobody really has any resources left because they all shared them during the Crisis. The AI knows this and the time all factions fought together makes everyone a lot more friendly to each other. At least for a while. ###Of course any Total War enemies have to immediately start fighting again but everyone else usually stays in this global truce for a long time to rebuild the galaxy. Not because they must, but because they want.
###- the Terraformers are crippled and will build their ships much slower.### Xenon!
###- how long this generally peaceful phase after a Xenon Crisis will last can be controlled with a t-file option. The default setting is 6 AI cycles (2 ingame days). During the first day the AI will always be willing to sign peace with others unless it has rich resource level (which is probably impossible at this point). During the second day their resource level can already be medium to be able to start fighting again. During the third day the faction wars will be in full swing.



Customization:
- mod has a separate t-file '9973-L044'  with many new settings!!! Want to make OCV progress slower? The galaxy to unite against them sooner? Give some faction a bonus during your active savegame? All covered!
- also makes necessary changes to the base Mayhem t-file ('9972-L044').Some of them might seem strange at first. Like the much lower Outpost specialization maximum or the vastly different NPC fleet ratios. But please trust me at least with the changes to production and squadron ratios.
		<t id="200">25</t> <!-- General crafting time cost multiplier, for lasers, missiles, shields, stations and ships. (Zero Hour default: 25 base default: 100) -->
		<t id="142">20</t> <!-- Maximum specialization level. (Zero Hour default: 20 base default: 50) -->
		<t id="145">5</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Battle Group. (Zero Hour default: 5 base default: 4) -->
		<t id="146">7</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Border Patrol. (Zero Hour default: 7 base default: 4) -->
		<t id="147">6</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Rearguard. (Zero Hour default: 6 base default: 4) -->
		<t id="148">20</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Task Force. (Zero Hour default: 20 base default: 4) -->
		<t id="149">5</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Police. (Zero Hour default: 5 base default: 2) -->
		<t id="150">3</t> <!-- Fleet ratio per X sectors owned (negative is per sector) - Escort. (Zero Hour default: 3 base default: 1) -->
		<t id="286">0</t> <!-- Claim minimum delay between two claims by the same battle group, in seconds. (Zero Hour default: 0 base default: 14400) -->
		<t id="229">1</t> <!-- Additional combat manoeuvres for all fighters. (Zero Hour default: 1 base default: 0) -->
		<t id="282">10</t> <!-- Extra waiting time between turret firing for Huge Ships. The only purpose of this setting is to increase performance. (Zero Hour default: 10 base default: 0) -->
		<t id="283">0</t> <!-- Number of sectors UNDER which an empire will only build half of the ships they need in each squadron. The amount of squadrons is not modified. 0 to deactivate (Zero Hour default: 0 base default: 7) -->
		<t id="252">50</t> <!-- Starting resource multiplier, for all AI Outposts, in percent. Only affects default Outposts spawned during galaxy generation. (Zero Hour default: 50 default: 100) -->
