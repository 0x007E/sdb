[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/sdb) ![Build](https://github.com/0x007e/sdb/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `SDB` - Switch Development Board

The `SDB` is a board with differnt type of switches, like push-buttons, a dip-switch, a code switch [SH-7050](#additional-information) and a rotary encoder [PEC12R](#additional-information). The board itself can be driven from `3` to `15V`. The board offers the possibility to switch signals in different ways to any analog/digital development board or any other circuit.

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/20?progress_color=00ff00&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/sdb/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30230/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/sdb/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30230/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/sdb/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| PCB       | [zip](https://github.com/0x007E/sdb/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/sdb/releases/latest/download/kicad.tar.gz) | KiCAD/Gerber/BoM/Drill files |
| Mechanical | [zip](https://github.com/0x007E/sdb/releases/latest/download/freecad.zip) / [tar](https://github.com/0x007E/sdb/releases/latest/download/freecad.tar.gz) | FreeCAD/Housing and exported step/stl files |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/sdb/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/sdb/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link                                                                 | Description                               |
|:----------:|:--------------------------------------------------------------------:|:------------------------------------------|
| SH-7050    | [pdf](https://www.nidec-components.com/e/catalog/switch/sh-7000.pdf) | Nidec rotary coded switch                 |
| PEC12R     | [pdf](https://www.bourns.com/docs/Product-Datasheets/PEC12R.pdf)     | Bourns PEC12R - 12 mm Incremental Encoder |

---

R. GAECHTER
