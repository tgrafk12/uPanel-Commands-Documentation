# UPanel Commands

Here you can find a list of commands and definitions of each UPanel commands.
(The commands should be self explainitory, but we decided to make a visual list)

> [!NOTE]
> Copying the commands listed here will not work alone! You will need to fill in the information inside the '< >' or '[ ]' manually to use the commands. Only ONE value can be used when a command has ' | '.
> For example, '/ban Nala|1234567891011' will not work, only one value is required for the command to work.

> [!IMPORTANT]
> Commands with '< >' Require a value for the command to work.
> Commands with '[ ]' do NOT require a value to work. 
> A valid command looks like this '/ban Nala' or '/ban 1234567891011'

## Ban

    /ban <player name | SteamID> 

> Bans a player on your server/network



## Check Owner

    /checkowner
    
> Checks the owner of the current structure/barrier that you are looking at. (Values return in “ugo” see UGo command for more details)



## Discord

    /discord
    
> Creates a popup for the user to join the configured discord invite from https://upanel.one/dashboard


## Glitch

    /glitch
    
> Teleports the user to any glitched structures or buildings on the current server.


## Kick

    /kick <player name | SteamID> [custom-reason]
    
> Kicks a user from your network.


## Link
 
    /link
    
> Displays a popup to the user to link their account to uPanel. Requires a Discord account and Steam Account


## Mute
    
    /mute <player name | SteamID> [reason] [duration] [global|-g]
    
> Prevents a user from speaking in chat for a set duration. Can be set for other servers you own on your network via “Global” 


## Report
 
    /report <player name | SteamID> [reason]

> Reports a user to the Admins of the server. Reports can be put into a configurable channel in your Discord server that you set up.


## Stats
 
    /stats <user>

> Doing this command, will give you stats for the player you are currently playing on. Admins can use this command with an optional player name at the end of the command to get that user's stats.


## UConfig

    /uconfig <generate | migrate> [api key] [server id]

> Configures UPanel to your server

## UGo
  
    /ugo <build-number/identifier>
    
> Teleports the user to that object. You can find the UGo identifier in the uPanel Building logs set up in your Discord Server or by doing [/checkowner](README.md#check-owner)


## Unban
 
    /unban <player name | SteamID>
  
> Unbans a player from your server/network. (Does not apply to players that have been Oversight Banned)


## Unmute
 
    /unmute <player name | SteamID>
    
> Unmutes a player from your server/network


## UPanel
 
    /upanel <connect | disconnect | reconnect> <force>
    
> “Force” the plugin to connect to uPanel servers if stuff is not working properly.


## Warn

    /warn <player name | SteamID> [custom-reason] [global | -g]
    
> Warns a player on your server/network. (can be globally muted or per server)


## Warns
 
    /warns <player name | SteamID>
    
> Gets a list of all warns for that player in your network.
