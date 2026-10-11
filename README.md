Introducing Guardianblocks!

-----

Adds a Guardian Block block to the game! Depending on what item is inside, it will do various different functions for base protection!

-----

This mod was a crucial cornerstone of a server I used to play on as a kid back in b1.7.1 through shortly after 1.0. The server was called Minecarts.net, owned by Verrier and Megabytes. When that server closed its doors for good, it left a gaping hole in the hearts of everyone who was active on that server, including me. It's been my life passion to recreate this mod to the best of my ability ever since. I did make one change from how it was before, since before it used the "Block of [X]" directly and recorded a GBID to manage it. I feel like the way it's done now is more modernized, creating a whole new item but keeping the game balance and functionality the same. The new block is acquirable pretty early in the game, but the resources it requires to function will still increase the budget for materials to fully protect your base. The idea is that you will need multiple Guardian Blocks to fully cover your entire base, and planning your build will require careful consideration of placement and cost, while still feeling incredibly vanilla and like this block fully belongs in Minecraft.

This has been one of my life passions and life goals to accomplish, and I'm incredibly close to completing it. I'm close enough that I can die happy knowing this mod is now out there and now exists, but not close enough to deploy it in any reasonably public server (unless you don't care about lava/fire griefing).

-----

___Items___

- No item/Wrong item: Inactive, does nothing.

- Block of Iron - Protects blocks from being placed or broken by players, creepers, endermen, or TNT in a 9x5x9 cube centered around the block.

- Block of Gold - Protects blocks from being placed or broken by players, creepers, endermen, or TNT in a 17x7x17 cube centered around the block.

- Block of Diamond - Protects blocks from being placed or broken by players, creepers, endermen, or TNT in a 25x9x25 cube centered around the block.

- Block of Netherite - Protects blocks from being placed or broken by players, creepers, endermen, or TNT in a 41x13x41 cube centered around the block.

- Block of Emerald - Protects containers from being opened in a 9x9x9 cube centered around the block.

- Block of Redstone - Protects buttons, levers, and doors from being activated in a 9x9x9 cube centered around the block.

- Block of Lapis Lazuli - Protects mobs from being damaged by unauthorized players as well as prevents hostile mobs from spawning in a 9x9x9 cube centered around the block.

-----

___Crafting Recipe___

8 Chiseled Stone Bricks in a circle on a crafting table, like a chest.

-----

___Commands___

/gb add [PlayerName] = Adds another player to bypass the protections of the Guardian Block you are actively looking at.

/gb remove [PlayerName] = Removes a player from the list of allowed players from the Guardian Block you are actively looking at.

/gb list = Lists all players allowed to bypass the protections of the Guardian Block you are actively looking at.

-----

___Operator/Moderator/Staff notes___

Staff bypass is attached to Creative Mode. If you need to intervene with the usage of Guardian Blocks, simply being in Creative Mode will automatically bypass the protections and allow you to do what you need to do.

-----

___To-Do___

- Still need to protect against liquid griefing. MCreator 2026.2 doesn't make this easy, and I'm not comfortable enough with java coding to make this happen on my own. I'm uploading this to github so that hopefully anyone smart enough can help finish this mod for me. Because it's entirely possible to build a 1 wide dirt bridge over someone's base, and dump lava to spread down over top of it, and that is definitely something I want this mod to prevent with this mod.

- Same as above with fire spread/fire tick.

- Maybe add the ability for server operators to "click and drag a corner" to extend the range of a single guardian block if they choose to? That might not be so lightweight and might be way more complicated. This one's a hard maybe.

-----

___Does NOT protect___

- Lava/Water/Using Buckets (as of 0.9.1, I hope to have this fixed ASAP with Iron, Gold, Diamond, and Netherite tiers)

- Explosions still damage entities within a Lapis tier Guardian Block's range, this is intended. Take better care of your pets!

- Placing Guardian Blocks __while in creative mode__ does NOT assign an owner tag in NBT, meaning nobody can bypass it except people in creative mode. This is intended, makes for good server spawn locations.

- Pressure Plates, Wooden Gates, and Skulk Sensors still work within a redstone Guardian Block's radius. This is intended, so that spawn areas or player-created public spaces can still feel interactive instead of completely locked down.

-----

Added both compiled .jar file to Releases, and the sharable .zip to use in MCreator 2026.2. I don't care what happens or changes with this mod, I just wanted it to exist. Just don't sell it.
