## The Odin Project ##
05/01/26 Setting Up Dev Environment with Linux Mint & VSCodium, painfully, Ubuntu issues in VirtualBox slowed this down.
Uninstalled flatpak version of VsCodium, reinstalled with terminal commands
Practicing navigating and editing files with the terminal

06/01/26 More time spent setting things up, reading through basic html setup

07/01/26 Running through HTML basics. Learnt about page anchors and link hijacking security! Everything else was a repeat, but good to go back to basics.

## LINUX TERMINAL ##
Some Linux terminal commands:
touch abc.txt # makes a file
codium abc.txt # opens a file in VS
mkdir abc # makes a folder
cd .. # goes up a folder
mv abc.txt abc # moves abc.txt into abc
mv abc.txt .. # moves abc.txt back into parent folder
cd ~ # navigates back to base directory

## CSS BASICS ##
22/01/26
Working through CSS excercises slowly.

Inspector in dev tools shows padding/margin/border under the box model.

display:block; is default for most elements in browser. Things like div, parapraphs etc.
display:inline; for anchors, span etc. but can also be used to group containers without moving to the next line
display:inline-block; captures the best of both worlds, will appear on the same line as other inline or inline-block elements but functions as a block for width/height, padding/margins etc.
content > padding > border > margin

["*"] wildcard can be used to apply style to every matching property, or every element if used on its own
margin-left:auto; will move content to the rightmost edge, reverse for right,top,bottom

## FLEX ##
23/01/26
A flex container is any element that has display: flex on it. A flex item is any element that lives directly inside of a flex container.

Any element can be both a flex container and a flex item

flex: 1 equates to: flex-grow: 1, flex-shrink: 1, flex-basis: 0.
Lets all the flexible items be the same length, regardless of its content

flex-grow responsible for ratio splits and how its 'growth' (space it grows to take up).
flex: 2 1 0% // flex: 1 1 0%;
flex-grow: 2 would 'grow' double the size of flex-grow: 1

flex-shrink responsible for items sizing down as container shrinks.
default shrink factor is flex-shrink: 1, which means all items will shrink evenly. To have an item retain its size and to NOT shrink then you can specify flex-shrink: 0;

flex-grow/flex-shrink items do not respect width values. If the parent is big enough they grow to fill it. Likewise, when the parent is too small, the default behavior is for them to shrink to fit.

flex-basis sets the initial size of a flex item. Any growing/shrinking starts from the baseline size. flex-basis 0 ignores width. flex-basis: auto checks for a width declaration
flex: 1 => flex: 1 1 0 => (flex-grow: 1, flex-shrink: 1, flex-basis:0) | flex: auto => flex: 1 1 auto => (flex-grow: 1, flex-shrink: 1, flex-basis:auto)
