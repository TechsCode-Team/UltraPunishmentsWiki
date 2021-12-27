# Welcome!
Welcome to the Wiki page of Ultra Punishments, where you can find all the information and documentation. You can navigate the wiki using the sidebar on the right.
<br>

## Contact
You can communicate with our support team by joining our **[Discord](https://discord.gg/3JuHDm8)**. It is the only way we can give you support once you have verified your purchase.
<br>

## What can you find on the wiki?
- [Commands](/wiki/overview#commands) - The list of commands
- [Permissions](/wiki/overview#perms) - The list of permisisons
- [Installation Guide](/wiki/installation) - A quick guide on how to install Ultra Punishments
- [Features](/wiki/features) - A list with all the features of Ultra Punishments
- [API](/wiki/api) - A guide on how to use the API for developers
<br>
<br>

# Commands {#commands}
Here is a list of all the commands that can be used.
<br>

* `/upun`
  To open the Punishment GUI
* `/ban <User> <Server> <Time> [Reason]`
  To ban a player
* `/unban <User>`
  To unban a player
* `/mute <User> <Time> [Reason]`
  To mute a player
* `/unmute <User>`
  To unmute a player
* `/freeze <User> <Time> [Reason]`
  To freeze a player
* `/unfreeze <User>`
  To unfreeze a player
* `/kick <User> [Reason]`
  To kick a player
* `/warn <User> <Server> <Kick|Message> [Reason]`
  To warn a player
* `/clearchat`
  Clears the entire chat for everyone
* `/mutechat`
  To mute the chat for normal players
  <br>

## Symbols:
- <> = Required
- [] = Optional
<br>
<br>

# Permissions {#perms}
Here is a list of all the permissions that can be used
<br>

* `ultrapunishments.admin`
  Allows access to `/upun`
* `ultrapunishments.ban.execute`
  Allows to ban a player
* `ultrapunishments.ban.revoke`
  Allows to unban a player
* `ultrapunishments.mute.execute`
  Allows to mute a player
* `ultrapunishments.mute.revoke`
  Allows to unmute a player
* `ultrapunishments.freeze.execute`
  Allows to freeze a player
* `ultrapunishments.freeze.revoke`
  Allows to unfreeze a player
* `ultrapunishments.kick.execute`
  Allows to kick a player from the server
* `ultrapunishments.warn.execute`
  Allow to issue warnings
* `ultrapunishments.warn.revoke`
  Allow to revoke previously issued warnings
* `ultrapunishments.chatclear.execute`
  Allows the clear the chat for everyone
* `ultrapunishments.mutechat.execute`
  Allows to mute the server chat
* `ultrapunishments.manage.templates`
  Allow to manage templates
* `ultrapunishments.manage.settings`
  Allow to manage settings
* `ultrapunishments.manage.exclusions`
  Allow to manage ban exclusions
* `ultrapunishments.manage.details`
  Allow to manage the details
* `ultrapunishments.report.respond`
  Allow to respend to reports
* `ultrapunishments.mutechat.bypass`
  Allow players this permission to bypass the mutechat
* `ultrapunishments.broadcaster.recieve`
  Allows players to see the punishment broadcast message
  <br>

# Placeholders
Below is a list of all available placeholders. Keep in mind these placeholders require **[PlaceholderAPI](https://www.spigotmc.org/resources/6245/)** & a plugin that supports the API!
<br>

#### Main Placeholders
* **`%upun_player_bans%`**
  Shows current user ban amount
* **`%upun_player_mutes%`**
  Shows current user mute amount
* **`%upun_player_reports%`**
  Shows current user report amount
* **`%upun_player_freezes%`**
  Shows current user freeze amount
* **`%upun_player_punishments%`**`
  Shows current user all punishment amount
* **`%upun_player_isPunishable%`**
  Shows (`True`/`False`) if current user is punishable
* **`%upun_player_isMuted%`**
  Shows (`True`/`False`) if current user is muted
* **`%upun_player_isBanned%`**
  Shows (`True`/`False`) if current user is banned
* **`%upun_player_isFrozen%`**
  Shows (`True`/`False`) if current user is frozen
* **`%upun_player_banDuration%`**
  Shows how long current user ban duration is
* **`%upun_player_freezeDuration`**
  Shows how long current user freeze duration is
* **`%upun_player_muteDuration%`**
  Shows how long current user mute duration is

#### Format Placeholders
* **`{id}`**
  Shows the id of the punishment
* **`{PunishmentDate}`**
  Shows the date the punishment was issued.
* **`{PunishmentTime}`**
  Shows the time of the punishments when issued.