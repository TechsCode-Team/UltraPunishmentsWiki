## Commands and Permissions


* **/upun** To open the Punishment GUI
  (Requires ``Any permission that has something to do with the GUI``)
* **/ban (User) (Server) (Time) {Reason}** to ban a player
  (Requires ``ultrapunishments.ban.execute``)
* **/unban (User)** to unban a player
  (Requires ``ultrapunishments.ban.revoke``)
* **/warn (User) (Server) [Kick or Message] {Reason}** to warn a player
  (Requires ``ultrapunishments.warning.execute``)
* **/mute (User) (Time) {reason}** to mute a player
  (Requires ``ultrapunishments.mute.execute``)
* **/unmute (User)** to unmute a player
  (Requires ``ultrapunishments.mute.revoke``)
* **/mutechat** to mute the chat for normal players
  (Requires ``ultrapunishments.mutechat.execute``)
* **/kick (User) {Reason}** to kick a player
  (Requires ``ultrapunishments.kick.execute``)
* **/Freeze (User) (Time) {Reason}** to freeze a player
  (Requires ``ultrapunishments.freeze.execute``)
* **/Unfreeze (User)** to unfreeze a player
  (Requires ``ultrapunishments.freeze.revoke``)

### Symbols and option explanation

* **()** = This feeld is required
* **{}** = This feeld is optional
* **[]** = There has to be choosen on of the options

* **User** This feeld needs to contain a player
* **Server** This feeld is the server the punishment will count for. `all` for all servers and `Server_Name` for a precise server
* **Time** This feeld is the duration of the punishment
* **Reason** This feeld will be the reason of the punishment
* **Kick or Message** `Kick` will kick the player with the warning `Message` Will send a message to the player




<br />

#### Other Permissions
* ``ultrapunishments.manage.templates``
  Allow players with this permission to manage templates
* ``ultrapunishments.manage.settings``
  Allow players with this permission to manage settings
* ``ultrapunishments.report.respond``
  Allow players this permission to respend to reports 
* ``ultrapunishments.mutechat.bypass``
  Allow players this permission to bypass the chatmute
* ``ultrapunishments.manage.exclusions``
  Allow players this permission to manage ban exclusions
* ``ultrapunishments.access.details``
  Allow players this permission to acces the details
* ``ultrapunishments.warning.revoke``
  Allow players this permission to revoke previously issued warnings
