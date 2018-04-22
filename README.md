# PongTracker
OpenNI based Ping Pong ball tracker

## Installation Instructions

1. Download binary distribution of OpenNI2 from [Occipital](https://structure.io/openni) and follow installation instructions
    * To ensure OPENNI2_INCLUDE and OPENNI2_REDIST are available for cmake use source the OpenNIDevEnvironment file in the OpenNI2 Binary
2. Clone this repository to your machine
3. `cd PongTracker`
4. `mkdir build`
5. `cd build`
6. `cmake ..`
7. `make`