*Originally developed as a group project on the first semester of the Bachelor of Engineering in Robot Technology at the University of Southern Denmark (SDU). This repository is a personal fork maintained for portfolio purposes.*

# Drawing Robot
A 3-axis drawing robot developed as a semester project at the University of Southern Denmark (SDU). The system converts digital images into drawing paths, processes and optimizes the resulting coordinates in Java, and communicates them to a B&R PLC over TCP to control the robot using Structured Text.

The project combines **software development, image processing, simulation, networking, and robotics** into an end-to-end system capable of automatically reproducing images using a pencil.

## Features
- Image processing, path generation, and path optimization in Java
- Black-and-white and six-level greyscale drawing
- Java-based animated drawing simulation
- GUI for selecting image and drawing method
- TCP client-server communication between Java and PLC
- PLC-controlled (Structured Text) 3-axis robot with stepper motors
- Automatic pencil sharpening

## Showcase
<p align="center"> 
<img src="https://user-images.githubusercontent.com/39928082/200000349-7032717f-b081-4ab3-b343-85bd94cfe196.gif" alt="SDU" title="SDU" width="80%" height="80%"/> 
</p>

<p align="center"> 
<img src="https://user-images.githubusercontent.com/39928082/199998276-67d2aa06-8f68-43ae-b4f2-bddfe8cf1543.png" alt="SDU" title="SDU" width="80%" height="80%"/> 
</p>
