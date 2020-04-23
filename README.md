# space-engineers-star-system-progression
I wanted to make a bit harder survival Star System type world where starting anywhere is possible but you still need to go through objective steps in order to advance efficiently.

## The idea of it

With these mods the EarthLike has really poor access to anything but the basic construction ores, plus cobalt and magnesium. You want to get to orbit for good sources of silver in asteroids. Then to the Moon for gold, to MarsLike for Platinum, and either Triton or Alien planets for Uranium.

Roughly the same logic applies to other planets but they have other challenges as well. Mars is a harsh start with the lack of oxygen. You need to pretty quickly find ice inside suface boulders and you won't find cobalt easily until you have Jump Drives. Alien planet has an unbreathable oxygen atmosphere with a fairly strong gravity field, but similarly has few sources of cobalt, which it's moon Titan does has near the surface. Triton has plentiful uranium and a breathable atmosphere but a very high gravity.

## Procedurally Generated Ore
I've used this tool to generate ore maps for all official planets including Triton. However, I still haven't found out how to modify surface boulders on Triton.

Generally the ores are in larger veins than Space Engineers normally provides, and the common ones even moreso. If an ore is rare on some planet, it really is rare, and in much smaller patches than they otherwise would be.

In many cases the ores with low numbers are up to 300m deep in the ground and plentiful rare ones are usually closer to surface than they normally would. Almost all of the rare deep ores have no surface hints, and these days even shallow ones are hard to see by default.

The numbers below are not directly comparable between planets and moons due to surface area differences.

Ores in Map | EarthLike | Moon | Triton | Mars | Europa | Alien | Titan
----------- | --------- | ---- | ------ | ---- | ------ | ----- | -----
Iron | 182503 | 3196 | 75058 | 67473 | 3311 | 222045 | 2215
Nickel | 64847 | 5008 | 36141 | 57137 | 1625 | 80519 | 3534
Silicon | 44016 | 17808 | 29217 | 24771 | 3443 | 5459 | 4369
Cobalt | 174137 | 188 | 50085 | 278 | 1545 | 989 | 34519
Magnesium | 33917 | 5994 | 36286 | 23240 | 17081 | 64395 | 675
Silver | 121 | 5864 | 219 | 221 | 126 | 90308 | 17
Gold | 181 | 5152 | 4952 | 168 | 4211 | 262 | 4616
Uraninite | 154 | 91 | 7619 | 376 | 71 | 35459 | 35
Platinum | 160 | 490 | 473 | 45359 | 299 | 578 | 52

## Planetary modifications
I've changed gravity and atmosphere parameters on most planets other than EarthLike.

Planet | Gravity | Atmosphere density | Oxygen density | Max wind speed
------ | ------- | ------------------ | -------------- | --------------
EarthLike 	| 1.0 	| 1.0 	| 0.9 	| 80
Moon 		| 0.25 	| none	| none	| none
Triton 		| 1.9 	| 1.4 	| 0.6 	| 70
Mars 		| 0.6 	| 0.6 	| none 	| 60
Europa 		| 0.3 	| yes 	| none 	| 50
Alien 		| 1.6 	| 1.2 	| 0.1 	| 120
Titan 		| 0.4 	| yes 	| none 	| 50
