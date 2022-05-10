# Client–Server Systems Development Environment

Development environment for the George Fox University client–server systems class. This development environment only supports ARM-based systems like Apple Silicon on the newer MacBook generations. **x86-64 archetecture is NOT supported**. Fully configured and ready to import with [UTM](https://mac.getutm.app/).

## Why can't I use the already-provided environment?
The already-provided environment only supports x86-64 systems because it was compiled on a different architecture. If you try to download the given image then you will not be able to run it. Additionally, there is only one application that is capable of virtualizing different operating systems on Apple silicon and that application is [UTM](https://mac.getutm.app/). Virtualbox does not currently support Apple Silicon. Another option: Parallels, is not a free software and it does not support the already-provided image in the class.

## Solution: Introducing Universal Turing Machine (UTM)
For MacBook users who are running on Apple Silicon, the solution is very simple and takes just **15-20 minutes of your time**. All you need to start developing is [UTM](https://mac.getutm.app/). What is UTM? Well, UTM is an application that allows you to virtualize almost any operating system on Apple Silicon hardware. You can emulate almost any operating system with high-performance too! There won't be any noticeable slowdown when you are working on class assignments! Not only that, UTM is highly secure and supports the same features as VirtualBox. This image will run with near-native performance because I tuned the UTM configuration within the image I am providing to you to utilize Apple's Hypervisor virtualization framework.

## Set Up and Installation
### Apple Silicon:
1. Download [UTM](https://mac.getutm.app/) then open the downloaded file and follow the instructions to install it
2. Download [the image](https://drive.google.com/file/d/16yB9sQu3UQ1nXqLO7BCxMFFvKGDZ24hd/view?usp=sharing) I built (Don't worry I built this image to be an exact clone of the class-provided one, every dependancy and libaray was rebuilt and recompiled to support ARM-based machines)
3. Unzip the image you downloaded to a location that is SAFE and SECURE (I suggest making a new folder and titling it with the class name)
4. Open UTM then select `file` -> `import virtual machine`

