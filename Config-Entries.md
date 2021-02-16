# Config Entries for Yatopia


### verbose
``Default``: ``false`` Change to ``true`` if You want to turn on verbose mode.

### brand-name
``Default``: ``Yatopia`` What should Your server display as it's brand name.

# settings:

### itemStuckSleepTicks
``Default``: ``1`` Controls how often a dropped item checks rather it's stuck inside a block (their most expansive operation). Higher values like ``15`` can be safely used and greatly improves dropped item performance if your server has thousands of them (from big farms/TNT/farming players etc).

### disableEntityStuckChecks
``Default``: ``false`` Entities don't check if they are stuck in a wall and should suffocate. E.g useful in hubs where player damage is canceled anyway.

### fire-block-physics-event
``Default``: ``true``

### pistonPushLimit
``Default``: ``12`` Just a fun option that enables you to modify the maximum amount of blocks that a piston can push. Together with slime/honey blocks and pushable tiles from Tuinity this allows a lot of new machines/doors.

### fixFallDistance
``Default``: ``false`` 

### fix-protocollib
``Default``: ``true`` Fixes ProtocolLib by preloading ProtocolLib's EnumWrappers.

### log-player-login-location
``Default``: ``true`` Logs every player login location.

# tick:

### enchanting-tables
``Default``: ``false``

# threads: (WARNING: CURRENTLY ONLY ON DEV/THREADED-WORLDGEN BRANCH)

### featuregen
``Default``: ``-1`` Sets how many threads to use, -1 sets to all.

### worldgen
``Default``: ``-1`` Sets how many threads to use, -1 sets to all.

### regionfile
``Default``: ``-1`` Sets how many threads to use, -1 sets to all.

# villagers:

### simplerVillagerBehavior
``Default``: ``false`` Replaces the entire villager AI to the old AI system that all other mobs use. This breaks iron farms/villager breeders/villages (WIP to fix these problems), all villagers get a random profession (if they didn't have one) like in 1.8, don't need nor use workstations and refresh their trades after some time (trades are completely unaffected). This makes villagers as performant as all the other mobs by getting rid of their "brain" (Mojang's name^^) and behavior controller system, instead using the normal goal selector system. This way villagers are over twice as performant, but with the drawbacks that for now Iron farms/villager breeders are broken, so they can just be used for trading systems.

### villagersHideAtNight
``Default``: ``false`` Addon for ``simplerVillagerBehavior``, gives villagers the ability to drink an invisibility potion like wandering traders at night to make it less likely for them to be killed since (for now) they don't stay at the village/use their houses at night and no ability for them to respawn.

# intervals:

### player-time-statistics 
``Default``: ``1`` How many ticks it takes to update the statistics of player. Recommended value is 20 for better performance with the same accurate counting.

# criterion-triggers:

### location
``Default``: ``true`` You should turn this setting off, if You are not using any datapacks that use criterions.

### enter-block
``Default``: ``true`` You should turn this setting off, if You are not using any datapacks that use criterions.

### tick
``Default``: ``true`` You should turn this setting off, if You are not using any datapacks that use criterions.

# checks:

### flight
``Default``: ``true`` Change to ``false`` to disable this check.

### vehicle-flight
``Default``: ``true`` Change to ``false`` to disable this check.

### moved-quickly
``Default``: ``true`` Change to ``false`` to disable this check.

### moved-wrongly
``Default``: ``true`` Change to ``false`` to disable this check.

### vehicle-moved-quickly
``Default``: ``true`` Change to ``false`` to disable this check.

### vehicle-moved-wrongly
``Default``: ``true`` Change to ``false`` to disable this check.

# worlds:

## default:

### disable-observer-clocks
``Default``: ``false`` Change to ``true`` , if You want to disable observer clocks.

### fast-feature-search-dont-load-chunk
``Default``: ``false`` Change to ``true`` , to don't load chunks while using fast feature search. 

### tick-empty-hoppers
``Default``: ``false`` Change this to ``true`` , to tick empty hoppers.

# pigmen:

### dont-target-unless-hit
``Default``: ``false`` If pigmens should target You without being hit.

# collisions:

### players
``Default``: ``true`` If players should collide.

### animals
``Default``: ``true`` If animals should collide.

### ambient
``Default``: ``true`` If ambient should collide.

### monsters
``Default``: ``true`` If monsters should collide.

### villagers
``Default``: ``true`` If villagers should collide.

### pillagers
``Default``: ``true`` If pillagers should collide.

### iron-golems
``Default``: ``true`` If iron golems should collide.

### misc
``Default``: ``true`` If misc should collide.

### items
``Default``: ``true`` If items should collide.

### water-creature
``Default``: ``true`` If water creatures should collide.

### water-ambient
``Default``: ``true`` If water ambient should collide.

# ticks-per:

### full-hopper-cooldown
``Default``: ``128`` How many ticks for full hopper cooldown. 
