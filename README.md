# PNguide
a simple guide to make prehistoric nature run if you are having issues running it like lag, fps drops and other mods to make gameplay better

___

## basic 

first start with the basic
mod you need to make pn work (pn = prehistoric nature)

LLibrary
https://legacy.curseforge.com/minecraft/mc-mods/llibrary 

Patchoul  
https://legacy.curseforge.com/minecraft/mc-mods/patchouli/files/3162874 

and if you want to use all of the dimension mods with pn and if you are getting a Id issue this should fix it as well (DO NOT USE notenoughids IT WILL CRASH)

![65c779c23e95db88472447ea4671e954-png](https://github.com/hampop/PNguide/assets/87606666/3ff769d0-0164-4d53-9e54-90830ce2ebfb)

Roughly Enough IDs
https://legacy.curseforge.com/minecraft/mc-mods/reid 
___

##  Performance mods

now start with Performance mods if you are lagging or having drops frames 
(note some of these need dependency mods installing as well - read their instructions)



Foam​Fix (improves memory usage) 
https://www.curseforge.com/minecraft/mc-mods/foamfix-optimization-mod


if you are still getting memory issue like if you have low ram like 4gb or 8gb ram the next mod will work better for you 


VintageFix (improves memory usage and this mod replaces Foam​Fix) 
https://www.curseforge.com/minecraft/mc-mods/vintagefix



TexFix (improves memory usage and will work with VintageFix and Foam​Fix)
https://www.curseforge.com/minecraft/mc-mods/texfix


TexFix is a bit outdated and there is a other mod that does the same thing as it and more 


censoredasm (improves memory usage and will work with VintageFix and Foam​Fix and will not work with TexFix)
https://www.curseforge.com/minecraft/mc-mods/lolasm


燐/Hesperus (improves the lighting engine and this mod replace Phosphor)
https://www.curseforge.com/minecraft/mc-mods/hesperus


Entity Culling
https://www.curseforge.com/minecraft/mc-mods/entity-culling [in this mod's own config, add in "lepidodendron" to be excluded from the ENTITIES list (but not the the TILE ENTITIES one)]


Nothirium 
https://www.curseforge.com/minecraft/mc-mods/nothirium 


Optifine
https://www.optifine.net/home 


and now the JVM 

Xmx?G is the max ram to give minecraft and the Xms?x should be half of the max ram 

you can change the G to m                                       

G = GB

m = mb

1024mb = 1Gb

-Xmx8G -Xms4G -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+UseNUMA -XX:+CMSParallelRemarkEnabled -XX:MaxTenuringThreshold=15 -XX:MaxGCPauseMillis=30 -XX:GCPauseIntervalMillis=150 -XX:+UseAdaptiveGCBoundary -XX:-UseGCOverheadLimit -XX:+UseBiasedLocking -XX:SurvivorRatio=8 -XX:TargetSurvivorRatio=90 -XX:MaxTenuringThreshold=15 -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:+UseFastAccessorMethods -XX:+UseCompressedOops -XX:+OptimizeStringConcat -XX:+AggressiveOpts -XX:ReservedCodeCacheSize=2048m -XX:+UseCodeCacheFlushing -XX:SoftRefLRUPolicyMSPerMB=10000 -XX:ParallelGCThreads=2 









