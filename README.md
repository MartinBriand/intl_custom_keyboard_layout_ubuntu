Here is what the install programm does:

* Replace the "Compose" file of /usr/share/X11/locale/en_US.UTF-8 with the one of the folder.
* Replace the "us" file of /usr/share/X11/xkb/symbols with the one of the folder.
* Replace the "evdev.xml" file of /usr/share/X11/xkb/rules with the one of the folder.
* Append the "environment" file of the folder to /etc/environment

Note that for the last step, it adds to lines to the environment, it might be that those lines are already present. Check it before running the script or you will get duplicated lines.
