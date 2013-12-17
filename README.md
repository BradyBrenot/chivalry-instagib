chivalry-instagib
=================

Any tiny bit of damage causes a character to explode. Fun for the whole family.

This mod is provided as an example of a code mod that: 
- uses includes to reduce code duplication 
- uses a config file for easy server setup 
- uses localized strings to allow for translation 

Feel free to reuse this example or any parts of it, the whole point of this is to provide an example for modders. Just rename any derivative mods to something else to avoid confusion.

=================

In the Steam Workshop: http://steamcommunity.com/sharedfiles/filedetails/?id=202422398

=================

Using the .cmwsdk file from the Workshop, or after compiling and cooking this mod locally (setting the "modname" to "instagib"):


Start a server with ?modname=instagib on the command line (appended to the map). For example:

UDK.exe aoctd-frigid_p?modname=instagib ...

=================

You can specify the mod you'd like to use in the maplist as well (in PCServer-UDKGame.ini), allowing you to switch between mods if you want. For example: 

Maplist=aoctd-frigid_p?modname=instagib 

Maplist=aoctd-moor_p?modname=someothermod 

================= 

If you want to play offline, just use the 'open' console command, again appending ?modname

open aoctd-frigid_p?modname=instagib
