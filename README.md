# PrintNC in Solidworks

This is the [PrintNC](https://github.com/threedesigns/printNC) design rebuilt in Solidworks from the original Fusion360 files. For more information on PrintNC see the [website](https://threedesign.store/) and the [wiki](https://wiki.printnc.info/en/home)

Because of the difficulty in keeping the solidworks files in line with the fusion 360 files, they will never be 1-to1. If you want to build a modified PrintNC and you know Solidworks, these files can be useful in designing your CNC machine. Otherwise you are much better off following the official [Fusion 360 files](https://wiki.printnc.info/en/project-files).


## Disclaimer
**WARNING** This is still very much a work-in-progress. I cannot guarantee that there are no part interference, hole alignment mismatch, etc. The design will get more refined over time, but as for now **USE AT YOUR OWN RISK!**

## Notes
- See [equations.txt](src/equations.txt) for hole tapping and clearence, width, height, steel dimensions used in the files.
- Where possible I keep similar parts as different configurations. eg metric bolt lengths, steel stock, etc. This cuts down on the number of part files.
- The main assembly is broken up into sub-assemblies. Each subassembly is defined by its motion axis. When complete there will be x, y, z axis and frame sub-assemblies under the main assembly.
- Some parts have a 1 at the end of their names. This is so they don’t conflict with the imported IGST files I’m using as reference. Once the references are no longer needed, I will fix the naming of the part files.

## Steel table and enclosure
![table](images/table_01.png)

## PrintNC standard size
![standard size](images/PrintNC_standard_size.png)

## Paramizered sizes:
![2000x600 size](images/PrintNC_param_2000x600.png)
![500x500 size](images/PrintNC_param_500x500.png)