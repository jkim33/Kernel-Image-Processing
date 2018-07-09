# CStuy 2018 - Kernel
## From Jason Kim

## What is Kernel Image Processing?
### Details
Image Processing is a method of image processing that allows one to blur, sharpen, edge detect, etc. an image. This process uses matrices, which is the kernel, and it also uses a mathematical process called convolution.
### Kernel
A Kernel is simply a matrix, typically 3x3 or 5x5, that has different values depending on the effect it should achieve. Each value within a kernel becomes important in the mathematics of the changing of a pixel. A Normalized Kernel would have elements, whose sum is one.
### Convolution
Convolution is the process of adding each element of the image to its local neighbors, weighted by the kernel. This is related to a form of mathematical convolution. [*From Wikipedia*](https://en.wikipedia.org/wiki/Kernel_(image_processing))

## How do I download this?
### ZIP File
On the top-right corner, there should be a green button that says Clone or Download. Click it and download the ZIP File (For the normal peeps), or clone it (Only if you know how to)
Once you download the package, go to the correct directory and run the correct program for your OS.
### OS Differences
- For Windows-32: Kernel-Image-Processing/Kernel/application.windows32/Kernel.exe
- For Windows-64: Kernel-Image-Processing/Kernel/application.windows64/Kernel.exe
- For MacOSX-64: Kernel-Image-Processing/Kernel/application.macosx64/Kernel.app/Contents/MacOS/Kernel
- For Linux-Arm64: Kernel-Image-Processing/Kernel/application.linux-arm64/Kernel
- For Linux-ArmV6HF: Kernel-Image-Processing/Kernel/application.linux-armv6hf/Kernel
- For Linux-32 : Kernel-Image-Processing/Kernel/application.linux32/Kernel
- For Linux-64 : Kernel-Image-Processing/Kernel/application.linux64/Kernel

## How do I run this?
Once you've found the correct executable, make sure that your webcam is enabled. Also make sure that the privacy settings of the webcam won't block the program. Once the program is running, here is how you use the different kernels.
- Press 1 -> Normal/Identity
- Press 2 -> Blur
- Press 3 -> Edge Detection
- Press 4 -> Sharpen
