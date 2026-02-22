48 Quests, 95 Objectives using vanilla items as rewards.
- 16 Hunting Quests 
	Objective Total: 32, 
	Objective Types: Action & Collection
- 8 Medical Officer Quests 
	Objective Total: 18, 
	Objective Types: Collection 
- 10 Infected Response officer Quests 
	Objective Total: 30, 
	Objective Types: Target
- 3 Evacuation Support Officer Quests 
	Objective Total: 3, 
	Objective Types: AIVIP
- 2 Supplies Retrieval Officer Quests  
	Objective Total: 2, 
	Objective Types: TreasureHunt
- 1 Threat Intelligence Quests  
	Objective Total: 1, 
	Objective Types: AICamp
	
+ many Travel or Collection Quests and Objectives for DeerIsle Poi & Lore items.

7 Extra Airdrop Locations:
- Airfield, Airfield North, Camp Bear, Camp Eagle, Camp Wolf, Scouts Camp 1 & Scouts Camp 2.

Optional extra files for Expansion-Bundle:
- MapSettings.json to add a Map Marker for the "Quest Starter" area.
- Object .map Files for Quest POI.
- SafeZoneSettings.json to add a 100m SafeZone around the "Quest Starter" area.
- zombie_territories.xml to add between 3-7 Infected at Quest POI.

==================================================================================

Expansion Quests Installation:
- Stop your Server.
- Delete the Folder: 
	config/ExpansionMod/Quests (some servers use profile/)
- Copy this Folder from the pack in its place:
	config/ExpansionMod/Quests
	
- I also recommend:
	- config/ExpansionMod/Settings/QuestSettings.json 
		"MaxActiveQuests": 2
		
	- Using the changes explained in "Extra Quest Configuration" below.

==================================================================================

Extra Quest Configuration:
- mpmissions/empty.deerisle/env/
	If you want to make the "Infected Infestation" missions easier for your players,
	add the content of the file zombie_territories.xml 
	to your servers mpmissions/empty.deerisle/env/zombie_territories.xml
	This will ensure between 3 to 7 extra Infected in each location.
- mpmissions/empty.deerisle/expansion/missions/
	If you want extra Airdrop missions you can add the files from this folder
	to your servers mpmissions/empty.deerisle/expansion/missions/
- mpmissions/empty.deerisle/expansion/objects/
	Add various Static items around the Map at Quest POI, Fire Barrels etc.
- mpmissions/empty.deerisle/expansion/Settings/
	MapSettings.json
	  Adds Expansion Map Marker for the ExpansionQuestBoardSmall.
	SafeZoneSettings.json:
	  Adds a 100m SafeZone around the "Starter" Quest area.
	  
==================================================================================

Questboards and NPCs:
- The ExpansionQuestBoardSmall can be found at:
	Position [5625.979980, 29.932699, 5392.060059]
	Orientation [49.679794, 0.000000, -0.000000]
  This is the "Starter" Quest area.
  
==================================================================================