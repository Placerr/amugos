# UltimateVotes [1.13 Spigot / BungeeCord][UUID] 2.1-0756e46
- Native Minecraft Version: 1.13
- Tested Minecraft Versions: 1.8 / 1.9 / 1.10 / 1.11 / 1.12 / 1.13 / 1.14 / 1.15 / 1.16 / 1.17 / 1.18 / 1.19

Ultimate Votes.
The ultimate voting plugin!

Requirements:
- MySql Database. The plugin cannot be used without one!
- WorldEdit min of V5.3.0
- Votifier (standalone server, this is not needed in a bungeecord setup)
- BungeeVote and YAMLer (bungeecord server)
- RedisBungee (Optional)
- Server running latest Bungeecord and Spigot . I do NOT support any lower version. If you purchase this and you are using lower - versions you do so at your own risk.
- Features:
- UUID Support.
- MySql Database tracking of votes (monthly and globally).
- Reward system. (Players are only rewarded once per vote NOT once per server per vote if using a bungeecord installation. This will NOT be changed.)
- Timed commands.
- Percentage chance rewards / lucky rewards.
- Vote milestones. For example reach 10 votes to get rewarded.
- Ability to check in game player votes.
- Top 10 voter list in game.
- Vote spam prevention (BungeeCord).
- Auto reloads top voters at a set interval from the database.
- Auto reminds players to vote every day if they have not.
- Wall of signs to show top 10 voters.
- Offline voting support.
- Per world voting rewards.
- Claim command for players to claim their voting rewards (Optional).
- BungeeCord support. (Optional)
- RedisBungeeCord support. (Broadcast messages to all connected bungeecord instances when a player votes)
- Reward players when they are online.
- Customisable messages.
- Rewards list, view in game what rewards are given for voting (manual not automatic).
- To be implemented:
- Top 5 Daily voters scoreboard.
- Reward top 3 players at the end of the month.
- Web Based interface for rewards. NEW
- special reward after so many <x> votes combined from allvoting players.
- Any suggestions? please ask in the discussion section of this resource.
Developer API:
Want to integrate this plugin into yours? You can do so with the built in developer API class.

JavaDoc available here: https://teoz.jrnetwork.net/ultimatevotesapi/

Instructions:


This wiki page is subject to change in the future.


Player Commands and permissions:
# Commands:
- /vote - Brings up this the vote command menu.
- /vote claim - Claim rewards.
- /vote top - View the top voters this month.
- /vote alltime - View the top voters of all time.
- /vote mtop - View your vote count for this month.
- /vote malltime - View your vote count for all time.
- /vote sites - View the voting website(s).
- /vote about - More about this plugin.
# Permissions:
- ultimatevotes.player.* - Allows the use of all the following permission nodes.
- ultimatevotes.player.info - allows a player to read the info about the vote command.
- ultimatevotes.player.claim - allows a player claim rewards.
- ultimatevotes.player.top - allows a player to view the top monthly voters.
- ultimatevotes.player.alltime - allows a player to view the top all time voters.
- ultimatevotes.player.mytop - allows a player to view their monthly voters.
- ultimatevotes.player.myalltime - allows a player to view their all time votes.
- ultimatevotes.player.sites - allows a player to view the voting sites.
# Admin Commands and permissions:
# Commands:
- /uv - Brings up the command menu.
- /uv reload - Reloads the config.yml and rewards.yml.
- /uv addtestvote <player> - simulate a player voting, this does not reward the player (Adds vote to database on both tables).
- /uv rewardplayer <player> - attempt to reward a player if they have unclaimed votes.
- /uv setwallsigns - set the wall of signs using a worldedit region selection.
- /uv restart - restart the plugin.
- /uv resetmonthly - reset the monthly votes. This CANNOT be reverted!
- /uv checkmonthly <playername> - Check a players monthly vote count.
- /uv checkalltime <playername> - Check a players all time vote count.
# Permissions:
- ultimatevotes.admin.* - Allows the use of all the following permission nodes.
- ultimatevotes.admin.use - Allows a player to use all admin commands
- ultimatevotes.admin.updatenotification - Notifys player of updates to the plugin.
- Individual permission nodes will be added for the admin commands in the future.

# Bungeecord commands and permissions:

# Commands:
- /uvb - brings up command menu
- /uvb addtestvote <player> - add to add a test vote for a player
- /uvb reward <player> - Attempt to reward an online player using bungeecord communication.
- (they need to have unclaimed votes)
- /uvb convert <playername> - get the UUID of a player
- /uvb addtestvote <playername> - add a test vote for a player
- /uvb broadcast <message> - broadcasts a message to all connected bungeecord servers
# Permissions:
- ultimatevotesbungee.admin - Only give to trusted players!
# Compatability:
This plugin is compiled with Bukkit 1.8.8. Bukkit 1.7.10 and 1.8 is known to work ok but may break in the future. Any earlier version may not work and is done so at your own risk, I provide no support for earlier versions. If you are not sure please contact me before purchasing.

# Known Bugs:
There is a bug in the orientation of the sign wall. It does not show the top voters if it is for example facing East or West it will just show the last updated message, You will need to make the wall face North or South for it to work or vice versa.

#Server List Sites:
New to voting? Don't know what voting sites to use?

- Minecraft Server List: http://minecraft-server-list.com/
- PlanetMinecraft: http://www.planetminecraft.com/
- Minecraft MP: http://minecraft-mp.com/
- ServerPact: http://www.serverpact.com/ or http://www.serverpact.nl/
- GameTracker: https://www.gametracker.com/ (not a voting site)
- Minecraft servers:: http://minecraftservers.org
