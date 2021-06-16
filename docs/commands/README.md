# Commands
A complete list of all the commands in **Dyphae** and how to use them... yay
<br>

## /say
- Description: **Say something in the chat**
- Usage:
`Command.say(String message)`
- Example:
`Command.say("Oh hello there Mr Dumb Dumb Face!")`

## /give
- Description: **Give a player/s stuff**
- Usage:
`Command.give(String selector, String item, int amount)` or `Command.give(String selector, String item, String nbt, int amount)`
- Examples:
`Command.give("@a", "minecraft:diamond", 1)`, <br>
`Command.give("@r", "minecraft:netherite_hoe", "CustomModelData:12", 69)`

## /seed
- Description: **Returns the worlds seed**
- Usage:
`Command.seed()`
- Example:
`Command.seed()`

## /reload
- Description: **Reloads all datapacks in the world**
- Usage:
`Command.reload()`
- Example:
`Command.reload()`

<br>
<br>
<br>

***Documentation generated using [Docsify](https://docsify.js.org/#/)***