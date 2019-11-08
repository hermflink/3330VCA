# 3330VCA

Kicad project files of a AS3330 based VCA. Part of a modular DIY synth project, other modules are available in other repositories. Not entirely compatible with a CEM3330 as this would require a diode to ground on pin 4.

Used the Audio.lib from https://kicad.github.io/symbols/Audio to extend the Kicad library for the AS3330 component.

Designed to work with +/- 15V, not tested for +/- 12V

The PCB is 9.5 x 5.5 cm and has no PCB-mounting of potmeters, switches, jacks; these are all connected by pin header connectors

The PCB  has a fault: the connection between pin 5 and 8 of AS3330 on the backplane should be removed. Instead, pin 5 should be connected to R15/R17 as the schema points out.

Loosely based on http://www.digisound80.co.uk/digisound/modules/80-9_files/80-9_ETI.pdf

R4, C2, R18 and C8 can be safely left out.

