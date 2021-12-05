# Datapack template
Basic datapack template for Minecraft 1.16/1.17/1.18

# Installation
Download the source and extract it in the `datapacks` folder in your world directory.

# Loading the datapack
When your datapack is located in world's `datapacks` folder, simply run in-game `/reload` command. It will load your datapack in to your game. 


# Events
JSON Files in `./data/minecraft/tags/functions` contain list of functions which are ment to autorun at a certain event.
For example `load.json` defines list of functions which are fired when the datapack is loaded.

This file should be structured like this,
```json
{
	"values": [
		"datapack:load"
	]
}
```
where *datapack* is name of the folder located under `data`, and *load* is name of your function.