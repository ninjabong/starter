hi!
===

![ninjabong](ninjastar.jpg "ninjabong")

my [osxc](http://osxc.github.io) playbook, already forked ! (and in-progress porting from legacy-osxc)

----------

**playbooks/** are mostly a mess of bits that get "- include:"ed in all.yml, as well as used for testing.

----------

**roles/** my custom [osxc](http://osxc.github.io) roles
I've been working on trying to document full options with example playbook use for roles in roles/foo/README.md

-   **computername:** sets the Computer Name normally done via System Prefences \- Sharing.
-   **datetime:** sets time zone, enable/disable network time, network time server and menubar clock options equivalent to System Preferences - Date & Time
-   **desktop\_image** sets the User's desktop picture via [set_desktops.py](https://github.com/grahamgilbert/macscripts/set_desktops/set_desktops.py), supports an image in your starter dir or a http(s) url.
-   **finder\_prefs:** sets a bunch of Finder preferences normally done via Finder's Pref Pane.
-   **gatekeeper:** enable or disable GateKeeper system wide via spctl.
-   **locatedb:** load or unload locatedb via launchctl.
-   **loginwindow:** customizes text to appear on the system and efi loginwindows
-   **sleep:** set various sleep times for Disks, Display, System via systemsetup and pmset.
-   **sshd:** enable or disable sshd via systemsetup.
-   **systemprefs\_general:** sets prefs normally done via System Preferences \- General.
-   **user\_image:** sets the User's local account image
-   **unhide\_library:** unhides ~/Library in Finder.

----------

-   **ninjastar.jpg** is both for this [README.md](README.md) and [user_image role](https://github.com/ninjabong/starter/tree/master/roles/user_image/).
