# steamos
 steamOs stuff and fixes


 FAN-FIX.SERVICE

 This file fixes the bug in the Steam Decks fan controller. Currently (27th of April) there is a bug in the new fan controller which resets itself when Deck is put in Sleep mode.
 When the device is waken up, the fan controller won't use the new script to control the fan but just does what it wants.

 INSTALL

 1) Put your deck to Developer mode (so you can use sudo), found in Settings - General
 2) Switch to Desktop mode
 3)  Download (or copy paste the file contents) the fan-fix.service file on your Deck
    - You can use terminal with vim
    - or download KATE text editor from Discover store
 4) Open Konsole app (Terminla) and go to the folder where you downloaded or copy pasted the file
    - for example: cd ~/Downloads
 5) now type: sudo cp fan-fix.service /etc/systemd/

 The service is now in the correct place. Now you have to just start it and enable it to start in every boot:

 In Konsole type:    sudo systemctl --enable fan-fix.service
    
