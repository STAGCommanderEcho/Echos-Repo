THESE ARE EXAMPLE FILES
DO NOT COPY OVER YOUR ORIGINAL FILES

Description:
- Fixes some Log Annoyances.

Files:
- DivingLootConfig.json
	Removes food items from Underwater Loot Containers which removes the folllowing from CrashLogs:
	  Function: 'InitTemperature'
	  NULL pointer to instance
  As far as I know this is caused because the server can't get the food items Temperature while in a container underwater. 
  Please let me know if that's not the case.