# BrenoCQ's Personal KiCad Library

This repository contains my personal collection of KiCad library files, including schematic symbols, PCB footprints, and 3D models. I maintain this library to ensure consistency across all my personal hardware design projects and to continuously improve the quality and practicality of the components based on my building and soldering experience.

## Contents

The repository is structured to hold the main library files:

* `BrenoCQ.kicad_sym`: Contains all my custom schematic symbols.
* `BrenoCQ.pretty/`: Contains all my custom PCB footprints. This is a directory formatted as a KiCad footprint library.
* `BrenoCQ.3dshapes/`: Contains the 3D models used by the footprints in `BrenoCQ.pretty/`.

## Philosophy

I maintain this single, unified library for my personal projects because:

* **Component History/Reference:** Maintaining a personal library creates a curated list of components I have experience working with. It serves as a quick reference to easily find and reuse chips and parts that I know have worked well in past projects, saving time on re-evaluation.
* **Iterative Improvement:** As I build and test projects, I often identify ways to improve footprints (e.g., adjusting pad sizes for easier soldering, refining silkscreen outlines). Keeping them in a central library allows me to make these improvements once and have them benefit all future projects.
* **Efficiency:** Having my frequently used components readily available saves time compared to creating them from scratch or searching through large, generic libraries.

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
