# Autonomous Indoor Drone

A level 3 autonomous drone that can pass through gates/windows in indoor environment. 

## Concept video

[![](http://img.youtube.com/vi/diFjEheEhRY/0.jpg)](http://www.youtube.com/watch?v=diFjEheEhRY "")

### Component Details 

The goal of this project is to develop a autonomous drone that scans and analyze the environment. Includes information about open paths on the track, as well as the gate's shape and position on the track. The Drone system will consist of three sub category:

## Sensors

RPLIDAR A1M8: RPLIDAR A1 is a low cost 360 degree 2D laser scanner (LIDAR) solution developed by SLAMTEC. The system can perform 360degree scan within 6meter range.The produced 2D point cloud data can be used in mapping, localization and object/environment modeling.

Camera(2 MP): Detects and conveys information used to make an image.
Processing & Controller

Raspberry Pi 3: A Single-board computer, which will process the environment using Rplidar and camera to avoid huddles, collisions and for trip & path management. Processor: 1.2 GHz 64-bit quad-core ARM Cortex-A53. 1 GB (shared with GPU)

PixHawk: A flight controller board that controls and stabilize the drone.

## Propeller

Motor MultiStar Elite 2216 920KV * 6: The durable motor designed for heavy lifting drones.

Propeller * 6: Diameter-10 inch, Pitch- 4.7 inch, Blades-2 

ESC (Electronic Speed Controller): The ESC takes the signal from the flight controller and power from the battery and makes the brushless motor spin.

Battery LiPo 6000mAh - 55/80C:

## Body Frame

CARBON FRAME Size-550 mm Weight-760g:

### FlowChart

### - Hardware Architecture
![hardware architecture](/hardware.png)

### - Software Architecture
![Software architecture](/software.png)
