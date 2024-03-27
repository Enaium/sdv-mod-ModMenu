﻿# ModMenu

ModMenu

## Install

1. [Install the latest version of SMAPI](https://smapi.io/).
2. Install [this mod](https://www.curseforge.com/stardewvalley/mods/modmenu).
3. Install [EnaiumToolKit](https://www.curseforge.com/stardewvalley/mods/enaiumtoolkit).
4. Run the game using SMAPI.

## Custom

`manifest.json`

### Setting

namespace.className

```json
{
  "Custom": {
    "ModMenu": {
      "Setting": "ModMenu.Framework.Screen.SettingScreen"
    }
  }
}
```

```c#
namespace ModMenu.Framework.Screen
{
    public class SettingScreen : IClickableMenu
    {
        
    }
}
```

### Contact

```json
{
  "Custom": {
    "ModMenu": {
      "Contact": {
        "HomePage": "https://github.com/Enaium-StardewValleyMods/ModMenu",
        "Issues": "https://github.com/Enaium-StardewValleyMods/ModMenu/issues"
      }
    }
  }
}
```