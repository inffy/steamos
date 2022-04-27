# steamos
 steamOs stuff and fixes


 FAN-FIX.SERVICE

 This file fixes the bug in the Steam Decks fan controller. Currently (27th of April) there is a bug in the new fan controller which resets itself when Deck is put in Sleep mode.
 When the device is waken up, the fan controller won't use the new script to control the fan but just does what it wants.

 INSTALL

 1) Download (or copy paste the file contents) the fan-fix.service file
 2) Copy/Place it to /etc/systemd/
    
