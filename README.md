## Game controller database for MiSTer

Game controller default mappings derived from https://github.com/gabomdq/SDL_GameControllerDB. 

Non-Linux platform entries are removed and some MiSTer specific entries are added.


### MiSTer specific extensions to gamecontrollerdb format

- platform 'MiSTer' added. In the event of conflict the MiSTer platform takes priority over 'Linux'.
- buttons 'menuok' and 'menuesc' are mappable. If these entries do not exist in the mapping 'a' and 'b' buttons are mapped to these functions.
- Core based matching. 'mistercore:<corename>' limits the mapping entry to only the named core. Wildcards are supported. A database linecan have multiple mistercore entries. 

