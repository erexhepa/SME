## ImageJ Plugin instructions:

Prerequisites and installation:

1. If Fiji/ImageJ is not installed then download and install a version preferably bundled with JRE 1.8 (http://imagej.net/Fiji/Downloads). 

2. If you have an ImageJ or Fiji version already installed, make sure Java SDK 1.8 or higher is also installed on your system (or download and install it from http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).
Once done, ImageJ/Fiji will automatically detect Java 1.8 and use it as default.

3. Download and place plugin 'SME_stacking.jar' in the 'plugins' folder of your Fiji/ImageJ installation.

Usage:

1. Open an image stack

2. In the "plugins>SME Stacking" submenu press "SME Stacking". If the stack is single channel, it will be processed directly. If the stack is multi channel, you will be asked to specify the reference channel from which the manifold is computed. The extraction is then processed from all channel to produced a color 2D image. 

## Matlab Toolbox instructions:

1. clone the src_matlab folder

2. Run the SME_demo.m
