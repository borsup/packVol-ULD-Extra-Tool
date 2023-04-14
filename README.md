# packVol-ULD-Extra-Tool
An Excel VBA tool to add customizable inlaps to PackVol containers.

Installation
============
To use this tool, you will need Microsoft Excel installed on your Windows-based computer. To install, simply download the packpackVol-ULD-Extra-Tool.xlsm file from this repository and open it in Excel.

Usage
=====
Click on the "Import container file" button and select the XLS file generated from PackVol. The container properties sheet will be copied to the packVol-ULD-Extra-Tool.xlsm file.

(Optional) Define a name for the container you want to create. The container name cannot exceed 40 characters.

Select the container type from the drop-down menu, which corresponds to the name of the sheets in this file. So, it is recommended that you rename the sheets with familiar names for better visibility.

Define the number of inlaps you want to add to the container, up to 4.

For each inlap, fill in the fields to define its properties. Select the axis on which the inlap will be located by choosing: X1, X2, Y1 or Y2. Enter the dimensions (length, width and height) and choose whether it will be created with a depth corresponding to the length or width. You can also specify any position on the axis by specifying the elevation from the ground and the distance from its reference corner: left or right.

Once all the inlaps have been defined, click on the "Build my inlap container" button. The program will add the properties for each inlap to the sheet corresponding to the chosen container.

The newly created file will be saved in your username's "Downloads" folder and can be imported into the PackVol software. You will then see a 3D representation of the container with the inlaps of your choice. In this way, when Packvol will make the loading optimization, no package will be placed inside these regions.

Contributing
============
This tool is provided free of charge for personal and commercial use. However, if you find this tool helpful and wish to support its further development, you can make a donation in Bitcoin to the following wallet address: 16coFa4h4ySy8fNCmnJo74ReZdq22v5CNC

License
=======
This project is licensed under the MIT License, a permissive open-source software license that allows the use, modification, and distribution of the software for any purpose, commercial or non-commercial, with little or no restriction. It also grants the right to sublicense and sell the software.

The MIT license comes with no warranty, and the original creator is not responsible for any damages or liabilities caused by the software. Users are free to modify and distribute the software without obtaining permission from the original creator. However, a notice including the name of the original creator, borsup, must be included.


Thank you for using PackVol ULD Extra Tool!
