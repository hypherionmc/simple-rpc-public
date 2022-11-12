**Requires FABRIC API for Fabric**

**Requires Quilt Standard Libraries for Quilt**

### IMPORTANT NOTICES

* The documentation has moved to https://srpc.fdd-docs.com
* Based on community feedback, ALL CONFIGS have been moved into `config/simple-rpc` instead of `simple-rpc`. This means no configs for this mod is outside of the config folder anymore. This change is automatic, but please backup your configs just in case.

**Bug Fixes**:

* Fixed Server Entries Config not updating when changes are made (Issue #46)
* Fixed Translated config files not loading before restarting the game (Issue #47)
* Fixed Server Side config not properly sending to the client
* Fixed modded dimensions not being supported properly by dimension overrides (Issue #42)

**New Stuff**:

* You can now use Multiple images for image keys that will be selected at random (Issue #44)
* You can now add your own Configuration variables that can be used just like built-in variables (See here: https://srpc.fdd-docs.com/custom-variables/)
* Added support for ReplayMod (1.16.5+ Fabric Only). Config is in `simple-rpc-replaymod.toml` if the mod is installed

**Changes**:

* ALL CONFIG FILES ARE NOW LOCATED INSIDE config/simple-rpc. This change was made based on community feedback. All configs now live in the config folder instead of on their own. As always, this action is done automatically and no action is needed on your side. Just remember to export the correct folder
* Made internal changes to how configs are handled. Config loading/migrations should now be a lot smoother.
