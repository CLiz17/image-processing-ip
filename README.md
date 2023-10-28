# Image Processing on a Zynq ZedBoard FPGA

## Box Blur: Neighborhood Processing with a 3 x 3 kernel

This project focuses on implementing image processing on a Zynq ZedBoard FPGA, with a specific emphasis on applying a Box Blur filter using a 3 x 3 kernel. The project involves multiple stages, from module development to simulation and generating the output image using Vitis SDK.

## Project Overview

### 1. Module Development
The image processing IP is divided into three main modules:

1. **Line Buffer Module**: This module is responsible for managing the line buffer, an essential component for image processing operations.
2. **Convolution Module**: This module performs the convolution operation using a 3 x 3 kernel to apply the Box Blur filter.
3. **Control Logic with Line-Buffer Modules**: Control logic integrates the line buffer modules and facilitates smooth image processing operations.

### 2. Integration and Packaging
The three modules are integrated to create a comprehensive image processing IP package.

### 3. Testing and Simulation
A testbench is created to simulate the IP package and verify its functionality.

### 4. Vitis SDK Integration
The project is opened in Vitis SDK, and the final output image is generated using the Zynq ZedBoard FPGA.

****
**Inspired from @vipinkmenon/SpatialFilter**
