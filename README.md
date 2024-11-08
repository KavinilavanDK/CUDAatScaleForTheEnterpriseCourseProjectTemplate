# Canny Edge Detection with CUDA

##### Overview

This project implements a Canny edge detection algorithm using CUDA to leverage the parallel processing capabilities of GPUs. The application reads grayscale images from a specified input directory, processes them using a CUDA kernel, and outputs the results to a specified output directory. This implementation aims to enhance the performance of edge detection tasks, particularly for large image datasets.

##### Code Organization

bin/: This folder holds all binary/executable code that is built automatically or manually. Executable code should use the .exe extension or a programming language-specific extension.

data/: This folder holds example data in any format. If the original data is large or can be brought in via scripts, this can be left blank in the repository to avoid major downloads when only the code/structure is desired.

src/: The source code is placed here in a hierarchical fashion, as appropriate.

README.md: This file holds the description of the project so that anyone cloning or deciding if they want to clone this repository can understand its purpose to help with their decision.

Makefile: This file provides instructions for building the project's code automatically.

run.sh: An optional script used to run your executable code, either with or without command-line arguments.

##### Key Concepts

CUDA Programming
Image Processing
Edge Detection Algorithms
Memory Management in CUDA

##### Supported OS
Linux
Windows (with appropriate modifications)

##### Supported CPU Architecture

x86_64

##### CUDA APIs Involved
cudaMalloc()
cudaMemcpy()
cudaFree()
cudaEventCreate()
cudaEventRecord()
cudaEventSynchronize()
cudaEventElapsedTime()

##### Dependencies needed to build/run
CUDA Toolkit
OpenCV (version 4 or later)

##### Prerequisites

Install the CUDA Toolkit on your machine. Ensure that your GPU is compatible with CUDA.
Install OpenCV using the appropriate package manager for your operating system.


##### Build and Run
Clone the repository:

git clone <repository-url>
cd <repository-directory>
Install the required dependencies:

For OpenCV, you can use:
sudo apt-get install libopencv-dev  # For Debian/Ubuntu
Build the project:

make all
Run the application:

./run.sh
The processed images will be stored in the output/ directory.
##### SAMPLE OUTPUT
![image](https://github.com/user-attachments/assets/c924fb35-d1d3-40de-9b7e-4eb6a709bbb6)
![image](https://github.com/user-attachments/assets/5b6c3bd3-64e6-47dc-9aa5-c166eab570e3)
![image](https://github.com/user-attachments/assets/45a614cd-0d81-42db-8bd0-4f2612ed5cdb)
![image](https://github.com/user-attachments/assets/35163c25-b469-4744-a451-7b13dbd4d0ad)


