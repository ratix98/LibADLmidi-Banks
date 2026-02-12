# libADLmidi-Banks
Banks used for adlmidi that I modified for use on a Soundcards with an OPL3 chip.

# What this is

A Simple home for every bank I modified for the OPL3. I used the opl3 bank editor by Wohlstand. Each bank is heavily modified from existing sets so a few instruments will probably sound a little more hollow or weak. A lot of the wopl files I have uploaded here are not the greatest but it shows alot of improvements were made as I muddled about more with the editor. The results though seem to work out while listening to it on vintage hardware. Housed here are Shareware versions of a few games that demostrate what the opl3 can do.
For proper sound output in the shareware titles when using a soundblaster 16 or compatible you must set the dmxoption with the following on the commandline otherwise note cuts will happen.

set dmxoption=-opl3

for doom and heretic you need to add -file genmidi.op2


This works in dosbox under emulation as well.

# Why

it is fun and there are no multiple opl3 cards that i know of and most modern devices I have seen use a single chip.

OPL2 is also supported to an extent.
Known good OPL2 banks that should work just fine are QFG4AD.wopl & MASHOPL2.wopl which are all ripped from sierra games or created from scratch after spending countless hours just futzing with the bank editor program and comparing to other instruments from adlib.

Doom & Heretic folder added. to use simply download and put into your doom, doom2, and heretic directory and launch the game via the example above without using the "dmxoption=-opl3" this particular file is opl2 friendly and should sound pretty decent across all games. its basically sierra on-line's instrument data shoved into doom and tweaked a little bit for compatibility.
