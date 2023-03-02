# bot-mind

This is my main project for Dual Universe.

Bring more life in DU!

# What is it?
This is the "frame system" for player made bots or characters (NPC). There are two types Static and Dynamic.

# bot-static
This one is like the person who meet you on building entrance, or seller at the counter, or "AI" helper on the ship.
![image](https://user-images.githubusercontent.com/125310231/222529677-663aaec7-1787-43a2-bf7d-f4fb556eb225.png)
![image](https://user-images.githubusercontent.com/125310231/222532163-b5939fdb-a9f2-4ecd-b914-f59b48ce902c.png)

# How to install (static):
Require: program board, screen for face, (optional) second screen for lua menu, databank, (optional) second program board for html HUD.
1. Copy all what inside file "bot-static-MIND-v*.conf"
2. In game RMB on FIRST program board -> Advanced-> Paste lua configuration from clipboard
3. Connect first screen in "screen_face" slot.

![image](https://user-images.githubusercontent.com/125310231/222538628-3526e26a-9061-4d89-b03b-a16d06ea215a.png)

5. Connect second screen in "screen_menu" slot. OR in "Edit lua parammeters" turn off "useMenuScreen".

![image](https://user-images.githubusercontent.com/125310231/222540005-6da3a298-6f6f-4cf6-9fde-81f24ae28fcd.png)

7. Connect databank in "databank" slot.
8. Copy all what inside file "bot-static-HUD-v*.conf"
9. In game RMB on SECOND program board -> Advanced-> Paste lua configuration from clipboard
10. Connect databank in "databank" slot.
11. (Optional) You can connect detection zone to activate First program board by signal, but Second PB only by hand because: setScreen(content)(Note that this function is disabled if the player is not running the script explicitly (pressing F on the Control Unit, vs. via a plug signal).)

# How to use.

![image](https://user-images.githubusercontent.com/125310231/222546046-022dc10a-24f6-4eef-b7e3-4e683d809c70.png)

# bot-dynamic
-work in progress-
# How to install (dynamic):

