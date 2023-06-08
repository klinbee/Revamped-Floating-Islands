# Floating-Islands-1.18-1.20
Datapack that changes the world generation for all dimensions to be floating islands, with biomes and structures, along with some additional changes to help for balancing.

After 1.18, Mojang stopped supporting Floating Islands world types, which is a shame because it's a really cool world type. Even though it is unsupported, it does still exist in the code somewhat, but it is imperfect and doesn't even generate with biomes. My goal was to change this, and even improve on the default by changing the ore distribution for balancing and ocean formation to look cooler and more realistic. 

Changes:
1. Adds the normal biome distribution into floating islands.
2. And due to biomes being added, structures properly generate.
3. Made ores more common since there is less terrain.
4. Made diamond/ancient debris vein sizes larger again because of less terrain.
5. Added "oceans" where less terrain generates and more aquifers generate to simulate floating bodies of water.
6. Increased the amount of sugarcane that generates due to less bodies of water.
7. Made certain pockets of water not generate in swamps/mangroves due to excessive water pouring.
8. Made lavafalls/waterfalls less common due to excessive pouring. (Also limited their y-value).
9. Changed the y-value for bastion generation to fit more with the floating islands style generation.
10. Changed ancient city generation to work with the constraints of floating island generation.
11. Changed the default block for ancient city to be stone, and the default block for warm/lukewarm oceans to be sand/sandstone instead of grass.

If there are any specific changes you do not like, let me know, and I can make a specific version that removes these changes. 

A common request could just be removing floating islands with different dimensions, and this can be done by removing the "dimension".json file from the noise_settings folder. (So remove nether.json to remove the floating islands generation from the nether).

Additionally I could attempt to do a caves world gen (like for the end or overworld), but I myself don't have that much of an interest in it at the moment. Let me know if you are interested. :).


Backstory: Several months ago, I wanted to play a floating islands on survival. I watched a video on how to do it, but things kept going wrong. Firstly, the video was for 1.18, and 1.19 does not allow you to import world gen settings due to a bug that is currently unpatched. Secondly, because floating islands have become unsupported by mojang (kind of) they only generate river and frozen river biomes in the overworld. This made me very upset because I wanted the full experience: jungles, badlands, snowy taigas, villages, outposts, mansions, etc. Only river biomes stopped this from occuring. I tried seeking help, but could not find any. Eventually, I came back to it and I made huge progress and in only a few hours, I found out how to add the biomes back and tweaked the world gen to go lower than normal (so you could get proper deepslate layers). I also lowered the height of the floating islands a tiny bit (from y=184 to y=160) because the world felt a bit larger with the added lower y-values (which caused more lag, this is kind of a laggy datapack though but should not be terrible). After dealing with the overworld, I took a crack at the nether and it was also easier than I expected so I just did that as well. Eventually I found the ocean biomes to be boring, and tried, and tried, and TRIED for SO LONG to make the oceans look better using many many many many many methods, and finally, as of V1.5, I feel most satisfied with it. I also changed ore distribution after realizing how it would probably be unfair to not be able to get as many ores just because there is less land.
