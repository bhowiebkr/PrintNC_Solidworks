# PrintNC in Solidworks

This is the [PrintNC](https://github.com/threedesigns/printNC) design rebuilt in Solidworks from the original Fusion360 files. For more information on PrintNC see the [website](https://threedesign.store/) and the [wiki](https://wiki.printnc.info/en/home)

## Progress
I’ve just started out so not too much. I have the new V3 Z-axis mostly rebuilt. Starting to work on the gantry and base next from V2.X alpha.

**WARNING** This is still very much a work-in-progress. I cannot guarantee that there are no part interference, hole alignment mismatch, etc. I will be going over all of that after the initial complete design is finished.

## Notes
- See [equations.txt](src/equations.txt) for hole tapping and clearence used in these files. This file gets linked to sketches when necessary.
- Where possible I keep similar parts as different configurations. eg metric bolt lengths, steel stock, etc. This cuts down on the number of part files.
- The main assembly is broken up into sub-assemblies. Each subassembly is defined by its motion axis. When complete there will be x, y, z axis and frame sub-assemblies under the main assembly.

![Z-axis](images/Z-axis.PNG)
