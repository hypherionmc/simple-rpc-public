**1.12.2 is a maintenance only update! It does NOT mean it's actively supported again**

**1.19 Forge requires Forge 1.19 - 41.0.110 or later**

**Changes**:

* %ip% is now fully removed and will no longer resolve
* All Configs have been moved to the central Simple RPC folder
* Improved config loading and reloading
* clientID has been renamed to applicationID to align with discord naming

**New Stuff**:

* You can now add buttons to Dimensions
* You can now add an RPC based on Dimension, Biome or BOTH
* Added a new Variable to get the player count excluding you on servers

**Bug Fixes**:

* Fixes `%playerhead%` image variable not working outside of Single and Multi-Player
* Fixed Config Migrations not always succeeding and resulting in multiple config files
* Server Configs on Fabric no longer generate on the Client
* Config files that fail to load now actually log the full error to the logs
