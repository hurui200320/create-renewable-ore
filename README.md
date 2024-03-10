# create-renewable-ore
A datapack add recipes that allows you to get ores from renewable resources.

Currently tested: 1.20.1 Forge

## Brief

This data pack is inspired by [ilmango's ATFC series](https://www.youtube.com/watch?v=UtmT3qrU04E), where you can get ores from renewable sources like cobblestone. However, I generally don't want to go that hard core in the game, but I still want the renewable ores, so I made this data pack.

## How to use

Clone the project, remove the `-master` suffix and place the folder into your world's `datapacks` folder.

You need Create mod and Biomes O' Plenty mod.

## Added recipes

The recipes need items from Create mod and Biomes O' Plenty mod. Here is an overview of the flowchart:

![flowchart drawio](https://github.com/hurui200320/create-renewable-ore/assets/8587572/e6591820-17c7-4909-9858-deb6e932e4ae)

The black line means the recipe is already in game. The blue line is the newly added one.

There are total 7 new recipes and everything is made to be renewable and automated:

### Crush sand for ores

Some ores are hard to design, so I just use sand for them. There are already a sand washing recipe in the game,
so all I left is crushing. By crushing any sand:

+ 7% chance to get a copper nugget
+ 7% chance to get a zinc nugget
+ 5% chance to get a lapis
+ 5% chance to get a amethyst shard
+ otherwise the sand is consumed

### Press charcoal for coal

By pressing charcoal, you can turn it into coal. Why? Because...

### Press coal block for diamond

Because you need coal block to get diamond. Each time you press a coal block, you have 2% chance to get a diamond.
Otherwise the charcoal block is consumed.

### Mix blood and cobbelstone for crimsite

Pronous flesh and blood are added by Biomes O' Plenty to the nether.
There is a stone called Crimsite added by Create mod and can be crushed into irons and eventually get redstone.
I designed a way to create this type of stone from blood and cobbelstone.

Mixing 1 cobbelstone and 250mBucket blood will give you 1 crimsite back. One bucket of blood is 1000mBucket.

### Mix pronous flesh and water for blood

When the blood touches the water, it will generate a pronous flesh. Just like a cobbelstone generator.
So you can get unlimited pronous flesh. Then you can mix it with 1 bucket of water to get 1 bucket of blood.

Now you get infinite blood!

### Heat pronous flesh for nether rack

I was thinking about how to get ancient debris, I thought it was too OP if I added it. But I actually mine using baritone so it's already OP.

To get ancient debris, you have to get something related to nether. The most common block in nether is of course
the nether rack.

By heating the pronous flesh and wait 10 seconds, you will get a netherrack.

### Wash nether rack for ancient debris

By washing the nether rack, you have a very low chance (0.1%) to get one ancient debris.

## Other Minecraft version

Sadly, I wrote this data pack for my own usage, thus I only tested on my set up. Currently I'm playing on 1.20.1 with Create (Forge). You're welcome to test and adopt this data pack on other versions. Things should be mostly fine considering there is not too dramatical changes.
