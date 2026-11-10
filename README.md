This script is to generate icons and set the game name on your system under wayland. using this is not guaranteed to work if you have a weird steam setup, and should only be necessary (and will only work) for RPM steam, and is intended for fedora but may or may not work on other distros.

at worst it will only change the game name from "steam_app_blahblahblah" to the actual game's name on your dock etc, 
and at best will only grant it the low res images steam uses internally in the game list. but it is better than nothing and was the best I could come up with. 
I made this for myself but figured I would release this for others to use in case they had a similar issue. none of the other fixes I found worked, 
and nobody had any worthwhile advice for my issue with fixing this. again, it may be the worst way to go about this, but something is better than nothing to me, 
and at least I can visually see what I am playing or launching now if I want to play through the application launcher or tab out. hope this helps - blxxd

To use the script, download it, cd to the file location (example cd /home/$user/Downloads), and run the command "chmod +x Steam_Icon_Fix_Thing.sh" to make it executable.
Then any time you need to use it, make sure you are in the same directory where it is and run "bash Steam_Icon_Fix_Thing.sh"

Not an elegant coder or developer by any means but it gets the job done. if anyone can do better go for it, this worked for me, would love to see a better version, maybe even one that could get
higher resolution images for the icons, but again, this was my best solution without going out of my way to manually find a bunch of icons for all my games.
