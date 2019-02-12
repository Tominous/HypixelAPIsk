# HypixelAPIsk

# What does this Skript do?
Basically, it just gives a few lines of code to get the info from the Hypixel API (https://api.hypixel.net) and store it in a list variable ({_results::*}). You can then get any value from the API through this variable.
e.g. If a player has MVP++, {_results:: Player::monthlyPackageRank} will be "SUPERSTAR"

# How do I use it?
I included an example command which will reply with the rank of a player.
You can use it by doing '/hypixelranks <IGN>' (e.g. /hypixelranks Sk1er).
It should hopefully give you an idea of how to use the API to get basic information about a player.

# Configuration
Just put the .sk file in your scripts folder, open in in your favorite skript editor (I use Sublime Text and Notepad++) and put your API key in the APIKey option

# Dependencies

Skript (of course), Reqn and skript-json

# Downloads

Skript:
Minecraft 1.9+: https://github.com/SkriptLang/Skript/releases/download/dev36/Skript.jar                                 
(It may work with 1.8, but I will not provide support for it)                                
Reqn: https://forums.skunity.com/resources/reqn.95/                                  
Skript-JSON: https://forums.skunity.com/resources/skript-json.151/
