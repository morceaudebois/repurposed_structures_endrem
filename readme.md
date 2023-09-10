This is a Minecraft datapack for the Fabric versions of [End Remastered](https://modrinth.com/mod/endrem) and [Repurposed Structures](https://modrinth.com/mod/repurposed-structures-fabric). It makes the two mods compatible by making the End Remastered eyes spawn in all their respective repurposed structures.

<h1 align="center">
  <a href="#"><img src="https://raw.githubusercontent.com/morceaudebois/repurposed_structures_endrem/main/datapack.png" width="70%" alt=""></a>
</h1>

## How to install
You can install the datapack by dragging it (uncompressed) in `yourminecraftfolder/saves/yourworld/datapacks`. It differs from mods and ressource packs in the way that it needs to be installed in each world instead of the whole Minecraft instance.

To know if it's installed properly, you can enter the command `/datapack list` and you'll see your whole list of datapacks installed (make sure to enable cheats first or the command won't work).

You can learn more about datapacks [here](https://minecraft.fandom.com/wiki/Tutorials/Installing_a_data_pack).

## Random stuff to know

I *think* the weight/spawn rates are accurate. They might need to be lowered for balance, as there will be more structures in the world. I'm open to pull requests if you think you can do it better!

I decided to not make the following eyes spawn:
- Nether Eye in Jungle Fortress (it's.. not a Nether structure)
- Cursed Eye in Underground Bastion (same reason)
- the Cold Eye can spawn in repurposed igloos, but I lowered the spawn rate

## Compatibility
As far as I understand, datapacks aren't compatible with each other. They don't simply add to the default loot tables, they completely override them. This means you'll probably run into issues if you have an other datapack installed that edits the same loot tables.