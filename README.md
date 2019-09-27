Currently a work in progress. This space will contain hardware configurations and software examples to create a portable data camera using the JETSON Nano.

# Nano Datacam Project 

## Overview
The Nano Datacam is a portable rig for using the Jetson Nano to experiment with machine learning and computer vision. It mixes powerful edge computing technology with high quality professional video capture methods and wireless connectivity to create a unique method of media capture. The project's goal is to create a data camera, a device that blurs the lines seperating digital video capture, AI, data visualization, computer vision and 3D graphics. Such a device can be used in AI research, for generating visuals to accompany live drama and dance performances, for producing experimental documentaries, and other uses to further explore.

The resources in this repository can help a developer create a datacam rig - covering software and hardware setup and including explorations and demos. 

## Setup
The datacam rig uses the following hardware and software. Detailed setup information can be found in the next sections.
* Jetson Nano
  * wireless card
  * wireless antenna
  * 128 GB memory card (x2 for different disc images)
  * case and fan
  * 5v 4a power cable
  * jumper pins
  * Raspberry Pi CSI Camera V2
  * rechargeable battery
* Intel RealSense D435i
* Atomos Ninja V
  * SSD storage
  * battery
  * HDMI cable
* USB keyboard and handheld mouse
* Customized GH4 camera rig cage
* Velcro strips
  
### Jetson Nano Core Software Setup Resources
Create two seperate disc images because installing RealSense drivers for the D435i requires rebuilding the Linux kernel. 
1. Disc Image One: Jetpack SDK + Intel RealSense D435i
2. Disc Image Two: Jetpack SDK + NVIDIA Jetson Inference + openFrameworks

#### Disc Image One: Jetpack SDK + Intel RealSense D435i
1. [Install Jetpack SDK](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#intro)
2. Install Intel RealSense Drivers - Follow the [JetsonHacks IntelSense tutorial](https://www.jetsonhacks.com/2019/05/16/jetson-nano-realsense-depth-camera) including the kernel patch instructions.

#### Disc Image Two: Jetpack SDK + NVIDIA Jetson Inference + openFrameworks
1. Install Jetpack SDK & NVIDIA Inference - Follow the [pyimagesearch tutorial](https://www.pyimagesearch.com/2019/05/06/getting-started-with-the-nvidia-jetson-nano/)
2. Install openFrameworks - Follow [madelinegannon's tutorial](https://gist.github.com/madelinegannon/237733e6c114f156b31366f47c1f3d32) 

### Add Wireless Capability to Jetson Nano
Follow the the [JetsonHacks wireless install tutorial](https://www.jetsonhacks.com/2019/04/08/jetson-nano-intel-wifi-and-bluetooth/).

### Datacam Rig Setup
This section has detailed photos of a datacam rig to help you build your own. Each rig will require some customization but the goal of the build is to make a sturdy stable rig that is fairly easy to move around with.

## Use Cases and Application Demos
The following sections suggest some possible uses for the datacam device with links to application code repositories.  
1. AI research
2. Generating visuals to accompany live drama and dance performances
3. Producing experimental documentaries
4. Other uses to further explore


