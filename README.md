# space-engineers-star-system-progression
I wanted to make a Star System type scenario where starting anywhere is possible but you still need to go through objective steps in order to advance efficiently.

[Workshop link](https://steamcommunity.com/sharedfiles/filedetails/?id=2071799682)

## The idea of it

Basically you need to get off-planet for silver, to the nearby moon for gold, and to other planets for whatever you don't reliably get where you started. Moons with an atmopshere have weak winds.

### EarthLike Planet
Breathable atmosphere, rich in basic construction ores plus plenty of cobalt and magnesium. You want to get to orbit for good sources of silver in asteroids. Then to the Moon for gold, to MarsLike for Platinum, and either Triton or Alien planets for Uraninite.

### MarsLike Planet
A really harsh start with weak winds the lack of oxygen - you need to quickly find ice inside surface boulders or on the ground. While Platinum is plentiful and found closer to surface, Cobalt is scarce and deeper. Same as on Earth starts you need to get to the moon Titan for reliable source of gold. Titan also has plentiful Magnesium.

### Alien Planet
Has an unbreathable oxygen atmosphere with a fairly strong gravity field and strong winds. Rich in Silver, Uraninite and basic construction ores, but less plentiful cobalt compared to EarthLike. It's moon Titan has some cobalt very near the surface.

### Triton Planet
Breathable atmosphere but a very high gravity and not too strong winds. Relatively rich in basic construction ores plus Uraninite but also has notable amounts of Gold as well since it has no moon. Getting off this planet is a challenge but once you do you'll be rather well equipped.

## Procedurally Generated Ore
I've used this tool to generate ore maps for all official planets including Triton. However, I still haven't found out how to modify surface boulders on Triton.

In many cases the ores with low numbers are up to 300m deep in the ground and plentiful rare ones are usually closer to surface than they normally would. The numbers below are not directly comparable between planets and moons due to surface area differences.

Planet | EarthLike | Moon | Triton | Mars | Europa | Alien | Titan
------ | --------- | ---- | ------ | ---- | ------ | ----- | -----
Iron | 182503 | 3196 | 75058 | 57223 | 3311 | 170973 | 5867
Nickel | 64847 | 5008 | 36141 | 53898 | 1625 | 68437 | 6347
Silicon | 44016 | 17808 | 29217 | 23748 | 3443 | 9276 | 5918
Cobalt | 174137 | 188 | 50085 | 23409 | 1545 | 53512 | 13621
Magnesium | 33917 | 5994 | 36286 | 23240 | 17081 | 67098 | 2255
Silver | 121 | 5864 | 219 | 221 | 126 | 92999 | 40
Gold | 181 | 5152 | 4952 | 168 | 4211 | 603 | 8113
Uraninite | 154 | 91 | 7619 | 376 | 71 | 36517 | 144
Platinum | 160 | 490 | 473 | 45359 | 299 | 597 | 63

## The Scenario
This mod is used in [this scenario (git respository)](https://github.com/paranox/space-engineers-survival-progressively-less-likely) and it defines the star system itself.