# ItemStacksandWeight Plugin for Valheim

#####This is not my mod!!! i only updated it and re-uploaded all credit goes to MTNewton!!!#####


Increases item stack size (10x by default) and item weight (x0.1 by default).

Loading up a world without the mod installed or reducing item stack size will cause any items in a stack above the new stack size to be lost.

Configuration entries are generated based on the items in the ObjectDB instance.  
You must join a world for it to create the individual item config entries.

You may choose to enable/disable the stack size or weight modification by setting the respective enabled flag.

Item weights and stack sizes can be individually set, setting these values above 0 will have it ignore the multiplier and use the given value instead.

## Installation
1. Download and install [BepInEx Valheim](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
2. Download this mod and move the `ItemStacks.dll` into `<GameLocation>\BepInEx\plugins`
3. Launching the game and joining a world will generate a config file at `<GameLocation>\BepInEx\config`

## Configuration
`<GameLoacation>/BepInEx/config/Bjornheim.ItemStacksandWeight.cfg`
```
[ItemStacks.ItemMultipliers]

## Multiply the original item stack size by this value
## Minimum resulting stack size is 1
## Overwritten by individual item _stack_size values.
# Setting type: Single
# Default value: 10
stack_size_multiplier = 10

## Multiply the original item weight by this value
## Overwritten by individual item _weight values.
# Setting type: Single
# Default value: 0.1
weight_multiplier = 0.1

[ItemStacks.ItemStackSize]

## Should item stack size be modified?
# Setting type: Boolean
# Default value: true
enabled = true

## Set above 0 to use this value instead of the stack size multiplier
## Game default: 20
# Setting type: Int32
# Default value: 0
amber_stack_size = 0

## Set above 0 to use this value instead of the stack size multiplier
## Game default: 50
# Setting type: Int32
# Default value: 0
amberpearl_stack_size = 0

...

[ItemStacks.ItemWeight]

## Should item weight be modified?
# Setting type: Boolean
# Default value: true
enabled = true

## Set above 0 to use this value instead of the weight multiplier
## Game default: 0.1
# Setting type: Single
# Default value: 0
amber_weight = 0

## Set above 0 to use this value instead of the weight multiplier
## Game default: 0.1
# Setting type: Single
# Default value: 0
amberpearl_weight = 0

...
```

## Changelog
- 
- v1.0.0
    - initial mod Re-upload
    - configurable item stack size and item weight (defaults to 10x base item stack size and 0.1x item weight)

## Source Code
https://github.com/mtnewton/valheim-mods/tree/master/ItemStacks
