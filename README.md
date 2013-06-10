Quinn Ebert's pmset Toy
=======================

Utility for getting (and in future setting) all system power settings on OS X with a single command.

Motivation
----------

For those not in the know, I have a Solidoodle 2 3D printer.  The machine I use to control it sits across the room from my primary desktop computer.  The machine in question is a portable computer.  When printing, I want to avoid the machine going to sleep, but I want the machine to sleep automatically when not printing.  Apple doesn't have the same concept of "Power Plans" or "Power Schemes" we see supported in that evil Redmond-based operating system.  My pmset Toy project aims to bridge that gap.

System Requirements
-------------------

* Currently only officially supports Mac OS X 10.8.4 on 64-bit x86, it will check the OS and architecture, pass '--force' if you're OK with running on something else you know will be compatible (I won't be held responsible for consequences one way or another).

Supported Features
------------------

* Get a list of commands you can later paste to restore the machine's current power settings.

Planned Features
----------------

* Maintain a list of "power profiles."
* Support switching between those "power profiles" with a single command.