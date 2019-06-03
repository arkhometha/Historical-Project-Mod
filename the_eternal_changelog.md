# The Eternal Changelog

This file is not for the faint of heart. It details every single change ever made to the mod. It's likely full of typos and mistakes.

***

## v0.4.4 - 17/05/2019

* Electric Arc Furnace will unlock in 1905.
* Congo Conference decision population requirement reduced from 1M to 800k.
* Made the Neutrality modifier for Switzerland not reduce militancy as much as it did.
* (Mostly AI Behaviour): Reduced AI Aggression Base back to vanilla levels (Aggression vs uncivs is still slightly higher than vanilla). Increased AI priority for bureaucrats and the chance of them investing in pop projects. Base Tax, Tariff and Admin efficiency also move back to the vanilla (20%) level. Reduced the FACTORY_UPGRADE_EMPLOYEE_FACTOR from 75% of 70%. IMMIGRATION_SCALE changed to 0.005 (from 0.008) and PROMOTION_SCALE changed to 0.003 (from 0.004). The problem here was that the AI simply didn't have the money nor knew how to deal with the increased pop promotion speed. They bled pops because they couldn't deal with it. So now this happens more slowly and countries will have more money to deal with it. Reducing aggression is also something necessary - the AI goes crazy near the end of the game, where wars were slowing down, but increasing in scale.
* Increased the amount of money factories save from 1500 to 3000.
* Only AI non-democracies will use the "state of emergency" decision from now on. Players can still use the decision as they wish.
* Changed Limited-Access Roads to unlocked in 1915 instead of 1919, to stop it coinciding with a lot of the Army inventions.
* Faroe Island cores will go away in the late 19th century.
* Added 13 inventions to the Metallurgy tree. Reworked RGO bonuses in the tree so a good part of the bonus come from the inventions. The inventions won't fire if there's unemployment in their respective RGOs. Overall, the bonus to Coal and Iron production the tree gives was increased from 250% to 300% for Iron and 330% to 400% for coal. Most of the inventions and the bulk of the bonus to output are for late-game inventions.
* Added a decision for Canada to accept the Metis, which will also remove Maritime Union, Columbia, Metis and Rupert's Land cores from Canada. Removed the Metis from the generic "native integration" decisions.
* Khiva will not start with Nukus anymore. Slight reshape of Khiva. I need to find better sources on the region and decide on a final set up for the central Asian nations, there's conflicting information to the extent of the khanates.
* Fixed requiring impossible things to build the Suez canal.
* Moved 895 - Mersin to the Adana state so the state is not conquered as a colonial state from Egypt.
* Korea will start the war for independence during the Tonghak rebellion with a CB to get their cores back, if anyone took them. They should also fight the Chinese properly and be released properly if the aggressor are the Chinese.
* Added a decision for fore Korea to claim Tsushima (2589). It can also be used again to rename the island.
* Fixed a bug when organizing the Congo that mistakenly made the organizer also the true owner of the Congo Free State.
* Reduced Muhammad Ali modifier mobilization size by 4%.
* Fixed potential split states in the Middle East and Africa because of (potential) different colonial levels.
* Russia up to the Urals will now be full states instead of colonies, with the exception of the Kazakh territories and the Caucasus.
* The end of the initial caucasian war will now move a few pops to Jordan.
* Merged Mosul and Baghdad states into one, moved a few provinces of the later to the Basra state. Made Damascus the capital of the Eastern Syria state, moved the province to that state.
* Fixed an AI check who would make the AI research iron/coal output techs despite unemployment.
* Pacifism party policy now slightly reduces infamy.
* Restored Aristocrat voting support back to vanilla levels.
* Stopped communists supporting the roll-back of political reforms unless they are in power. They will still support social reforms.
* Monarchies should no longer be able to set the Upper House to "ruling party only". That is reserved for ideological, one-party regimes.
* Changed Moldavia's ruling party at the start to liberal. Change Wallachia's ashkenazi pops there to sephardic. Based on https://www.jstor.org/stable/25104807
* Line of Advantage decision can't be used by a vassal country or if a competing japanese power (Japan for the Shogunate, Shogunate for the Japan) exists.
* Absolute monarchies (with the appointed upper house) now have an option to dissolve the upper house and fill it with either Reactionaries, Liberal or Socialists (if unlocked). These will have consequences, however, and cost prestige, plurality and some stability.
* Fixes to the Brazilian OOB: added a Brazilian navy with 2 man'o'war, 10 frigates, 2 commerce raiders and 2 clipper transports (based on https://en.wikipedia.org/wiki/Imperial_Brazilian_Navy ). Added a starting admiral, changed one admiral that should be a general and removed generals that were too old and left the service soon after the game start, or were too young and likely not in a position of power.
* The "Avanti Italia" decision can't be used without owning the Lombardian cores.
* Fixed a NNM bug where Neutral Countries were dragged into wars through the Shadow of War event.
* The Gadsden Purchase decision/event chain will spread CSA cores to the new provinces if neighbouring provinces on the same state have CSA cores.
* Refusing a good peace deal (the ones that give you militancy and war exhaustion will now give 10 WE instead of 5.
* Increased the requirement to add an wargoal during a war back to the vanilla 7% from the current 5.5%. That is balanced with the new "propaganda" decision.
* Added a "Propaganda Campaign" decision. A country can, at the cost of plurality and money, try to tip the country in favour of its government in the UH or increase the population's jingoism. 
* Slight reshape of Franche-Comté to better follow the Meuse river. Renamed the state to Ardennes and moved Besancon to the Champagne state.
* Canada will start with Immigration Quotas instead of Open Borders.
* Zanzibar should keep its slave states after its freed from Oman.
* Changed the slave pops in Iran from the old african_minor replacement to Kilombero. based on https://en.wikipedia.org/wiki/Afro-Iranians
* Changed Mashriqi pops from Nasaf to Kabala, renamed the province to Samawah.
* Made a strait connecting Sado and Niigata.
* Fixed a missing flag that made the EIC not be integrated at all.
* Removed Turkmenli and Assyrian cores from Raqqah. Assyrian pops were moved north to Hasakah. Converted a good part of the Mashriqi pops to bedouin pops in Raqqah. As-Suwayada in Syria also got 2700 Druze mashriqi pops converted to Bedouin,and a few mashriqi pops in Ma'an in Jordan converted to bedouin.
* Changed the pops in the Caucasus group from using Russian units/leader portraits to arab units/portraits.
* Fixing low pension level being 10% instead of 100%.
* Added Fish to the list of RGOs that can get the local_tractors modifier. Renamed the modifier to "Tractors and Trawlers". Made the aristocrats be the ones who need the money when deciding if the event will fire faster or not.
* Pop issues:
  * Fixed a vanilla bug that made impossible for pops that were not getting their everyday needs to care about the pension reforms, when it should be the contrary.
  * Fixed unrealistic unemployment levels (50% of a state unemployed, with the minimum starting at 10%) needed for pops to care more about unemployment subsides.
* Removed Tea RGO from Corrientes and Misiones, changed the production in the state to Cattle, Tobacco and Tropical wood. Changed Xolotas and Formosa to Cotton. Based on (EL COMERCIO DE LA PROVINCIA DE CORRIENTES DURANTE LA PRIMERA MITAD DEL SIGLO XIX. UN PANORAMA DE SU EVOLUCIÓN http://revistas.unne.edu.ar/index.php/fhn/article/download/3452/3099 and https://www.elterritorio.com.ar/la-economia-misionera-al-inicio-del-territorio-6193972785638980-et
* Added a new fish-rgo output invention.
* Fixed two immigration modifiers having the same name, potentially screwing up a few events/decisions.
* Removed the Zulu cores from random neighbouring provinces and left only one in Thaba Bosiu, where there are Zulu pops. They still won't be able to conquer just that province if Basotho has the rest of the state, but once they are reduced to that province only by the Boers they can take it. Normalized Matabele cores in the region to stop Nguni from assimilating.
* Renaming of a few culture groups.
* Changed the MTTH for the Doctrine of Lapse events back to NNM levels.
* Ha'il should now correctly get cores in Nejd's arab gulf state.
* Hawaii changes: Literacy and pop changes. They got an event representing the declining Hawaiian population, as well as the reformation in a constitutional monarchy and a increase in the yankee population. Hawaii will start with a minimal yankee population representing missionaries and their families, and they will start with Yankee as accepted that they lose (like the Ionian islands lose) as soon as Polynesian is not a majority or they own non-cored provinces. They will also start in the US's sphere of influence, and I fixed a decision that the US could take to buy Hawaii which would never work under previous conditions. Finally, if another power annexes Hawaii and there are still Yankee pops there, the US gets a core on the island. This is mostly based on https://digitalcommons.unl.edu/cgi/viewcontent.cgi?referer=https://www.google.com/&httpsredir=1&article=1035&context=historydiss especially data about literacy and pop distribution (as only 50% were catholics in 1837, the literacy changes were made to reflect that).
* Made the constitutional crisis distribute militancy and consciousness according to who can vote, instead of a generic for-all effect.
* Fixed the vanilla Olympics events so the AI doesn't bankrupt itself with them. Made prestige gain, costs for hosting and relations given/lost even instead of varying because of the year. The events will also give a relation boost to any GP that participates in the Olympics, not just neighbour Olympic countries. The AI will no longer choose to host it or not or to participate or not in 50/50 basis, they will be much more inclined to host/join (except if they hate the host, that gives them a chance of not participating). Fixed a wrong flag that could repeat an event until the country choose to take another option. Changed so countries can join the IOC even during war and made the event more likely for Greece. Took steps to guarantee the first Olympic games is likely to happen.
* Fixed a few nations with the Liberty NV being able to get a NV event not meant for them.
* Fixed a decision for a puppet with a sphere owner that is not their overlord and tries to break free still being applicable to substates in a few situations.
* Increased the MTTH in the Socialism_Fascism events to try and make them less spammy. Made so communism events check pop support for communism instead of socialism.
* Stopped the NNM Oriental Crisis events removing Turkish cores from Adana, except for Antakya, if Turkey lost the crisis.
* The "Drums of War" event should no longer give a CB for countries that already have a CB on the unciv getting the event.
* Changed Qing's starting reform from Land to Bureaucratic. Swapped 1547 - Jian from Tea to Grain. Changed 1283 - Hydebarad from Grain to Silk. Changed 1482 - Fuzhou and 1486 - Tingzhou from Tea to Fish and Grain, respectively. Later they will flip back to tea.
* Slightly increase coffee demand in the middle-class and "urban" pops. Added the "housing" goods as needs for Intellectuals.
* Changed the PDM/NNM RGO change events for provinces with high unemployment to try and check that the new RGO won't end up creating a mass of unemployed (before firing an event to change a high-unemployment RGO to cotton, it will try to check if Cotton isn't a high unemployment good).
* Converted the "Break the Tea Monopoly" decision in an event that will progressively turn provinces to tea in India (if there isn't Tea overproduction). The decision created a huge "punch" in the tea market, knocking out several provinces out of business and creating massive unemployment. A more gradual change is more realistic and should avoid that problem.
* Blockades should now slightly affect province output.
* During the Pacific War, the GP that spheres either Chile or its adversaries can choose to remain neutral and lose its spherelings/influence or join the war.
* Changed Cheap Factories to use Steel rather than Iron to be built. Now only Basic Factories use iron.
* Changed the scale of a few vanilla disease modifiers.
* Fixed a rogue decision for Thailand that changed some RGOs in Vietnam.
* There's a vanilla bug that happens when a country that is mobilizing is annexed, which results in the country having "ghost units" - units in exile that belong to a country that doesn't exist. This creates problems with pops and screws with unit visibility, so HPM has a fix: when the AI detects the problem, they will give a few new and small island provinces in the pacific to the country that has the ghost units until it de-mobilize. This happens usually less than 10 times during a game and the country that demobilizes exists for around 10 days, then it's reabsorbed like nothing happened. This shouldn't cause any problems during a normal game, but if for some reason you'd rather not have the bugfix, there's a starting option to disable it.
* Unciv Rebel pushing back economic reforms should be more random now.
* To avoid abuse, the event that gives infamy for a country that permanently occupies another (or carry on a war they already won) will take longer to fire if players are involved in both sides of the conflict and it will need more strict requirements before firing if the one being occupied is a player.
* Forming Arabia no longer requires unoccupied provinces.
* Building any ships now require a naval base. This is made to represent the different levels of naval tech countries are - not all countries can build ocean-worthy ships at the game start. For uncivs, the closer you are to Europe, the more likely you are to have the necessary ports to build these ships.
* The rest of the Tahiti region islands will go to France with the event to get Tahiti, except for the Pitcairn islands, which will go to the UK (if they exist). Removed the free port that came with the event. Fixed pops in Pitcairn.
* The Hellenic Parliament decision will now give 5 prestige.
* Made a decision to make French Canadian primary in Canada and flip the government to reflect the french government if France owns all Canadian cores or if Canada is a puppet of France.
* Sweden will get an event to support the Danish during the Schleswig-Holstein War. If they choose not to, they lose relations with them and some prestige.
* If France goes to war during the Ems Dispatch event chain, they won't call their allies.
* Changed a few NVs in the americas from Order to Liberty/Equality, to better reflect these nations rejection of their former colonial masters.
* Crisis will now be unlocked from 1886 rather than 1870 - to try and avoid early crisis during the scramble for Africa. Currently considering moving this further.
* Fixed the Burmese OOB.
* To avoid elections being dominated by a single issue (a problem brought forward when update 3.04 changed election events to be nation wide without changing their effects), the nation-wide events were changed to affect random states according to the number of states the nation has. The option that has the least impact on moving the issue (usually the last option) is still applicable nation wide.
* Reduced the immigration bonus Secondary Powers get to avoid an oligopoly of counties that can attract immigrants.
* Minor changes to the RGO Spread events so tractors, explosives and electricity so spam is reduced in high-literacy countries. Might rework this to somehow cut down spam to the player entirely while preserving the gradual spread.
* Tweaked the Tewodros event chain to give a bit more of an advantage to the country that gets it.
* Fixed the OOB for the Ha'il, Nejd, Hedjaz and the Yemeni states. Added a general for each and adjusted starting relations.
* Fixed bad requirements for the events in the integrated HPM misc minimod that made the South Tirol compromise fire even if Italy didn't border the required provinces and resulted in an exclave being created. Changed the decision in an event chain, which the AI will only take if they are a "Benefactor" AI. The player can still use the compromise if they own South Tirol and it can end in different ways - from population transfers to unresolved.
* Changed Newcastle to Iron. Newcastle flips to coal later in the century. Plymouth, Holyhead and Isle of Man change to Iron later on in the game.
* Added a decision for Austria to reclaim Eisenstadt from a puppet Hungary, getting the province, eliminating the Hungarian core and getting a core there. This was done because they lose their cores there if they free Hungary.
* Added a system that attributes a personality to the AI, so they can use decisions which don't make sense to be used always. This system is in its infancy and only applies to the South Tirol Compromise decision, but in the future it will apply to much more. Right now there's two types of AI: Benefactor and Malevolent.
* Reworked the system that dealt with mass killings. The main points are:
	* When the decision (Named "Directive No 1") is taken, you get a modifier. This modifier is the main thing that will give infamy. It will start giving a low amount of infamy but as more killings are done, there's a chance of more infamy coming.
	* Political and Social reforms will be blocked. This is made to represent the state focusing its whole bureaucracy in the task at hand.
	* Population loss will not be done at once in a national event. It will happen over time with state-events. Every time one of these events fire there's a chance that the evidence for the ongoing massacre is going to tick up.
	- These events have a somewhat high MTTH but will happen faster in states that:
		* Have a majority of primary/accepted pops.
		* Are your cores.
		* Where your primary/accepted pops AND the ruling party ideology are the majority
		* Have soldiers in it.
		* Have good infrastructure.
		*Among other things.
		
	- Nation-wide policies/triggers that will affect the speed of these events are:
		* High/low admin and military spending.
		* Certain techs can speed it up (e. g. machine guns, gas attacks).
		* Totalitarian state modifier will greatly speed it up.
	
	- These events will not happen in a state:
		* Where there isn't a single pop of the primary/accepted culture (and there isn't any brigades in the province).
		* Occupied provinces or being occupied by rebels or other countries forces.
	* For it to happen on states without any primary/accepted pops, you need at least one military unit in the state. It will take longer to happen and be less effective.
	* The more the "evidence clock" has ticked, the bigger the faster the events fire. The higher the chance of a scandal erupting. 
	* The player can choose to end the policy at any time, but there's a cooldown to dismantle the apparatus before it can be re-done again. The time the player will wait will depend on how long the thing has has been going - with bigger cooldowns when the events have been running for longer.
	* Losing a war, a change in the type of government or having the "national confusion" modifier will interrupt the process. 
  
  ***
  
  
