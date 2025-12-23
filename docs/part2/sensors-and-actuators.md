---
sidebar_position: 2
---

# Sensors and Actuators

Sensors and actuators form the interface between a humanoid robot and its environment, enabling perception and action. This section covers the critical components that allow robots to sense their surroundings and execute physical movements.

## Sensor Systems

### Vision Sensors
Vision systems provide crucial environmental information:

- **Stereo Cameras**: Depth perception through binocular vision
- **RGB-D Cameras**: Color and depth information in a single sensor
- **Thermal Cameras**: Detection of heat signatures
- **Event-Based Cameras**: Ultra-fast response to motion and changes

### Tactile Sensors
Tactile sensing enables safe and effective manipulation:

- **Force/Torque Sensors**: Measuring interaction forces at joints
- **Tactile Skins**: Distributed pressure sensing across surfaces
- **Proximity Sensors**: Detection of nearby objects without contact
- **GelSight Sensors**: High-resolution surface texture detection

### Proprioceptive Sensors
These sensors monitor the robot's internal state:

- **Encoders**: Joint position measurement
- **Accelerometers**: Linear acceleration detection
- **Gyroscopes**: Angular velocity measurement
- **Inertial Measurement Units (IMUs)**: Combined acceleration and rotation data

## Actuator Systems

### Motor Technologies
Different motor types serve specific functions:

- **Servo Motors**: Precise position, velocity, and torque control
- **Brushless DC Motors**: High efficiency and power density
- **Stepper Motors**: Accurate positioning without feedback
- **Linear Actuators**: Direct linear motion for specific applications

### Advanced Actuation
Modern actuation technologies include:

- **Series Elastic Actuators (SEA)**: Built-in compliance for safe interaction
- **Variable Stiffness Actuators (VSA)**: Adjustable mechanical impedance
- **Pneumatic Muscles**: Human-like force characteristics
- **Shape Memory Alloys**: Lightweight actuation for small movements

## Sensor Fusion
Combining multiple sensor inputs improves reliability and accuracy:

- **Kalman Filtering**: Optimal estimation from multiple noisy sources
- **Particle Filtering**: Non-linear state estimation
- **Deep Sensor Fusion**: Learning-based integration of sensor data
- **Temporal Integration**: Combining information across time steps

## Integration Challenges
Implementing effective sensor-actuator systems requires addressing:

- **Latency**: Minimizing delay between sensing and action
- **Calibration**: Ensuring accurate sensor readings
- **Robustness**: Maintaining performance in varied conditions
- **Bandwidth**: Managing data transmission rates