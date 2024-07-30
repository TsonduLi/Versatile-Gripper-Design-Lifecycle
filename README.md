# Versatile Gripper Design Lifecycle

## Overview

This project documents the comprehensive lifecycle of designing and developing a versatile gripper capable of handling various shapes, weights, and materials. The gripper integrates strong mechanical design principles with advanced control algorithms to achieve precise and adaptable performance.

## Features

- **Strong Gripping Force**: Achieved through relative linear motion between two bases.
- **Multithreaded Data Synchronization**: Concurrently collected and transmitted IMU, sensor images, and laser readings via the MQTT IoT protocol using Python.
- **Flexible Design**: Capable of gripping objects with different geometries, employing rigid universal clamps to enhance durability.
- **Advanced Control Mechanisms**: Utilizes linear actuators and force sensor resistors (FSR) for precise control and feedback.

## Components and Design

### CAD Views
- Detailed isometric views of the gripper and its components are provided.
- Comprehensive CAD models created using Creo.

### Bill of Materials
- The gripper structure is primarily produced using PLA with varying fill densities for different parts.
- Components include pin arrays, linear actuators, force sensing resistors, and linear rails.

### Key Components
- **Lower Base**: Provides structural support and houses the stationary parts.
- **Upper Base**: Connected to a linear actuator and moves to grip objects.
- **Pin Arrays**: Designed to ensure high stiffness and adaptability.
- **Cap**: Designed to match the robotics arm in the Technion lab and provides room for pin array contraction.
- **Force Sensing Resistor**: Used for detecting the appropriate gripping force.
- **Linear Actuator**: Facilitates smooth linear motion for the upper base.

## Analysis and Testing

### Force and Bending Analysis
- Detailed analysis of force distribution on different geometries like nuts, cylinders, and cubes.
- Bending analysis of the gripper's pins and base to ensure structural integrity under load.

### Prototyping and Manufacturing
- 3D printing used for prototyping with specified filling densities for different components.
- Detailed production files and quality control steps provided for each part.
