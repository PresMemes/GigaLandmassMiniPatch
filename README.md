# GigaLandmassMiniPatch

## Load order
```
UI Overhaul Dynamic
Landmass
Miniatures
Gigastructural Engineering & More (3.4)
Gigastructures - Landmass - Miniatures patch
```
Or something like that  

Put `GigaLandmassMiniPatch` into your `Documents\Paradox Interactive\Stellaris\mods` folder and Irony should detect it. (Or your custom mod folder if you have one set up)

Make sure to download Gigastructures https://steamcommunity.com/sharedfiles/filedetails/?id=1121692237 so you can check the original files

## test.sav
Put `test.sav` into your `Documents\Paradox Interactive\Stellaris\save games` folder, and it should boot you straight to the Giga settings screen, and I've already reseached all techs and maxed your resources. Of course, you can always make your own save and use that for testing.

You do NOT need a new game for .asset file changes, loading an existing one is perfectly fine.

## Known issues
NOTE: Sometimes, changing a planet's class via console (planet_class pc_flat_world) will make it dissapear. In that case, you need to spawn it naturally. Either through the intended event chain (EHOF stuff) or unzipping your save game to find which star a certain planet spawned.  
```
- (AETERNUM/MEGASTRUCTURE) Orbital Arcology does not scale with the Planetary Computers? Works fine with other planets.
```
## To do
- Planet and Star Scaling  
  - Blokkat stuff needs to be tested
  - Flusio-Arcology needs to be tested naturally (can't use planet_class console commands)
- Ship Scaling  
  - I think this is mostly fine, but please check anyway.
- Megastructure Scaling  
  - Birch World, and everything you can see in the Aeternum home system is done.
