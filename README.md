# PNguide
a simple guide to make prehistoric nature run if you are having issues running it like lag, fps drops and other mods to make gameplay better

go here for FAQ [**FAQ**](FAQ.md)
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

as well use Mixin 0.7-0.8 Compatibility some mods are old and may crash on you without this mod 
https://www.curseforge.com/minecraft/mc-mods/mixin-0-7-0-8-compatibility

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

## JVM

and now the JVM 

Xmx?G is the max ram to give minecraft and the Xms?x should be half of the max ram 

you can change the G to m                                       

G = GB

m = mb

1024mb = 1Gb

-Xmx8G -Xms4G -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+UseNUMA -XX:+CMSParallelRemarkEnabled -XX:MaxTenuringThreshold=15 -XX:MaxGCPauseMillis=30 -XX:GCPauseIntervalMillis=150 -XX:+UseAdaptiveGCBoundary -XX:-UseGCOverheadLimit -XX:+UseBiasedLocking -XX:SurvivorRatio=8 -XX:TargetSurvivorRatio=90 -XX:MaxTenuringThreshold=15 -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:+UseFastAccessorMethods -XX:+UseCompressedOops -XX:+OptimizeStringConcat -XX:+AggressiveOpts -XX:ReservedCodeCacheSize=2048m -XX:+UseCodeCacheFlushing -XX:SoftRefLRUPolicyMSPerMB=10000 -XX:ParallelGCThreads=2 

## How do I change my RAM or JVM arguments?

You probably want at least 4GB assigned to Minecraft to play the Prehistoric Nature mod.

Using the Minecraft Launcher:
- Click on "Installations" at the top
- Hover over your installation and then click the three dots on the right -> Edit
- More options (near the bottom)
- In "JVM Arguments" you can add your new arguments or edit them
- To allocate more RAM to the installation you need to edit the first thing you can see there beginning with -Xmx. The immediate next numbers before the space show the RAM. The format works so that to allocate 4GB you change this to say -Xmx4G
- "Save" and play

Using the Curseforge Launcher:
If you need to edit the JVM arguments then follow the steps above after Curseforge launches the Minecraft Launcher. Note that Curseforge will not remember the JVM arguments next time - very annoying and you will need to put them again every time you open it.
If you only need to edit RAM you can also do it like this:
- Open your installation in the Curseforge App
- Next to the play button at the top right, click on the three little dots -> Profile Options
- Untick the "Use System Memory Settings" box
- Slide the slider up to the amount of RAM you want to use
- "Done" and play 

https://github.com/hampop/PNguide/assets/87606666/09f0370f-8bf5-4cb8-88e2-c084cf598211

https://github.com/hampop/PNguide/assets/87606666/8a84dd72-6592-4961-8789-de8c87af9c25










