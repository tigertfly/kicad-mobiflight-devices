# KiCAD design blocks for MobiFlight devices

KiCAD [design blocks](https://docs.kicad.org/9.0/en/eeschema/eeschema.html#schematic-design-blocks) are reusable schematic (and PCB) snippets for PCB design. 

## About this repository

This design block library contains blocks for the basic input and output devices supported by [MobiFlight](https://www.mobiflight.com/). It is created with hope that it will be useful for those learning to design printed circuit boards for their flight simulator projects, and to have a reference schematics for the device wiring in the documentation.

This is a work in progress, and at least for now, the design blocks are mostly for schematics, as PCB layouts are more specific to particular panel layouts. 

The footprints use through-hole (THT) components by default, to be more accessible for most simulator builders. If you are more experienced in PCB design, you can of course change them to suit your preferences. For Some blocks there might also be a surface mount version - such blocks will likely contain `SMD` in their name.

### Additional resources
This design block library might reference some component footprints from the [kicad sim panel components -library](https://github.com/MobiFlight/kicad-sim-panel-components), installing it along this one is likely useful.

### Installation

You can download this repository as a `zip` file, but since it is likely in active development at this point, it might be better to use `git` to clone the repository on your computer, and pull updates from git when things are updated. I am sure things will settle later and we'll do a proper release, but for now mind the gaps and watch your head, figuratively speaking.

You can install the library via the KiCAD main window menu: `Preferences → Manage Design Block Libraries`. Choose the folder icon in the small toolbar (`Add existing`)

<img width="268" height="63" alt="Image" src="images/add-existing.png" />

Navigate to the "kicad-mobiflight-device-blocks" folder, and click `OK` to add the design block library. You likely will need to open the design blocks panel from the KiCAD schematic editor menu `View → Panels → Design Blocks`.