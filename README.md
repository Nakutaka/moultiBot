# MoultiBot

MoultiBot is a currently private Discord Bot used to perfom a variety utility commands.
Started on 11/08/2020.

## What can it does ?

The `time` command followed by the name of a city (mainly capitals) gives its current time.\
The `aled` command displays the main help message of the app.\
The `dice` command rolls a dice.\
The `duel` command followed by the @ (tag) of a user set up a duel between the user who type the command, and the tagged one.

### "Technical" specs

#### Time command
The full list of supported cities can be found [here](./timeZonesList).\
Accents are supported, and you are not forced to follow the exact spelling of the list.\ 
Example of spellings that work:\
`!time paris`  
`!time Los angeles`  
`!time SEOUL`  
`!time hong_kong`

#### Aled command
You can add the name of a command to get its help page.\
i.e `!aled time`

#### Dice command
Just type `!dice`.

#### Duel command
After starting a duel with `!duel`, the 2 users will have to type the dice command in the chat.
After 2 rolls or that 1 minute has passed, the duel ends.
