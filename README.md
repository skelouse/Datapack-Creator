## Minecraft DataPack Editor

> This is a datapack editor for making live edits IN GAME, and saving those to a file on desktop
> * **Steps:**
> * Build GUI
> * Build in game map viewer and generator
> * Talk to other datapack generator creators to see if they want to join in
> * Add crafting recipe GUI
> * Add function creator GUI (Tutorials and examples throughout)
> * Add block and creature drawing GUI
> * Add loot table GUI
> * Add Advancement editing GUI
> * Add Structure editing GUI
> * Add Tags GUI


### Functional Goals
> * Gui Editing
> * Viewing map overview for generator
> * Crafting recipes
> * Function Creator
> * Block, and creature drawing
> * Advancement editing
> * Loot table editing
> * Tags
> * Structures


#### Build new GUIs
> Actually use this to build our GUIs for this.


#### Overviewer
https://github.com/overviewer/Minecraft-Overviewer
> Live editing of the surface and biome generator, then sending that created map to the overviewer for analyzing.
> * Also for dimensions
> * Try to keep it as simple as possible
> * Render on disk, but not actually in the game
> * May need to send to the overviewer api


#### Crafting recipes
 > Have a facade GUI crafting table and nei like side bar for placing items into the table, and submitting a crafting recipe


#### Function creator
https://minecraft.gamepedia.com/Function_(Java_Edition)
 > Build a code editor for minecraft for live editing and testing of different functions


#### Block and creature drawing and creation
> Build a system for editing blocks in game, different controls for actually changing colors of blocks, and adding new pieces and dimensions to that block.  Saves the given block in correct folder


#### Advancement editing
> possibly a GUI overlay of the advancement table for dragging and dropping the new advancements into a specific location


#### Loot table editing
> Have a gui for editing loot table, click different things to replace vanilla like mobs, chests etc, and create new if you want to build your own structure


#### Tags
> tbd


#### Structures
> Incorporate a worldedit like copy and paste to actually paste that into a custom structure, include mobs.  Ability to add chests, and loot tables to those chests. 
> * a way to freeze mobs for placement in a structure
> * World edit clone for simply copy and paste
> * Ability to edit all structures, size, quantity, etc
> * Ability to visualize a structure in the overviewer


#### Links
> * https://minecraft.gamepedia.com/Category:Data_packs
> * https://minecraft.gamepedia.com/Tutorials/Creating_a_data_pack


#### Pypi repos ( Python development )

For building packs
* https://pypi.org/project/mcpack/

For pulling items, mobs, and vanilla things from minecraft
* https://pypi.org/project/nbtlib/

For editing packs
* https://pypi.org/project/onyx-mclib/

For reference
* https://www.metroite.de/
* https://github.com/ImCoolYeah105/Datapack-Utilities


