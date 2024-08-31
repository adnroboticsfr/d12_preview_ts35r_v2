# D12 Preview TS35-R V2 Post-Processor
[![English](https://img.shields.io/badge/language-français-blue)](./README.fr.md)

<img src="img/orca_slicer_0.jpg" alt="Preview - G-code" width="200">

## Overview

The D12 Preview TS35-R V2 post processor is designed for Orca Slicer and PrusaSlicer, providing a complete solution for generating model previews compatible with Wanhao D12 3D printers with MKS TS35-R V2.0 display and with mks robin nano board.

### Key Features

**Automatic Image Generation:** Converts thumbnails into a format compatible with the MKS TS35-R V2.0 display and an MKS Robin Nano board, embedding them into the G-code file to allow users to preview 3D models directly on their Wanhao D12 3D printers.

## Installation

1. **Download** the latest version of **d12_preview_ts35r_v2.zip**.
2. **Unzip** the executable file and place it in your desired location.

## Configuration

### Orca Slicer

1. **Printer Settings -> Basic Information:**
   - **G-code flavor** to `Marlin 2` (or `Marlin`)
   - **G-code thumbnails**: `100x100/PNG, 200x200/PNG`

    ![Orca Slicer - ](img/orca_slicer_1.png)


2. **Process -> Others -> Post-processing Scripts:**
   - Specify the path to the **Post-processor Scripts**:
    
     **"C:\Path\Where\You\Put\d12_preview_ts35r_v2.exe";**

    ![Orca Slicer - post-processor executable](img/orca_slicer_2.png)


### PrusaSlicer

1. **Under the Printer tab -> General:**
   - **G-code Flavor:** Marlin 2
   - **G-code Thumbnails:** 100x100, 200x200
   - **Set the G-code thumbnail format to** `PNG`.
   - **Supports binary G-code:** The checkbox should be unchecked.

   ![PrusaSlicer - Gcode](img/prusaslicer_1.png)

2. **Under the Print Settings tab -> in Post-processing scripts settings:**
    - Specify the path to **Post-processor scripts**:

   **"C:\Path\Where\You\Put\d12_preview_ts35r_v2.exe";**

   ![PrusaSlicer - Post-processing Scripts](img/prusaslicer_2.png)