This repo contains .cfg scripts with various purposes for Source engine games.

# How to install and use

Head to the directory ***<gameinfo.txt location>/cfg*** and drop script there. Run the script from in-game with ***exec*** command.

# gameinfo.txt directory names

+ Half-Life 2: **hl2**
+ Portal: **portal**
+ Portal 2: **portal2**
+ Black Mesa: **bms**

# Script purposes

+ *break*

  Breaks everything that is breakable except physics props as doing so causes NO_FREE_EDICTS crash on big maps.

+ *earthquake*

  Simulates an earthquake, making screen shake and objects fly around, becoming deadly projectiles.

+ *explodeatpicker*

  Generates a deadly explosion at location where player is looking at.

+ *golimp*

  Makes every NPC collapse on the spot. Lighter version of *killall*. Optional dependency: *unbreak*

+ *killall*

  Kills every NPC and prevents game from reloading in case essential NPCs die. Optional dependency: *unbreak*

+ *propsexplode*

  Makes every prop explode instantly. May cause crashes.

+ *qol*

  Various quality of life improvements such as bigger, stronger flashlight, no auto view adjustment while in vehicle, infinite suit power.

+ *ranoutofscrews*

  Break every connection between physics objects. Lighter version of *break*.

+ *repellant*

  Repel every physics object and kill NPCs close to player.

+ *trojanbomb*

  Make every breakable physics prop explode if broken.

+ *unbreak*

  Fix softlocks caused by *killall* and *golimp* scripts. Work in progress.
