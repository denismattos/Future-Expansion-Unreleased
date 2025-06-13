# Sullien's Comments
Much like [I did with my reupload of Future Expansion](https://github.com/denismattos/Future-Expansion-Unreleased/blob/main/authors_comments.md), I'm cleaning the .json of comments by moving them to a separate file, here.
## [Buildings.json](/jsons/Buildings.json)
Buildings.json's comments were used to divide additions and modifications by eras and categories.
### "Always Available (Kept because the Palace stores Policy Upgrades.)"
* Palace
* Leadership Hall
### "Renaissance Era"
* Sewer
* Newspaper
* Publication Depot
* Zoo
* Observatory
* Work Mill
* Opera House
* Ceilidh Hall
* Bank
* Satrap's Court
* Seaport
* Museum
* Public School
* Arsenal
### "Industrial Era"
* Factory
* Hospital
* Medicine Depot
* Coal Plant
* Stock Exchange
* Hydro Plant
* Oil Plant
* Train Station
* Weapons Depot
* Clothes Depot
* Military Academy
### "Modern Era"
* Broadcast Tower
* Stadium
* Supermarket
* Vehicles Depot
* Military Base
* Electronics Depot
* Plastics Factory
* Cannery
### "Atomic Era"
* Branch Office
* Airport
* Research Lab
* Spaceship Factory
* Visitor Center
* Nuclear Plant
* Heat Plant
* Recycling Center
* Bomb Shelter
### "Information Era"
* Medical Lab
* TV Station
* Missile Silo
* Environmental Center
* Military Lab
* Administration Center
* Operations Network
* Space Station
### "Future Era"
* Nano-Foundry
* Space Colony
* Energy Barrier
* Clean Plant
* Automatic Factory
### "World Wonder"
* Great Wall
* Petra
* Forbidden Palace
* Himeji Castle
* Leaning Tower of Pisa
* Porcelain Tower
* Sistine Chapel
* Taj Mahal
* Brandenburg Gate
* Big Ben
* The Louvre
* Kremlin
* Herat Citadel
* Statue of Liberty
* Eiffel Tower
* Cristo Redentor
* Empire State Building
* Manhattan Project
* Pentagon
* Gwangyang Mill
* Sydney Opera House
* United Nations
* Apollo Program
* Biosphere
* Hadron Collider
* Titan Missile Museum
* CN Tower
* Messeturm
* Hubble Space Telescope
* World Alliance
* Utopia Project
### "National Wonder"
* National Hall
* National Service
* Recruitment Center
* Defense Center
* Nuclear Testing Site
* Navigation Network
* Colony Ship Blueprints
### "Projects (Most of these Uniques are not functional and only there to inform, they are stored in the Improvements instead.)"
* Fertilizer Breakthrough I
* Fertilizer Breakthrough II
* Fertilizer Breakthrough III
* Economic Breakthrough I
* Economic Breakthrough II
* Economic Breakthrough III
* Industrial Breakthrough I
* Industrial Breakthrough II
* Industrial Breakthrough III
* Merchant Faculties I
* Merchant Faculties II
* Merchant Faculties III
* Artist Faculties I
* Artist Faculties II
* Artist Faculties III
* Scientist Faculties I
* Scientist Faculties II
* Scientist Faculties III
* Engineer Faculties I
* Engineer Faculties II
* Engineer Faculties III
* Refining Breakthrough I
* Refining Breakthrough II
* Refining Breakthrough III
* Infrastructure Breakthrough I
* Infrastructure Breakthrough II
* Infrastructure Breakthrough III
* Implants Breakthrough I
* Implants Breakthrough II
* Implants Breakthrough III
## [Eras.json](/jsons/Eras.json)
* Ancient era's `"startingSettlerCount": 1` line was commented:  
"These values should not include the values given in Difficulties.json."
* Information era's `"settlerBuildings"` attribute was commented (Presumably referring to the following `"startingObsoleteWonders"` attribute.):  
"So, theoretically, this is always just all the wonders at least 2 eras old. So we could just use that.  
But where is the modularity? The excluding of very specific wonders? That is no fun.  
So we just write down the entire long list (sorted by era!), instead."
## [TileImprovements.json](/jsons/TileImprovements.json)
TileImprovements.json's comments were used to divide improvements by eras and categories.
### "Basic Improvements"
* Farm
* Mine
* Trading Post
* Fort
* Windmill
* Resort
* Solar Farm
* Wind Farm
* Offshore Wind Farm
### "Resource Exclusive"
* Lumber Mill
* Pasture
* Camp
* Plantation
* Quarry
* Fishing Boats
* Oil Well
* Excavation Site
* Supply Route
* Industry
* Offshore Platform
### "Infrastructure"
* Urban District
* Industrial Zone
* Commercial Center
### "Enhancer"
* Water Plant
* Warehouse
* Institute
* Stage
* Park
* Media Center
### Great Improvements
* Academy
* Landmark
* Manufactory
* Customs House
* Holy Site
* Launch Site
* Citadel
### "Unique"
* Railroad
* City Center
## [TileResources.json](/jsons/TileResources.json)
TileResources.json's comments were used to divide resources by categories.
### "Bonus"
Natural Appeal
### "Strategic"
* Coal
* Oil
* Aluminum
* Uranium
### "Luxury"
Fossil
### "Manufactured Resources" 
* Power
* Composites
* Weapons
* Vehicles
* Clothes
* Medicine
* Publication
* Electronics
## [UnitPromotions.json](/jsons/UnitPromotions.json)
Some of UnitPromotions.json's promotions were divided by categories using comments.
### "Melee Infantry"
* Attacker I
* Attacker II
* Attacker III
* Defender I
* Defender II
* Defender III
* First Aid
* Guard
* Surprise
* Rally
* Advance
* Rush
### "Ranged Infantry"
No promotions.
### "Recon Infantry"
* Survival I
* Survival II
* Survival III
* Patrol I
* Patrol II
* Patrol III
* Voyage
* Retreat
* Raider
* Bribery
### "Melee Armor"
* Impact
* Oportunity
* Outmaneuver
* Blockade
* Push
### "Ranged Armor"
No promotions.
### "Recon Armor"
No promotions.
### "Melee Water"
* Lurk
* Extra Range
* Supplies
### "Ranged Water"
No promotions.
### "Recon Water"
No promotions.
### "Air Fighter"
* Interception I
* Interception II
* Interception III
* Air Siege I
* Air Siege II
* Air Siege III
* Bombardment I
* Bombardment II
* Bombardment III
* Operational Range
* Air Targeting
* Sortie
* Strategic Bombing
* Evasion
* Air Repair
* Dual Strike
### "Implants"
* Speed Implant
* Skin Implant
* Stealth Implant
* Optic Implant
* Mechsuit Implant
### "Unique Type"
* Disciplined
* Morale
* Tactics
* Implants
* Future Weaponry
* Ignore Terrain Cost
## [Units.json](/jsons/Units.json)
Units.json's comments were used to divide units by eras and categories.  
Additional comments were:
* Samurai was commented: "Samurai should also create Fishing Boats (not now, surely)."
* Berserker was commented: "Danish unique unit. Can attack from the sea without any penalty, and moves faster."
### Civilian
* Worker
* Heavy Worker
* Worker Bot
* Work Boats
* Great Spacefarer
### "Pre-Renaissance Era (Included due to Unit Upgrade Tree)"
* Scout
* Horse Archer
* Pikeman
* Landsknecht
* Trebuchet
* Hwach'a
* Longswordsman
* Samurai
* Berserker
* Crossbowman
* Chu-Ko-Nu
* Longbowman
* Knight
* Camel Archer
* Conquistador
* Naresuan's Elephant
* Mandekalu Cavalry
* Keshik
### "Renaissance Era"
* Caravel
* Fusilier
* Musketman
* Janissary
* Minuteman
* Tercio
* Lancer
* Sipahi
* Hakkapeliitta
* Cannon
* Frigate
* Ship of the Line
* Privateer
* Sea Beggar
### "Industrial Era"
* Rifleman
* Carolean
* Mehal Sefari
* Norwegian Ski Infantry
* Gatling Gun
* Ranger
* Ironclad
* Cavalry
* Cossack
* Hussar
* Submarine
### "Modern Era"
* Great War Infantry
* Foreign Legion
* Landship
* Infantry
* Machine Gun
* Tank
* Panzer
* Artillery
* Destroyer
* Battleship
* Triplane
### "Atomic Era"
* Fighter
* Zero
* Bomber
* B17
* Paratrooper
* Anti-Tank Gun
* Anti-Aircraft Gun
* Mechanized Infantry
* Carrier
* Atomic Bomb
* Rocket Artillery
* Helicopter Gunship
### "Information Era"
* Mobile SAM
* Jet Fighter
* Nuclear Submarine
* Guided Missile
* Nuclear Missile
* Missile Cruiser
* Modern Armor
* Jet Bomber
### "Future Era"
* Enhanced Infantry
* Warbot
* Hovertank
* Hovertillery
* Predator
* Seeker
* Giant Death Robot
* Orbital Fighter
* Orbital Strike
### "Unique"
* SS Booster
* SS Cockpit
* SS Engine
* SS Stasis Chamber