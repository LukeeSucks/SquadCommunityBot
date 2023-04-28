
# Detailed Command List for SCB
## Help Command (/help)
The help command's sole purpose is to help users find all the commands for the bot. All users can use this command, and it will call a Discord embed with all of the commands the bot has. It is detailed in a simple format that is informative without becoming over-cluttered.

![help](https://user-images.githubusercontent.com/130908195/235119189-5298a8b6-4ec1-4b90-9ff7-ec3173cbf73a.png)

## Map Help (/maps)
The maps command will simply call an embed that allows you to view all maps in the game and their call command. This allows you to view more details of a specific map and layer that you choose.
For example, triggering the command for game map Sumari using "/sumari" will bring up a Discord drop menu with each and every layer for the Sumari map. Users can choose which layer they desire to look at. Once the desired layer is chosen, it will send a singular image. This image contains the following details of the layer:
- Flag image of each team
- Image of the map and its capture points, if applicable
- Every vehicle both teams have
- Spawn delays of each vehicle, if any
- Amount of each vehicle
- How many tickets each team starts off with

![maps1](https://user-images.githubusercontent.com/130908195/235119345-66ab5323-0f60-4221-9c95-112280a13e51.png)
![maps2](https://user-images.githubusercontent.com/130908195/235119350-84f3ff84-8611-42b1-9cf2-55466974e11b.png)

## Factions Help (/factions)
This command, once called, will send a Discord drop menu with every faction in the base game. Once the user selects which faction they desire to see, it will send an embed containing the following information:
- Image of the faction with its flag
- The kits/loadouts usable by the faction
- The faction's weapons
- The faction's grenades and launchers
- The faction's vehicles
- The faction's emplacements

![factions1](https://user-images.githubusercontent.com/130908195/235119587-6d8fbd7f-f3b0-42a6-bdc4-e785fc8b94ea.png)
![factions2](https://user-images.githubusercontent.com/130908195/235119592-e6161f59-7243-4744-8d1f-0965deb4774c.png)

## Vehicle Statistics (/vehiclestats)
This command will bring up a Discord embed with all the vehicle types and their corresponding calling command. For example:
- Transport (/transportstats)
- Main Battle Tanks (/mbtstats)
- Infantry Fighting Vehicles (/ifvstats)
Once one of these commands is called, it will send a Discord drop menu with each vehicle of that type. Once a user selects which vehicle they would like to view, it will send an embed. This embed will contain the following information of the vehicle:
- An image or hotbox of the vehicle
- Name
- Description
- Icon
- Ticket value
- Killer point reward
- Construction resources
- Ammo resources
- Total resources
- Seat count
- Spawn command
For each gun on the vehicle:
- Gun name
- Number of mags
- Mag size
- Time between shots
- Time between single shots
- Tactical reload duration
- Projectile
- Max damage to apply
- Armour penetration

![vehiclestats](https://user-images.githubusercontent.com/130908195/235119747-c3e5ecce-c59f-4d45-aae0-23fa40512a80.png)
![vehiclestats2](https://user-images.githubusercontent.com/130908195/235119753-5c3535a0-294a-4ccb-acfc-2f2802d0f6f9.png)

## Vehicles (/vehicles)
This command will give a drop menu of each vehicle type in the game. Once the user selects which type of vehicle they want, it will send a Discord embed with every vehicle that falls under that category with its corresponding map icon. This helps reduce incorrect marking on the map by newer players.

![vehicles](https://user-images.githubusercontent.com/130908195/235119864-53d73933-6783-4728-9aa5-41a074153df9.png)

## Icon Legend (/iconlegend)
This command will send a singular image that contains every single kit icon, vehicle icon, and structure icon you may see on the map. It tells you what each one is, allowing newer players to recognize, understand, and correctly mark everything on the map. It also tells the user how many tickets are lost for each action that happens in the game.

![iconlegend](https://user-images.githubusercontent.com/130908195/235119927-87501314-88cd-4cb7-875f-d1ad6614ac7b.png)

## Bot Assets (/botassets)
This command will allow users to download all assets used by the bot all in one place for their own projects, helping them save time finding/making them themselves. This contains:
- Images of maps
- Images of every vehicle
- Hitbox image of applicable vehicles
- Team flag/team images
- Map icons
- Kit icons

![botassets](https://user-images.githubusercontent.com/130908195/235119983-dba15885-78bf-4645-837d-f2f334077329.png)

## Server Status WIP ( /serverstatus [name] )
This is a work in progress command that allows users to search for their desired server using the Battlemetrics API and find information on their server without having to load up the game from the comfort of Discord. This command is being improved to make searching for the user's server more accurate. The Discord embed will contain the following information of the server:
- Server name
- Server status
- Server players
- Server map
- Server game mode

![serverstatus](https://user-images.githubusercontent.com/130908195/235120026-acaf191b-4ce0-4b7d-8133-8f7abece322d.png)

## Report / Suggestion Help ( /reporthelp // /suggestionhelp)
These commands will allow users of the bot to report an issue or suggest an improvement to the bot developers, with a chance to describe the problem or suggestion so that the developers are able to work on or fix the task at hand. This allows users to help improve the bot and ensure that it is always working correctly and accurately at all times.

![report](https://user-images.githubusercontent.com/130908195/235120089-ac04cace-d563-4869-9ff7-adf74a64a789.png)
![suggestion](https://user-images.githubusercontent.com/130908195/235120105-6eefe4e9-7e9b-4511-bf14-f9b0b3cdca4f.png)

## Information ( /info )
This command allows users to get a brief idea of what the bot is and its history. It also allows users to see who the developers behind the bot are.
Overall, this is a detailed list of commands for the SCB bot, providing users with easy access to information about maps, factions, vehicles, and server status, among others. Additionally, users can report issues or suggest improvements to the bot developers and learn more about the bot itself.

![info](https://user-images.githubusercontent.com/130908195/235120116-7e18b31d-7ef1-4bd8-83c5-e95318867b5b.png)
