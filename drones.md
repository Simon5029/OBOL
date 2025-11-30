---
layout: page
title: Drones
permalink: /drones/
---

This page contains information about drones models.

Here is a list of great drones models (AI generated content):

-------------------------------------------------------------

# **Gazebo Drone Simulator**

**Gazebo** is an open-source 3D robotics simulator widely used for drone development, providing physics-based multirotor simulation with ROS/ROS2 integration for testing autonomy algorithms and sensor fusion.

Gazebo typically supports:
- Realistic multirotor physics with PX4/ArduPilot SITL/HITL integration via MAVLink.
- Sensor simulation including cameras, LIDAR, IMU, GPS, rangefinders, and optical flow.
- Customizable environments with obstacles, wind, lighting, and dynamic objects.
- Swarm simulation, computer vision testing, and reinforcement learning environments.

## License and Cost

Gazebo is open-source software under Apache 2.0 license, completely free across Linux, Windows, and macOS platforms.

## Limitations

Gazebo requires significant computational resources for complex scenes. Primarily Linux-focused with steeper learning curve for beginners compared to Unreal Engine alternatives.

## Useful References

- **[Gazebo Official Website](https://gazebosim.org)**  
- **[PX4 Gazebo Integration](https://docs.px4.io/main/en/simulation/gazebo.html)**  
- **[ROS2 Gazebo Documentation](https://gazebosim.org/docs)**  
- **[Drone Models Repository](https://github.com/PX4/px4-sim_gazebo-classic)**  
- **[Gazebo Tutorial Examples](https://gazebosim.org/tutorials)**

-------------------------------------------------------------

# **PX4 SITL Drone Simulator**

**PX4 SITL** is the official open-source software-in-the-loop simulator for PX4 autopilot, enabling full flight stack testing of multirotors, fixed-wing, VTOLs, and rovers without hardware.

PX4 SITL typically supports:
- Complete PX4 flight controller emulation with all sensors, EKF2, and control algorithms.
- Integration with Gazebo, jMAVSim, AirSim, and JSBSim for different fidelity levels.
- Mission planning, failsafe testing, and parameter tuning via QGroundControl.
- Swarm simulation and hardware-in-the-loop with actual flight controllers.

## License and Cost

PX4 SITL is open-source under BSD-3 license, completely free for all platforms with extensive community support.

## Limitations

SITL focuses on flight controller software validation rather than photorealistic rendering or advanced computer vision training. Requires Linux for full feature set.

## Useful References

- **[PX4 Simulation Guide](https://docs.px4.io/main/en/simulation)**  
- **[PX4 GitHub Repository](https://github.com/PX4/PX4-Autopilot)**  
- **[SITL Quick Start](https://docs.px4.io/main/en/simulation/sitl.html)**  
- **[QGroundControl GCS](https://docs.qgroundcontrol.com)**  
- **[PX4 Dev Guide](https://dev.px4.io)**

-------------------------------------------------------------

# **Parrot Sphinx Drone Simulator**

**Parrot Sphinx** is a photorealistic 3D simulation tool for Parrot professional drones, combining Gazebo physics with Unreal Engine rendering for accurate flight dynamics and sensor simulation.

Parrot Sphinx typically supports:
- High-fidelity simulation of ANAFI Ai and other Parrot drones with realistic aerodynamics and sensor models.
- Photorealistic environments using Unreal Engine assets with dynamic lighting and weather effects.
- Integration with Parrot Air SDK for autonomous mission testing and computer vision algorithm development.
- Hardware-in-the-loop support and swarm simulation capabilities.

## License and Cost

Parrot Sphinx is open-source under BSD-3 license, free to download and use with Parrot drones and SDK integration.

## Limitations

Primarily optimized for Parrot drone hardware and Air SDK. Less flexible for non-Parrot platforms compared to general-purpose simulators.

## Useful References

- **[Parrot Sphinx Documentation](https://developer.parrot.com/docs/sphinx)**  
- **[Sphinx GitHub Repository](https://github.com/Parrot-Developers/sphinx)**  
- **[Parrot Open Source Page](https://www.parrot.com/en/open-source-drone-software)**  
- **[Air SDK Integration Guide](https://developer.parrot.com/docs/air-sdk)**  
- **[Sphinx Simulation Examples](https://github.com/Parrot-Developers/sphinx-examples)**

-------------------------------------------------------------

# **jMAVSim MAVLink Simulator**

**jMAVSim** is a lightweight Java-based multirotor simulator designed for PX4 SITL testing, providing simple 3D visualization and MAVLink integration for rapid flight controller development.

jMAVSim typically supports:
- Real-time 3D visualization of multirotor attitude, position, and velocity with basic physics.
- Full MAVLink integration with PX4/ArduCopter SITL for offboard control and mission testing.
- Minimal resource usage suitable for continuous integration and automated testing pipelines.
- Support for GPS, attitude, and RC input simulation with parameter tuning.

## License and Cost

jMAVSim is open-source under BSD license, completely free and lightweight for all development platforms.

## Limitations

Basic physics and visualization only - no advanced sensors, photorealism, or complex environments. Best for flight controller validation rather than perception testing.

## Useful References

- **[jMAVSim PX4 Documentation](https://docs.px4.io/main/en/simulation/jmavsim.html)**  
- **[jMAVSim Source Code](https://github.com/px4/jmavsim)**  
- **[PX4 SITL Quick Start](https://docs.px4.io/main/en/simulation/sitl.html)**  
- **[MAVLink Integration Guide](https://mavlink.io)**  
- **[jMAVSim Usage Examples](https://github.com/PX4/PX4-Autopilot/tree/main/Tools/jMAVSim)** 

-------------------------------------------------------------

[![WIP](https://img.shields.io/badge/Status-WORK%20IN%20PROGRESS-yellow.svg)](https://github.com/)


