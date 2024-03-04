# create-renewable-ore
A datapack add recipes that allows you to get ores from renewable resources.

Currently tested: 1.20.1

## Brief

This data pack is inspired by [ilmango's ATFC series](https://www.youtube.com/watch?v=UtmT3qrU04E), where you can get ores from renewable sources like cobblestone. However, I generally don't want to go that hard core in the game, but I still want the renewable ores, so I made this data pack.

## How to use

Clone the project, remove the `-master` suffix and place the folder into your world's `datapacks` folder.

## Added recipes

All recipes are create mod only, which means all you need is the create mod.

### `crush_sand_for_ore`

Crush any kind of sand (including other mod's sand as long as they mark the item as `tag:minecraft:sand`) and you can get almost all of the vanilla ores, plus the zinc ore from create mod.

When crushing one sand:

+ 60% chance you will get the vanilla sand back, no matter what kind of sand you put in
  + by the meaning of "crush", you will get the purest sand after crushing, thus you get the vanilla sand no matter what you put in
  + also I don't know how to return the item you put in so I came up this explanation.
+ 2% chance you will get a crushed raw iron
+ 2% chance you will get a crushed raw copper
+ 1% chance you will get a crushed raw zinc
+ 1% chance you will get a crushed raw gold
+ 0.5% chance you will get a redstone dust
+ 0.5% chance you will get a lapis
+ 0.1% chance you will get a amethyst shard

### `crush_coal_for_diamond`

Crush coal and charcoal can make you diamond with very low chance. This was originally designed for press, but when testing, when pressing the last item in the stack the game always crash. So I changed the type to crush.

When crushing one coal (marked as "tag:minecraft:coals"):

+ 10% chance you will get a coal
+ 0.1% chance you will get a diamond

In real life, you need high pressure and extreme heat to make diamond. But in create, you get pressure from pressing, but heat can only come from the mixing. Mixing support multiple ingredients but mixing coals for diamond is kinda unreal. So I choose the pressing. But pressing is buggy, so I switched to crushing. The theory is that when crushing coal, some point you get high pressure and heat from friction thus you make diamond.

At least that's the best I can get. Contributions are welcome.

## Other Minecraft version

Sadly, I wrote this data pack for my own usage, thus I only tested on my set up. Currently I'm playing on 1.20.1 with Create (Forge). You're welcome to test and adopt this data pack on other versions. Things should be mostly fine considering there is not too dramatical changes.
