# LibADLmidi-Banks
Banks used for adlmidi that I modified for use on a Real OPL3 enabled card.

# What this is

A Simple home for every bank I modified for one OPL3 chip with the opl3 bank editor by Wohlstand. Each bank is heavily modified from DMXOPL from sneakernets so a few instruments will probably sound a little more hollow or weak. The results though seem to work out while listening. Housed here are Shareware versions of a few games that demostrate what the opl3 can do.
For proper sound output in the shareware titles when using a soundblaster 16 or compatible you must set the dmxoption with the following on the commandline otherwise note cuts will happen.

set dmxoption=-opl3

for doom and heretic you need to add -file genmidi.op2


This works in dosbox under emulation as well.

# Why

it is fun and there are no multiple opl3 cards that i know of and most modern devices I have seen use a single chip.

OPL2 is also supported to an extent.
Known good OPL2 banks that should work just fine are QFG4AD.wopl & MASHOPL2.wopl which are all ripped from sierra games or created from scratch after spending countless hours just futzing with the bank editor program and comparing to other instruments from adlib.

Doom & Heretic folder added. to use simply download and put into your doom, doom2, and heretic directory and launch the game via the example above without using the "dmxoption=-opl3" this particular file is opl2 friendly and should sound pretty decent across all games. its basically sierra on-line's instrument data shoved into doom and tweaked a little bit for compatibility.
