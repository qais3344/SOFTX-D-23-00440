# ClimateCool
Automating Cooling Load Calculations with MATLAB App based on ASHRAE Standards
***
## General Info
DynABlock_2D is a MATLAB® application for dynamic, pushover and limit equilibrium analysis of 2D rigid Block structures. 
The code has been developed with the aim to provide a tool for seismic assessment of rocking failure mechanisms in historic masonry structures subjected to settlements. 
Structures are represented as 2D assemblages of rigid blocks interacting at no-tension, frictional contact interfaces. Rigid or elastic contacts can be used for compression behavior at blocks interfaces. The geometric configuration of the rigid block assemblage can be easily imported from .DXF files, where blocks are modelled using polylines, with vertices corresponding to contact faces. Input data, including analysis types, mechanical properties and loading conditions are imported from .XLS files.
DynABlock_2D is built as a standalone executable application which provides as outputs force and displacement responses in the large displacement regime and the plot of the corresponding failure mechanism. A key feature of DynABlock_2D is the optimization-based formulation of the dynamic and static contact problems associated to dynamic, linear and non-linear kinematic analysis. The Mosek© optimization software is used to solve the optimization problems which are formulated in DynABlock_2D (www.mosek.com).
The present version of the code is limited to 50 blocks, expires in 2024, and can be used to run limit equilibrium analysis, pushover analysis and dynamic analysis both for rigid and elastic contacts. Other functionalities which are not comprised in the current version of the code, such as the modelling of finite compressive strength of masonry and the modelling of ties, will be included soon in further releases of the code.
A simple case study of an arch-pillars system is also included with the installation file. 
***
## Installation
### Supported platform 
Windows 64 bit x86.
***
### Prerequisites for Deployment
Download and install the Windows 64-bit version of the MOSEK Version 9.1.10 from the MOSEK Web site by navigating to https://www.mosek.com/downloads/9.1.10/ . 
MOSEK provides faculty, students or staff at degree-granting academic institutions a free academic license. The free academic license can only be used for research in academic institutions or educational purposes. 
Academic licences can be requested at https://www.mosek.com/products/academic-licenses/. The license file mosek.lic should be saved to:  C:\users\<userid>\mosek\, where <userid> is the User ID on the computer. Please note that the folder ‘mosek’ in C:\users\<userid>\ should be created by the user. Use the ‘Test license system’ utility which is available in ‘Mosek Optimization Tools’ from the Start Menu to verify that the license is checked out correctly. For further details visit: www.mosek.com.
### Setup instructions
To install DynABlock_2D on a computer running Windows 10 Operating system: right-click on  ‘DynABlock_2D_Setup.exe’ and select Run as administrator; 
follow the instructions in the installation wizard, using default options for installation folders. Select the option ‘Add a shortcut to the desktop’. 
If the MATLAB® Runtime is not installed, the User will be requested to download the Windows 64-bit version of the MATLAB® Runtime from the MathWorks Website. The MATLAB® Runtime is about 790 MB, this might take few minutes to complete. 
For more information about the MATLAB® Runtime and the MATLAB® Runtime installer, see Package and Distribute in the MATLAB® Compiler documentation in the MathWorks Documentation Center (www.mathworks.com).    

## Getting started
To run the analysis, right click on the DynABlock_2D shortcut icon on your desktop. The shortcut icon can be also saved and opened in another folder. Otherwise, open DynABlock_2D pointing to "All Apps" on the Start menu and clicking DynABlock_2D. 
After few seconds, the MS-DOS prompt appears where control messages are displayed as the analysis starts and proceeds. The DynABlock_2D ‘Open File’ window also appears. Select the XLS input file. 
Please note that the DXF and XLS files must be saved into the same folder of the shortcut icon (i.e. Desktop or another folder). Using Windows file explorer to point to a different folder from that used to run the shortcut icon is not allowed in the current version of the code.
For examples and documentation please also refer to: https://doi.org/10.5281/zenodo.6657392

