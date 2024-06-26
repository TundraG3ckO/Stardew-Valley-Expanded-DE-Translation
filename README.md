# Stardew Valley Expanded - German (de) Translation

# Requirements

[Stardew Valley Expanded](https://www.nexusmods.com/stardewvalley/mods/3753)

###### Optional
- [Grandpa's Farm](https://www.nexusmods.com/stardewvalley/mods/3753?tab=files)
- [Immersive Farm 2 Remastered](https://www.nexusmods.com/stardewvalley/mods/3753?tab=files)

# Usage

Download archive from releases or at [Nexusmods](https://www.nexusmods.com/stardewvalley/mods/17019).

Extract the contents to the Stardew Valley Expanded [mod folder](https://github.com/FlashShifter/StardewValleyExpanded/wiki/Install-guide#main-mod) and leave out the folders that you don't need.

For the translation of the main mod, you can also use the installer.

```
Stardew Valley
└── Mods
    ├── Stardew Valley Expanded - German Translation
    ├── Stardew Valley Expanded
    │   └── [CP] Stardew Valley Expanded
    ├── Grandpa's Farm
    │   └── [CP] Grandpa's Farm
    └── Immersive Farm 2 Remastered
        └── [CP] Immersive Farm 2 Remastered
```

# Create new version

- Update manifest.json to next release version
- Make sure to include the latest compiled installer exe file *after* updating the manifest.json file
- Draft a new release in Github
  - Create a new tag with incremented version
  - Target: main
  - Add release notes
- Pull main branch locally or just fetch tags locally
- Run shellscript and pass in the new tag
  - e.g. `./create-nexus-archives-from-tag.sh 0.0.6`
- Upload archives to Nexusmods
  - only need to upload those that contain changes
