## The Odin Project ##
05/01/26 Setting Up Dev Environment with Linux Mint & VSCodium, painfully, Ubuntu issues in VirtualBox slowed this down.
Uninstalled flatpak version of VsCodium, reinstalled with terminal commands
Practicing navigating and editing files with the terminal

06/01/26 More time spent setting things up, reading through basic html setup

07/01/26 Running through HTML basics. Learnt about page anchors and link hijacking security! Everything else was a repeat, but good to go back to basics.

Some Linux terminal commands:
touch abc.txt # makes a file
codium abc.txt # opens a file in VS
mkdir abc # makes a folder
cd .. # goes up a folder
mv abc.txt abc # moves abc.txt into abc
mv abc.txt .. # moves abc.txt back into parent folder
cd ~ # navigates back to base directory

22/01/26
Working through CSS excercises slowly.
Inspector in dev tools shows padding/margin/border under the box model.
display:block; is default for most elements in browser. Things like div, parapraphs etc.
display:inline; for anchors, span etc. but can also be used to group containers without moving to the next line
display:inline-block; captures the best of both worlds, will appear on the same line as other inline or inline-block elements but functions as a block for width/height, padding/margins etc.
content > padding > border > margin
["*"] wildcard can be used to apply style to every matching property, or every element if used on its own
margin-left:auto; will move content to the rightmost edge, reverse for right,top,bottom
