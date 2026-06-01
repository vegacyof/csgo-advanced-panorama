# csgo-advanced-panorama

Modified Panorama CSGO with the removal of outdated features and the addition of some custom features

## Features

1. Outdated functions have been removed (e.g. statistics tab, match preview tab, team search button, and so on)
2. Unlocking the Danger Zone in the menu
3. The Advanced Settings tab is in the settings with the ability to configure additional binds, net_graph, hand position, and server.
4. Showing the Spectator ping in TAB
5. The store panel remains in the main menu.

## Installation

1. Download `panorama.dll`, `csgo_advanced_ru.txt` (for the Russian language) or `csgo_advanced_en.txt` (for the English language) and `code.pbin` from the Releases page.
2. Replace `panorama.dll` in the `bin` folder (located next to `csgo.exe`).
3. Replace `code.pbin` in `csgo/panorama/` folder (e.g., `D:\SteamLibrary\steamapps\common\csgo legacy\csgo\panorama\`).  
   *Make a backup of the original `code.pbin` before replacing.*
4. Transfer the localization file (`csgo_advanced_ru.txt` or `csgo_advanced_en.txt` ) to the `csgo/resource` folder (example above)
5. Run CSGO with the launch parameter `-language advanced_ru` for Russian localization or `-language advanced_en` for English localization.

## Requirements

For proper functionality, a custom game coordinator is required:  
https://github.com/mikkokko/csgo_gc

## Credits

[shashlik226](https://github.com/shashlik226) - for help with the basics of panorama editing

Jackal - for the help in testing the mod