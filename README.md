# OpenCraftDocs
## Modding
### Objects
An object is anything in game. a Block, an Item, an Entity, a Spell, etc.
here is a list of all the Objects:
* Block
* Item
* Entity
* Spell
* Trade
* Skill
* Class
* Recipe

### Traits
Traits are a way how to give objects proporties.
#### Items
* IEnergyStorage
Anything that stores, generates or consumes energy.
* IManaStorage
Anything that stores, generates or consumes mana.
* IPlantable
Anything that can be planted.
* IArmor
Anything that can be weared as armor.
* IBauble
Anything that can be weared as an accessory.
* IBurnable
Anything that can be burned in a furnace.
* IBurnHeatable
Anything that can power a furnace.
* IEnchantable
Anything, that can be enchanted
* IValuable
Anything, that can be traded.
* ITransmutable
Anything, that can be transmutated.

#### Blocks
* IBreakable ***(DEFAULT)***
Anything that can be broken.
* IInsulator
Anything that can stop any amount of heat.
* IRedSignal
Anything that creates, or checks for, red signals.
* IBlueSignal
Anything that creates, or recives, blue signals.
* IGlowing
Anything that makes light.
* IOre
Anything that can be considered a ore.
* IUnbreakabale
Anything, that in any point, can not be broken.
* IPlant
Anything that grows, by modifing its state.
* IMultiPlant
Anything that grows by changing surrounding blocks.
* IHasRecipe
Anything that processes something. 
* IEnergyStorage
Anything that stores, generates or consumes energy.
* IManaStorage
Anything that stores, generates or consumes mana.
* ITool
Anything, that changes how blocks are mined.
* IWeapon
Anything, that can attack enemies.
* IItemStorage
Anything, that stores items.
* IMultiPart
Anything, that allows other multi parts to coexist in the same block space.
* IHeating
Anything, that heats its surroundings.
* ICooling
Anything, that cools its surroundings.
* IPolluting
Anything, that pollutes its env.
* ILiquid
Anything, that is a liquid.
* IGas
Anything, that is a gas.
* IMultiBlock
Anything, that can form a multiblock.
* IHanging
Anything, that hangs from two points, connecting them in some way.
* IConnected
Anything, that is connected from 3 or more points, forming a surface.
* IChiseable
Anything, that can be chiseled.
* IDynamicModel
Anything with a dynamic model.
