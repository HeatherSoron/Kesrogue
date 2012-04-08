Kesrogue is meant for the DCPU, and is written in DCPU assembly. I suggest you use DCPU-16 Studio (http://badsector.github.com/dcpustud/) to run it - that's the emulator I use for development, and I/O has not yet been standardized. Hence, Kesrogue may not work on other emulators.

Currently, Kesrogue is primarily aimed at developers. You can't do a whole lot, and there's a lot of debug code still in it. Once I get it built out enough to have a downward staircase, I'll probably provide a bit more info for non-devs.

So far, you can only move around, and slay the lone rabbit. The rabbit does not fight back, does not move, and has no HP, so slaying it is Very Easy (it is NOT a Pythonesque vorpal bunny).

At present, you CAN combine this with other programs - type "Q" (shift-Q) to quit, assuming a DCPUStud-like interface. It should leave ALL registers the same as it found them, although that might change as things develop.

Devs: see the specs/ folder, for specifications about the game.
