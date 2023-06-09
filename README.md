## Dead Cells Mod: Machine Blowgun

<img src="https://raw.githubusercontent.com/lerarosalene/dc-machine-blowgun/1ca5c77e8d9e560f7ce944f01cd4a6cdfe0fd00d/metadata/preview.jpg" width="600" />

Download and install via [steam workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2949347142).

This mod:
- changes blowgun rate of fire to ~50 per second
- changes its base poison damage from 15/sec for 2 seconds to 15000/sec for 2000 seconds
- gives you free blowgun at start of the game (after first 2 tutorial runs)
- gives you free blowgun in each boss rush run

With this changes blowgun without upgrades and 1-1-1 stats can melt anything up to final 5BC boss.

Last compatibility check: 3.4

## Build it yourself

- `.\build.ps1 build` to create res.pak
- `.\build.ps1 pub` to prepare publish directory to upload fork to steam workshop (change name in metadata.json if you want to do this)
- `.\build.ps1 check` to unpak res.pak to `check` to check what files it contains
- `.\build.ps1 ref` to unpak res.pak of main game in `reference` directory to veiw what's originally inside (it unpacks CDB and TMX files too)
- `.\build.ps1 clean` to remove all files created by this script, including `publish/` and `res.pak`
- `.\build.ps1 live` to patch YOUR ORIGINAL res.pak with this mod (it will allow to use this mod and still have achievements). WARNING: before running any other command besides clean, restore your original res.pak in game folder (Steam can do it for you)
