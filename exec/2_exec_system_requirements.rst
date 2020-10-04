**********************
2. System Requirements
**********************

To build and run sample applications for Execution Management as described in this manual,
The following version of the software is required

* OS: Linux(Docker)
* Modeling tool: mobilgene A Studio 19.11 2020.05 or higher
    .. hint:: You can use mobilgene Generator provided in mobilgene A Studio to generate manifests (.json) file instead of using mobilgene Generator.
        For detailed information how to use mobilgene Generator, See the User Guide of mobilgene A Studio.
        For using mobilgene Generator, See Ch. 4.3 Generating Manifest Files in this manual
* Build system: CMake(Cross Platform Make) 3.8.2 or higher
    .. hint:: You can write a native makefile including the build process that is platform-dependent by using CMAKE functions.
* Compiler : gcc 4.8 (or higher) when target OS is Linux

.. note:: In this manual, no target hardware is required for the build process.
    You can build and run the sample application on native Linux or Docker as a Virtual Machine. For detailed information of build process in mobilgene Adaptive, See the Quick Start Guide document.

