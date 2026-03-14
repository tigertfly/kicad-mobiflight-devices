# MobiFlight input and output device design blocks for KiCAD

KiCAD "design blocks" are reusable schematic (and PCB) snippets for PCB design.

This particular design block library has design blocks for all input and output devices
that MobiFlight supports, intended to help with simulator panel PCB designs.

Most, if not all, of these contain design blocks for schematics, as PCB layouts are
often veru specific to particular panel layouts.

Also, if there are default footprints specified, they usually are through-hole (THT)
components, which is more useful for those learning to design circuit boards. If you
are more experienced in PCB design, it is easy to replace the footprints if you need to.

This design block library might reference some component footprints from the
[kicad sim panel components -library](https://github.com/MobiFlight/kicad-sim-panel-components).
