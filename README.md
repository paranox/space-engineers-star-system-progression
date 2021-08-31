# space-engineers-star-system-progression
I wanted to make a Star System type scenario where starting anywhere is possible but you still need to go through objective steps in order to advance efficiently.

[Workshop link](https://steamcommunity.com/sharedfiles/filedetails/?id=2071799682)

## The idea of it

All Planets and Moons are available for starting out from. You do find all ores ores on all planets but each have specialties and limitations.

Basically you usually need to get to asteroids or moons for silver and only moons provide plentiful gold. Other planets will provide for whatever you don't reliably get where you started.

Asteroids won't have Uranium nor Platinum in them, but other resources will be available in them, Gold and Silver quite rarely but in larger veins.

### EarthLike Planet
An easy start with a breathable atmosphere, good winds and rich in basic construction ores. Plenty of Cobalt and Magnesium to be found too.

**Water Mod + Agaris Planet**
In many ways same as EarthLike but with surface water for ice collectors and underground water even in deserts. While ores somewhat follow the original planet's oremaps, they are mostly spread out the same as EarthLike. You find richer veins where original veins were. Especially the rare ores are almost never found elsewhere.

### EarthLike's Moon
A really hard start with no atmosphere, so no winds, and ice only at the poles. Average basic construction ores with plentiful Silicon but very scarce Cobalt. Good sources of Magnesium, Silver and Gold. Lack of Cobalt ore creates a situation where fighting NPCs is the most reliable source of it.

### MarsLike Planet
A really hard start with a thin atmosphere, weak winds and no oxygen. You need to quickly find ice inside surface boulders or at the poles. While Platinum is plentiful and found closer to surface, Cobalt is more scarce and deeper. Same as on Earth starts you need to get to the moon Europa for a reliable source of Gold, and plentiful ice, but Silver isn't common there either.

### Europa Moon
A hard start with a very thin atmosphere and weak winds, plentiful ice for oxygen though. Basic construction ores are not too common and Silver is rare but Gold and especially Magnesium are easily found. Getting to orbit or Mars might really be necessary for any progress.

### Alien Planet
Either a really hard start or a normal one depending on whether spiders are enabled or not. Has a dense unbreathable oxygen atmosphere with a fairly strong gravity field and strong winds. Rich in everything except Gold, Uraninite and Platinum.

### Titan Moon
A hard start with a very thin atmosphere, weak winds and no oxygen. You can find ice lakes around the surface for the most part. Cobalt is plentiful and found close to surface, good amounts of basic construction ores and Gold can be found, but almost no Silver.

### Triton Planet
A normal start with a breathable atmosphere but very high gravity and very strong winds. Relatively rich in all basic construction ores and even has some moderate amounts of Uraninite. Getting off this planet is a challenge but once you do you'll be rather well equipped. There is no moon, so scouting asteroids are needed for Silver and Gold.

### Pertam Planet
A normal start with a breathable, slightly denser atmosphere and strong winds, but no ice to speak of. Gravity is higher as well. The planet has only low amounts of basic construction ores, only little bit of Magnesium, but rather high amounts of all rare ores, especially Uraninite. There is no moon, but asteroids can provide easier access to Magnesium and constrution ores.

## Planetary modifications
I've changed gravity and atmosphere parameters on most planets.

Planet / Params | Gravity | Atm. Dens. | O2 Dens. | Max winds
--------------- | ------- | ---------- | -------- | ---------
EarthLike       | 1.0     | 1.0        | 0.9      | 80
Moon            | 0.25    | none       | none     | none
Mars            | 0.6     | 0.3        | none     | 40
Europa          | 0.3     | 0.1        | none     | 20
Alien           | 1.5     | 1.2        | 0.1      | 120
Titan           | 0.4     | 0.2        | none     | 20
Triton          | 1.9     | 1.4        | 0.9      | 150
Pertam          | 1.2     | 0.8        | 0.8      | 100
Agaris (Water)  | 1.0     | 1.0        | 0.9      | 80

### Procedurally Generated Ores
I've used this tool to generate ore maps for all official planets including new official planets. However, I still haven't found out how to modify surface boulders on Triton.

In many cases the ores with low numbers are up to 300m deep in the ground and plentiful rare ones are usually closer to surface than they normally would. The numbers below are not directly comparable between planets and moons due to surface area differences.

Planet / Ore    | Iron   | Nickel | Silicon | Cobalt | Magnesium | Silver | Gold  | Uraninite | Platinum
------------    | ------ | ------ | ------- | ------ | --------- | ------ | ----- | --------- | --------
EarthLike       | 182503 | 64847  | 44016   | 174137 | 33917     | 121    | 181   | 154       | 160
Moon            | 3196   | 5008   | 17808   | 188    | 5994      | 5864   | 5152  | 91        | 490
Mars            | 57223  | 53898  | 23748   | 23409  | 23240     | 221    | 168   | 376       | 45359
Europa          | 3311   | 1625   | 3443    | 1545   | 17081     | 126    | 4211  | 71        | 299
Alien           | 173149 | 71064  | 69632   | 57493  | 68114     | 56952  | 633   | 2353      | 632
Titan           | 5867   | 6347   | 5918    | 13621  | 2255      | 40     | 8113  | 144       | 63
Triton          | 76671  | 38676  | 28427   | 54584  | 36114     | 259    | 2864  | 1933      | 477
Pertam          | 8905   | 4454   | 6789    | 2056   | 539       | 16509  | 26525 | 32194     | 10880
Agaris (Water)  | 182503 | 64847  | 44016   | 174137 | 33917     | 121    | 181   | 154       | 160

## Deployment
Until I can be arsed to automate this with a script, here's a list of things used in mods:

### Star System Progression V2
* `metadata.mod` (from `/configs/Workshop/Star System Progression V2/metadata.mod`)
* `readme.txt` (from `/configs/Workshop/Star System Progression V2/readme.txt`)
* `thumb.jpg` (from `/configs/Workshop/Star System Progression V2/thumb.jpg`)
* `Data/*.sbc` (from `/Planets/*.sbc`)
* `Data/VoxelMaterialChangesBoulders.sbc` (from `/Surface Boulders/VoxelMaterialChangesBoulders.sbc`)
* `Data/VoxelMaterialChangesAsteroids.sbc` (from `/Scarcer Asteroid Ores/VoxelMaterialChangesAsteroids.sbc`)
* `Data/PlanetDataFiles` (from `/Ore Maps/PlanetDataFiles`)

### Star System Progression V2 - Water Planet Agaris
* `metadata.mod` (from `/configs/Workshop/Star System Progression V2 - Water Planet Agaris/metadata.mod`)
* `readme.txt` (from `/configs/Workshop/Star System Progression V2 - Water Planet Agaris/readme.txt`)
* `thumb.jpg` (from `/configs/Workshop/Star System Progression V2 - Water Planet Agaris/thumb.jpg`)
* `Data/Agaris.sbc` (from `/Planets - Water Mod/Agaris.sbc`)
* `Data/PlanetDataFiles/Planet Agaris` (from `/Ore Maps - Water Mod/PlanetDataFiles/Planet Agaris`)

## The Scenario
This mod is used in [this scenario (git respository)](https://github.com/paranox/space-engineers-survival-progressively-less-likely) and it defines the star system itself.
