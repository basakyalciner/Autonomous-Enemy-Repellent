# Autonomous Firearm System with YOLOv4: Enemy Detection and Neutralization
# Autonomous Firearm System with YOLOv4: Enemy Detection and Neutralization

![image](https://github.com/basakyalciner/Autonomous-Enemy-Repellent/assets/56589435/2fa0f572-37d7-4109-9245-b05b155bb582)
![image](https://github.com/basakyalciner/Autonomous-Enemy-Repellent/assets/56589435/1026acf6-81e7-41dc-aecc-c4b1019f73ca)


## Introduction

This project presents an autonomous firearm system that utilizes YOLOv4 for enemy detection and neutralization. We created custom datasets and trained the YOLOv4 model to identify three classes: "enemy," "civil," and "soldier." After successful training, the system can detect enemies, track their movements, and engage in neutralizing actions. This project supports three different platforms: Arduino, Jetson Nano, and Raspberry Pi. The mechanical system is equipped with a firearm that engages and neutralizes the detected enemies. Additionally, we implemented a communication protocol to allow the system to interface with a computer using a USB camera for remote enemy detection and control.

## Hardware Components

1. Arduino / Jetson Nano / Raspberry Pi: The brain of the autonomous system, responsible for processing sensor data and executing control actions.

2. Firearm Mechanism: The mechanical system equipped with a firearm, capable of engaging and neutralizing detected enemies.

3. USB Camera: A USB camera connected to the computer for remote enemy detection and control.

4. Motorized Mount: A motorized mount capable of tracking enemy movements and adjusting the firearm's aim.

## Software Implementation

### YOLOv4 Training

We created custom datasets comprising images and annotations for the three classes: "enemy," "civil," and "soldier." The YOLOv4 model was then trained on these datasets using the Darknet framework.

### Enemy Detection and Tracking

Once the YOLOv4 model is deployed on the chosen platform (Arduino, Jetson Nano, or Raspberry Pi), the system can detect enemies in real-time using the onboard camera. The enemy's position is tracked using the motorized mount, ensuring continuous alignment of the firearm.

### Neutralization Action

Upon enemy detection, the system engages the firearm and initiates the neutralization process. Safety protocols and guidelines must be strictly adhered to while testing and using the system.

### USB Camera Communication

To enable remote enemy detection and control, we implemented a communication protocol between the computer and the autonomous system. The USB camera on the computer captures enemy presence and transmits the information to the system, which then proceeds with the neutralization process.

## Usage

1. Clone the repository and install the required dependencies for the chosen platform (Arduino, Jetson Nano, or Raspberry Pi).

2. Prepare the custom datasets for YOLOv4 training, and run the training process.

3. Upload the trained YOLOv4 model to the chosen platform.

4. Set up the motorized mount and firearm mechanism as per the hardware instructions.

5. Power up the system and initiate the autonomous mode.

6. The system will now detect and neutralize enemies based on the pre-trained YOLOv4 model.

7. For remote enemy detection and control, establish communication between the computer and the system using the USB camera and the implemented communication protocol.

## Conclusion

Our autonomous firearm system with YOLOv4 provides an effective solution for enemy detection and neutralization. With its ability to interface with different platforms and the option for remote control, the system showcases a robust and adaptable design.



