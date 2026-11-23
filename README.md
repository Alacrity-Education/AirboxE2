# AirboxE2

KiCad source for the circuit diagrams in the **E2 · Introduction to digital electronics** course on the Alacrity Wiki:
<https://wiki.alacrity.ro/courses/airboxonlinebootcamp/e2>

This project contains only a schematic. It has no real board behind it and is not meant to be manufactured: the PCB file is empty, and nothing here gets routed or ordered. Every diagram in the E2 lesson is drawn in this schematic, from the MOSFET logic gates through the adders, latches and multiplexers to the buck converter.

## Contents

| File | What it is |
|---|---|
| `e2.kicad_sch` | The schematic with all E2 diagrams |
| `E2.kicad_sym` | Custom symbols used by the schematic |
| `e2.svg` | SVG export of the schematic |
| `e2.kicad_pro`, `e2.kicad_pcb` | KiCad project files (the PCB is unused) |

## Using it

Open `e2.kicad_pro` in KiCad 10 or newer (it was saved with KiCad 10). To update a figure in the course, edit the schematic, export it again (**File → Plot → SVG**), and replace the image on the wiki page.
