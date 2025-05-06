# BrenoCQ KiCad Library
This repository contains my personal collection of KiCad library files, including schematic symbols, PCB footprints, and 3D models.

## Contents
The repository is structured to hold the main library files:

* `BrenoCQ.kicad_sym`: Custom schematic symbols.
* `BrenoCQ.pretty/`: Custom PCB footprints.
* `BrenoCQ.3dshapes/`: The 3D models used by the footprints in `BrenoCQ.pretty/`.

## Getting Started (Adding to KiCad)
To use this library in your KiCad projects:

1.  **Clone or Download:** Get the files from this repository to your local machine.
2.  **Open KiCad:** Launch the KiCad application.
3.  **Add Symbol Library:**
    * Go to `Preferences` -> `Manage Symbol Libraries`.
    * In either the 'Global Libraries' or 'Project Specific Libraries' tab, click the `+` icon.
    * Browse to where you saved the repository files and select the `BrenoCQ.kicad_sym` file.
    * Click 'OK' to add it.
4.  **Add Footprint Library:**
    * Go to `Preferences` -> `Manage Footprint Libraries`.
    * In either the 'Global Libraries' or 'Project Specific Libraries' tab, click the `+` icon.
    * Browse to where you saved the repository files and select the `BrenoCQ.pretty` **directory** (select the folder itself).
    * Click 'OK' to add it.

The custom symbols and footprints should now be available in the Symbol Chooser and Footprint Assigner.

## License
This library is licensed under the [MIT License](LICENSE).
