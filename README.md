# space-engineers-star-system-progression
I wanted to make a Star System type scenario where starting anywhere is possible but you still need to go through objective steps in order to advance efficiently.

[Workshop link](https://steamcommunity.com/sharedfiles/filedetails/?id=2071799682)

## The idea of it

With these mods the EarthLike has really poor access to anything but the basic construction ores, plus cobalt and magnesium. You want to get to orbit for good sources of silver in asteroids. Then to the Moon for gold, to MarsLike for Platinum, and either Triton or Alien planets for Uranium.

Roughly the same logic applies to other planets but they have other challenges as well. Mars is a harsh start with the lack of oxygen. You need to pretty quickly find ice inside suface boulders and you won't find cobalt easily until you have Jump Drives. Alien planet has an unbreathable oxygen atmosphere with a fairly strong gravity field, but similarly has few sources of cobalt, which it's moon Titan does has near the surface. Triton has plentiful uranium and a breathable atmosphere but a very high gravity.

## Procedurally Generated Ore
I've used this tool to generate ore maps for all official planets including Triton. However, I still haven't found out how to modify surface boulders on Triton.

In many cases the ores with low numbers are up to 300m deep in the ground and plentiful rare ones are usually closer to surface than they normally would. The numbers below are not directly comparable between planets and moons due to surface area differences.

Planet | EarthLike | Moon | Triton | Mars | Europa | Alien | Titan
------ | --------- | ---- | ------ | ---- | ------ | ----- | -----
Iron | 182503 | 3196 | 75058 | 67473 | 3311 | 222045 | 2215
Nickel | 64847 | 5008 | 36141 | 57137 | 1625 | 80519 | 3534
Silicon | 44016 | 17808 | 29217 | 24771 | 3443 | 5459 | 4369
Cobalt | 174137 | 188 | 50085 | 278 | 1545 | 989 | 34519
Magnesium | 33917 | 5994 | 36286 | 23240 | 17081 | 64395 | 675
Silver | 121 | 5864 | 219 | 221 | 126 | 90308 | 17
Gold | 181 | 5152 | 4952 | 168 | 4211 | 262 | 4616
Uraninite | 154 | 91 | 7619 | 376 | 71 | 35459 | 35
Platinum | 160 | 490 | 473 | 45359 | 299 | 578 | 52

## The Scenario
This mod is used in [this scenario (git respository)](https://github.com/paranox/space-engineers-survival-progressively-less-likely) and it defines the star system itself.