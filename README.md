*Originally developed as a group project on the first semester of the Bachelor of Engineering in Robot Technology at the University of Southern Denmark (SDU). This repository is a personal fork maintained for portfolio purposes.*

# Drawing Robot
A 3-axis drawing robot developed as a semester project at the University of Southern Denmark (SDU). The system converts digital images into drawing paths, processes and optimizes the resulting coordinates in Java, and communicates them to a B&R PLC over TCP to control the robot using Structured Text.

The project combines **software development, image processing, simulation, networking, and robotics** into an end-to-end system capable of automatically reproducing images using a pencil.

<p align="center"> 
<img width="800" height="450" alt="drawing-robot-timelapse" src="https://github.com/user-attachments/assets/3f8a8777-3bfd-406e-bc15-7644c8b8b3e1" />
</p>


## Features
- Image processing, path generation, and path optimization in Java
- Black-and-white and six-level greyscale drawing
- Java-based animated drawing simulation
- GUI for selecting image and drawing method
- TCP client-server communication between Java and PLC
- PLC-controlled (Structured Text) 3-axis robot with stepper motors
- Automatic pencil sharpening


## Technologies
- Java
- B&R PLC
- Structured Text
- TCP/IP
- 3D Modeling and Printing


## Showcase
- [Real-time Drawing Robot Demo](https://www.youtube.com/watch?v=acghttoedZw)

<p align="center"> 
<img src="https://user-images.githubusercontent.com/39928082/199998276-67d2aa06-8f68-43ae-b4f2-bddfe8cf1543.png" alt="drawing-robot-results" width="80%" height="80%"/> 
</p>
