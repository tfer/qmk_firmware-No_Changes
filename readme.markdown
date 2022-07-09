# Purpose and Use of this qmk fork
No changes in this fork are ever meant to be pushed upstream, though changes upstream are meant to be
fetched.

What the purpose of this fork is provide a enviroment so I can build firmware for my rev 2 Preonic.

You can build the firmware of any of the provided keyboard, as long as it does not depend on any files in a 
branch other than master as that is the only branch included in this fork.

Building firmware is done in unix-like system, i.e.: linux, mac, or wsl.

# Working on your own keyboard firmware
To work on your own keyboard layouts, we pull in your layout files from its own repository as a git submodule.
This isn't done in the main branch, but in a separate branch.
