# PyDash_Enclosure - Information
This readme covers the case or enclosure portion of the PyDash. For the Dash App, PCB design, OS design, or dash builder, see the below repositories:
- [PyDash_OS](https://github.com/JungleGim/PyDash_OS)
- [PyDash_App](https://github.com/JungleGim/PyDash_App)
- [PyDash_PCB](https://github.com/JungleGim/PyDash_PCB)
- [PyDash_Enclosure](https://github.com/JungleGim/PyDash_Enclosure)
- [PyDash_Builder](https://github.com/JungleGim/PyDash_Builder)

## Introduction
The PyDash enclosure is designed to keep the PyDash PCB in place and provide a means of mounting to a vehicle

# Project Status
## Revlog
* Rev 2.0a
	- Build date: 03/07/2026
    - Alpha testing initial files and fitment
	- Intended for use with PyDash Rev2.0
    - See Project_Tracker.md for current working notes/issues that are WIP
	
## Future Development
* Complete documentation for printing and assembly, including a BOM
* Export files in different formats

## Repository Directory Map
The following information describes the folders found in the root directory of this repository
* (folder) Enclosure Assembly
	- Native files for the enclosure
	- This is the main folder that contains the complete assembly
	- (folder) external parts - bought or off the shelf parts for the assembly
	- (folder) pydash_parts - individual printed components to form the enclosure
* (folder) Documentation - TODO
	- Contains any user documentation like the assembly guide and BOM
* (folder) Additional format Files - TODO
	- contains zip files of the required printable parts in additional formats

# Requirements
## Build Environment
Currently, Solidworks is used to model the individual components. All native files are 

# Methodology
## Key Considerations and Constraints
Some of the considerations and/or constraints in making this project are listed below, roughly in order of importance.

* individual pieces should be print-in-place in a manner that provides a clean external finish using currently available FDM printer technology
	- achiving the above bullet may require additional post-processing like the four mounting bosses
* while trying to achieve IP65 would be nice, its not nescesary
	- the dash is meant for in-car use. Additional features like the micro-SD card and USB port would make it more difficult to seal. Additionally, using a consumer grade display poses a problem to achieve this as well
	- further, the dash PCB itself is coated prior to assembly, which should hopefully protect and seal all critical components
* assembly should require no special tools
* the enclosure should be servicable and easy to disassemble if needed
* mouting solutions must withstand the typical high-NVH environment of a track car

# Application HELP file
See the "User_Guide.md" markdown file for a full user guide 

# Known bugs and bug fixes
No current known bugs

# FAQ section
No current FAQ

# Copyright and licensing information
## GNU GPLv3
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.

## Additional disclaimer
The information included is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software or tools included in this repository.
