# Maxeller Pass-Through Kernel

## Overview

This project implements a Maxeller kernel named "PassThrough" that takes a stream of values and returns the same stream. 
The kernel is designed using MaxCompiler, which utilizes an extended version of Java called MaxJ. 
The code is written in Java with files having the .maxj extension.

## Project Structure

The project consists of the following components:

- **Kernel Code**: The main logic is implemented in the PassThroughKernel class, which extends the Maxeler Kernel class. The kernel takes an input stream 'x', performs a mathematical operation:
  ![Equation](https://latex.codecogs.com/png.latex?5x^3+4x^2-3x)

- **Manager**: Describes the data flow choreography between Kernels, the DFE’s memory, and the CPU.

- **SLiC Skin**: Enables communication between the CPU and DFE.

### Clone the repository to your local machine.
   ```bash
   git clone https://github.com/dzaja123/Dataflow-HW1-mathematical-operation-Maxeler.git
