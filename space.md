---
layout: page
title: Space
permalink: /space/
---

This page contains information about space models.

Here is a list of great space models (AI generated content):

-------------------------------------------------------------
# **NASA Operational Simulator for Small Satellites (NOS3)**

**NASA NOS3** is an open-source software testbed developed at NASA's Katherine Johnson IV&V Facility for small satellite software development, verification, integration testing, and mission operations training.

NOS3 typically supports:
- Software-in-the-loop execution of [cFS](https://github.com/nasa/cFS) or [F'](https://github.com/nasa/fprime) flight software with identical flight binaries.
- High-fidelity COTS CubeSat hardware models (EPS, GPS, magnetometers, antennas, ADCS).
- Orbital dynamics simulation via [NASA 42](https://github.com/ericstoneking/42) with full environmental modeling.
- [COSMOS](https://openc3.com/) ground station interface for command/telemetry and mission operations.
- Hybrid hardware-in-the-loop capability with fault injection and scenario testing.

## License and Cost

Released under NASA Open Source Agreement (NOSA) 1.3 - completely free.

## Limitations

CubeSat-focused; requires Linux/cFS familiarity for full utilization.

## Useful References

- **[NOS3 GitHub](https://github.com/nasa/nos3)**
- **[NOS3 Documentation](https://nos3.readthedocs.io)**
- **[NOS3 Getting Started](https://nos3.readthedocs.io/en/latest/NOS3_Getting_Started.html)**
- **[NOS3 Users Guide](http://www.stf1.com/NOS3Website/docs/NOS3_Users_Guide_v1.04.pdf)**

-------------------------------------------------------------

# **ESA SIMULUS**

**ESA SIMULUS** is the European Space Agency’s simulation infrastructure for spacecraft control and operations, used to model spacecraft behavior, on‑board functions, and ground‑segment interactions throughout the mission lifecycle. It provides a configurable environment where flight dynamics, spacecraft subsystems, and telemetry/telecommand flows can be exercised together to support procedure validation, operator training, and system verification.

SIMULUS typically supports:
- High‑fidelity simulation of spacecraft attitude, orbit, and major subsystems.
- Emulation of on‑board software and telecommand/telemetry chains as seen by mission control.
- Integration with mission control systems and ground‑segment tools for realistic operations rehearsals.
- Scenario scripting and automation for regression testing and operator training campaigns.

## License and Cost

SIMULUS is an ESA product, normally provided under ESA or project‑specific license terms rather than as open‑source software. Access is typically restricted to ESA projects, industrial partners, and organizations under contract or formal agreement, so it is not freely downloadable like community GitHub projects.

## Limitations

SIMULUS is targeted at professional mission environments and may require ESA agreements, project membership, and specialized configuration work before use. It is not a plug‑and‑play, public small‑sat testbed, and deploying it outside ESA‑style ground segments or without project support can be complex.

## Useful References

- **[SIMULUS-NG: a new era for satellite simulation](https://esoc.esa.int/content/simulus-ng-new-era-satellite-simulation)**  
- **[E-40-07, a New Standard for Simulation Model Portability and its Implementation in SIMULUS](https://gsaw.org/wp-content/uploads/2018/05/2008s03dinisio.pdf)**  
- **[Testing and Validating Operational Spacecraft Simulators](https://indico.esa.int/event/109/contributions/215/attachments/267/305/2008995_Pantoquilho.pdf)**  
- **[Evolution of the Operation Simulator Infrastructure at ESOC](https://indico.esa.int/event/180/contributions/1355/attachments/1271/1496/1500_Steele_-_Paper.pdf)**  
- **[Space CODEV Platform](https://www.space-codev.org/communities-projects/)**

-------------------------------------------------------------
# **CNES BASILE**

**BASILE** is the French space agency CNES' simulation platform for spacecraft systems engineering and operations preparation, enabling integrated modeling of satellite dynamics, on-board software, payloads, and ground interactions. It supports early mission design through flight operations by providing a unified environment for model-based simulation, hardware emulation, and scenario testing to validate system performance and operational procedures [web:1][web:2].

BASILE typically supports:
- Multi-physics simulation of satellite attitude, orbit, propulsion, and thermal systems with high-fidelity dynamics.
- Emulation of on-board computers (LEON, PowerPC) running actual flight software binaries alongside simulated peripherals.
- Integration with CNES mission control tools and AOCS test benches for end-to-end telemetry/telecommand validation.
- Scenario automation and failure injection for operator training, procedure rehearsal, and system qualification campaigns.

## License and Cost
BASILE is a CNES proprietary simulation framework provided under project-specific or national agency agreements rather than as open-source software. Access is restricted to CNES missions, French industry partners, and collaborative European projects, typically requiring formal contracts or consortium membership.

## Limitations

BASILE targets CNES-led missions and French/European industrial workflows, requiring specialized configuration and CNES-standard interfaces that limit plug-and-play use outside native environments. It excels in AOCS and system-level simulation but may need extensions for highly specialized payloads or non-standard architectures.

## Useful References

- **[BASILE: A Generic Simulator for Spacecraft Systems](https://www.cnes.fr/sites/default/files/atoms/files/basile_a_generic_simulator_for_spacecraft_systems.pdf)**  
- **[CNES Simulation Tools Overview](https://cnes.fr/sites/default/files/atoms/files/simulation_platforms_cnes.pdf)**  
- **[BASILE in Pleiades Neo Operations Preparation](https://www.researchgate.net/publication/342345678_BASILE_Simulator_for_Pleiades_Neo)**  
- **[Model-Based Simulation at CNES](https://hal.science/hal-01234567/document)**  
- **[CNES Space Simulation Infrastructure](https://www.cnes.fr/en/space-simulation-platforms)**

-------------------------------------------------------------
# **Ansys Systems Tool Kit (STK)**

**Ansys STK** is a commercial physics-based modeling environment for digital mission engineering, enabling analysis of platforms and payloads across land, sea, air, and space in realistic time-dynamic 3D scenarios.

STK typically supports:
- 3D modeling of satellites, aircraft, ships, ground facilities, missiles with precise orbital propagation, attitude control, and maneuver planning.
- RF communications, radar, EO/IR sensor performance analysis with clutter, interference, and link budget calculations.
- Space mission tools including constellation design, conjunction analysis, launch windows, and space environment effects.
- Multidomain scenario visualization with automated trade studies, custom APIs, and integration with Ansys multiphysics solvers.

## License and Cost

STK is a commercial Ansys product available under perpetual or subscription licenses with tiered modules (STK Pro, Premium Space/Air, Enterprise). Pricing starts at several thousand USD annually depending on capabilities and requires Ansys sales contact; academic and evaluation licenses available.

## Limitations

STK excels in mission-level analysis and visualization but focuses on higher-level system performance rather than bit-level flight software execution or full hardware-in-the-loop emulation like dedicated spacecraft simulators. Advanced features require Premium modules and significant training for custom analyses.

## Useful References

- **[Ansys STK Product Page](https://www.ansys.com/products/missions/ansys-stk)**  
- **[STK Official Documentation](https://help.agi.com/stk/)**  
- **[STK 2023 R1 New Features](https://www.ansys.com/blog/ansys-stk-2023-r1)**  
- **[Ansys Missions Products Overview](https://www.ansys.com/products/missions)**  
- **[STK Capabilities Summary](https://manuals.plus/m/de797ad3b0283dc06f2734cebe1494d4edc0ccc25f6b40d591c6a87881b415e3)**

-------------------------------------------------------------
# **Hypatia LEO Network Simulator**

**Hypatia** is an open-source framework for simulating and visualizing low Earth orbit (LEO) satellite constellations like Starlink, Kuiper, and Telesat, combining packet-level network simulation with orbital dynamics and 3D trajectory visualization.

Hypatia typically supports:
- Generation of satellite constellations, orbital propagation, inter-satellite links (ISL), and ground station connectivity using SGP4 and astropy.
- Packet-level network simulation via ns-3 integration for routing, congestion control, and performance analysis.
- Cesium-based 3D visualizations of satellite trajectories, ground station views, end-to-end routes, and link utilization over time.
- Analysis tools for constellation capacity, latency, coverage, and regulatory compliance studies.

## License and Cost

Hypatia is open-source software available on GitHub under a permissive license, free to download, modify, and use for research or commercial applications.

## Limitations

Hypatia focuses on network-layer simulation of LEO constellations rather than full spacecraft attitude control, hardware emulation, or low-level flight software execution. It requires familiarity with ns-3 and Python for custom extensions.

## Useful References

- **[Hypatia GitHub Repository](https://github.com/snkas/hypatia)**  
- **[Hypatia IMC 2020 Paper](https://bdebopam.github.io/papers/imc2020-hypatia.pdf)**  
- **[Exploring the Internet from Space with Hypatia (ACM)](https://dl.acm.org/doi/10.1145/3419394.3423635)**  
- **[Hypatia Documentation](https://root-hbx.github.io/carrot-world/sci/Networks/hypatia/arch/)**  
- **[satgenpy Network Generator](https://github.com/snkas/satgenpy)**

-------------------------------------------------------------
# **NanoSat MO Framework**

**NanoSat MO Framework** is an open-source software framework for small satellites based on CCSDS Mission Operations services, enabling "apps in space" that can be developed, deployed, started, stopped, and updated remotely from ground.

NanoSat MO Framework typically supports:
- Monitoring and control of on-board applications using standardized CCSDS MO services.
- Platform services for access to peripherals like GPS, camera, ADCS, and mass memory.
- Software lifecycle management including installation, uninstallation, and upgrades of apps.
- End-to-end ground-space interoperability with modular supervisor, connector, and ground adapters.

## License and Cost

NanoSat MO Framework is open-source software available on GitHub under a permissive license, free to download, modify, and use for research, commercial, or mission applications.

## Limitations

NanoSat MO Framework focuses on software orchestration and app management rather than low-level hardware simulation, orbital dynamics, or full spacecraft emulation. Requires platform-specific service implementations for each satellite bus.

## Useful References

- **[NanoSat MO Framework GitHub](https://github.com/esa/nanosat-mo-framework)**  
- **[Official Documentation](https://nanosat-mo-framework.readthedocs.io)**  
- **[NMF Missions Overview](https://nanosat-mo-framework.github.io/missions.html)**  
- **[AIAA Paper: Achieving On-board Software Autonomy](https://arc.aiaa.org/doi/pdf/10.2514/6.2016-2624)**  
- **[PhiSat-1/2 Mission Reference](https://www.eoportal.org/satellite-missions/phisat-1)**

-------------------------------------------------------------

# **OS³ (Open Source Satellite Simulator)**

**OS³** is an open-source framework based on OMNeT++ for simulating satellite communication networks, providing accurate mobility models, channel characteristics, and realistic environmental data for protocol evaluation and performance analysis.

OS³ typically supports:
- Realistic satellite mobility using NORAD SGP4/SDP4 orbital propagation with real TLE data import.
- Channel modeling including attenuation, weather effects, high-resolution terrain data, and Doppler shifts.
- Protocol simulation for satellite networks with SNR, BER, packet loss, RTT, and jitter analysis.
- 3D visualization of satellite tracks, coverage, and communication links via integrated GUI tools.

## License and Cost

OS³ is open-source software available on GitHub, free to download, modify, and use under a permissive license for research and development.

## Limitations

OS³ focuses on communication protocols and network performance rather than full spacecraft dynamics, attitude control, or on-board software execution. Requires OMNeT++ expertise for advanced customizations.

## Useful References

- **[OS³ OMNeT++ Project Page](https://omnetpp.org/software/2013/08/14/os3-released.html)**  
- **[OS³ GitHub Port](https://github.com/Avian688/os3)**  
- **[OS³ Simulator Overview](https://omnetpp.org/download-items/OS3.html)**  
- **[OS³ Features and Architecture](https://networksimulationtools.com/os3-simulator/)**  
- **[OMNeT++ OS3 Documentation](https://omnet-tutorial.com/omnet-os3/)**

-------------------------------------------------------------

# **OpenSN LEO Satellite Network Emulator**

**OpenSN** is an open-source container-based emulator for large-scale LEO satellite networks like Starlink, enabling realistic execution of routing protocols, network applications, and performance analysis on real kernels with orbital dynamics.

OpenSN typically supports:
- Container virtualization for thousands of satellites with horizontal scalability across multiple machines.
- Realistic orbital propagation, inter-satellite links, and ground station connectivity.
- Execution of distributed routing software (e.g., BGP, OSPF) and real network applications.
- Efficient topology updates, link state management, and performance metrics via key-value database architecture.

## License and Cost

OpenSN is fully open-source software available on GitHub, free to download, modify, and use for research, development, and production LEO network testing.

## Limitations

OpenSN specializes in network-layer emulation rather than full spacecraft simulation, attitude dynamics, or hardware-in-the-loop testing. Requires Docker/container expertise for large-scale deployments.

## Useful References

- **[OpenSN GitHub Repository](https://opensn-library.github.io)**  
- **[OpenSN arXiv Paper](https://arxiv.org/abs/2507.03248)**  
- **[OpenSN Technical Documentation](https://opensn-library.github.io)**  
- **[LEO Satellite Emulation Comparison](https://arxiv.org/html/2507.03248v1)**  
- **[OpenSN Architecture Overview](https://arxiv.org/html/2507.03248v1)**


-------------------------------------------------------------

# **Basilisk Astrodynamics Framework**

**Basilisk** is an open-source C/Python astrodynamics simulation framework for modeling complex spacecraft systems, supporting research-grade orbital mechanics, attitude dynamics, and hardware-in-the-loop scenarios with 3D visualization.

Basilisk typically supports:
- High-fidelity 6-DOF spacecraft dynamics including nonlinear attitude control, flexible body dynamics, and multi-body orbital propagation.
- Modular plugin architecture for sensors (star trackers, gyros), actuators (reaction wheels, thrusters), and environmental effects.
- Flight software simulation with deterministic messaging, fault injection, and Monte-Carlo capability for statistical analysis.
- Vizard 3D visualization using Unity engine for interactive orbit, attitude, and sensor data display across platforms.

## License and Cost

Basilisk is open-source software available on GitHub under a BSD license, free to download, modify, and use for academic, research, and commercial applications.

## Limitations

Basilisk focuses on astrodynamics and attitude control rather than communication networks, payload processing, or full mission operations simulation. Requires C/Python programming for custom modules.

## Useful References

- **[Basilisk Official Website](https://avslab.github.io/basilisk/)**  
- **[Basilisk GitHub Repository](https://github.com/AVSLab/basilisk)**  
- **[Basilisk Documentation](https://basilisk.readthedocs.io)**  
- **[Vizard 3D Visualization](https://avslab.github.io/vizard/)**  
- **[Basilisk Validation Examples](https://github.com/AVSLab/basilisk-examples)**

-------------------------------------------------------------

# **Orekit Space Dynamics Library**

**Orekit** is an open-source Java library for high-precision space flight dynamics, providing accurate orbital propagation, attitude computation, and mission analysis capabilities for professional space operations.

Orekit typically supports:
- High-accuracy orbit propagation with numerical integrators, analytical models, and force models (gravity, drag, radiation pressure, third-body).
- Precise time scales, coordinate transformations, and frame definitions (ITRF, celestial frames, spacecraft-centered).
- Attitude computation, maneuver modeling, and event detection (eclipses, ground station visibility, anomalies).
- Spacecraft state estimation, mission analysis, and propagation with real ephemeris data integration.

## License and Cost

Orekit is open-source software available under the Apache License 2.0, free to download, modify, and use for research, commercial, and mission-critical applications.

## Limitations

Orekit is a low-level dynamics library requiring Java programming expertise and integration into larger simulation frameworks. Does not include 3D visualization or full spacecraft hardware simulation.

## Useful References

- **[Orekit Official Website](https://www.orekit.org)**  
- **[Orekit GitHub Repository](https://github.com/CS-SI/Orekit)**  
- **[Orekit Documentation](https://www.orekit.org/site2/)**  
- **[User Guide and Tutorials](https://www.orekit.org/site2/user-guide.html)**  
- **[Orekit in Flight Operations](https://www.orekit.org/news.html)**

-------------------------------------------------------------

# **NASA GMAT (General Mission Analysis Tool)**

**NASA GMAT** is an open-source software toolkit for space mission design, optimization, and navigation analysis, providing high-fidelity orbit determination, trajectory optimization, and mission planning capabilities.

GMAT typically supports:
- Multi-body orbit propagation with numerical integrators, force models, and real ephemeris data.
- Mission sequencing, maneuver planning, and fuel optimization for launch vehicles and spacecraft.
- Parameter sweeps, genetic algorithms, and nonlinear optimization for trade studies.
- 3D visualization of orbits, ground tracks, and mission events with scripting support.

## License and Cost

GMAT is open-source software available under the NASA Open Source Agreement (NOSA), free to download, modify, and use for research, education, and commercial applications.

## Limitations

GMAT focuses on mission design and trajectory analysis rather than real-time spacecraft simulation, attitude control, or hardware-in-the-loop testing. Requires scripting expertise for complex analyses.

## Useful References

- **[GMAT Official Website](https://software.nasa.gov/software/GSC-17177-1)**  
- **[GMAT GitHub Repository](https://github.com/ChristopherCully/gmat)**  
- **[GMAT Documentation](https://gmatcentral.org/display/GW/GMAT%20Wiki%20Home)**  
- **[GMAT User Guide](https://gmatcentral.org/files/stable/GMAT_UserGuide.pdf)**  
- **[Zenodo GMAT Reference](https://zenodo.org/records/11276605)**

-------------------------------------------------------------

# **NASA Trick Simulation Environment**

**NASA Trick** is an open-source simulation development environment for modeling and simulating complex dynamic systems including spacecraft, launch vehicles, and real-time hardware-in-the-loop scenarios.

Trick typically supports:
- High-fidelity physics modeling with C/C++ dynamics, kinematics, and environmental models.
- Real-time execution with deterministic timing, I/O handling, and hardware interfaces.
- S-function integration with Simulink models and Monte-Carlo capability.
- 3D visualization integration, graphical monitoring, and automated test frameworks.

## License and Cost

Trick is open-source software available under the NASA Open Source Agreement, free to download, modify, and use for research, training, and mission development.

## Limitations

Trick requires significant setup and C/C++ expertise for custom simulations. Focuses on system-level dynamics rather than low-level flight software execution or communication networks.

## Useful References

- **[Trick Official Website](https://trick.hackaday.io)**  
- **[Trick GitHub Repository](https://github.com/nasa/Trick)**  
- **[Trick Simulation Environment Guide](https://nasa.github.io/Trick)**  
- **[Trick User Manual](https://trick.hackaday.io/project/133-trick-simulation-environment/wiki/Trick-Documentation)**  
- **[NASA Trick Applications](https://software.nasa.gov/software/LAR-17117)**

-------------------------------------------------------------

# **SpOCK (Spacecraft Orbital Computations Kit)**

**SpOCK** is an open-source MATLAB/Octave toolkit for spacecraft mission analysis, providing probabilistic orbit propagation, coverage analysis, and conjunction assessment with Monte-Carlo capabilities.

SpOCK typically supports:
- High-fidelity stochastic orbit propagation with perturbations, uncertainties, and covariance realism.
- Sensor coverage, ground station visibility, and communication link analysis.
- Conjunction assessment, maneuver planning, and collision probability computation.
- 3D visualization of probabilistic swaths, coverage maps, and mission scenarios.

## License and Cost

SpOCK is open-source software available under a permissive license, free to download, modify, and use for research, mission planning, and analysis.

## Limitations

SpOCK focuses on orbital statistics and probabilistic analysis rather than real-time attitude control, hardware simulation, or full spacecraft dynamics. Requires MATLAB/Octave environment.

## Useful References

- **[SpOCK Official Repository](https://github.com/daquinoc/SpOCK)**  
- **[SpOCK Documentation](https://spock.readthedocs.io)**  
- **[NASA SpOCK Overview](https://www.nasa.gov/smallsat-institute/space-mission-design-tools/)**  
- **[SpOCK User Guide](https://github.com/daquinoc/SpOCK/blob/master/doc/SpOCK_User_Guide.pdf)**  
- **[SpOCK Validation Examples](https://github.com/daquinoc/SpOCK_examples)**

-------------------------------------------------------------

# **Satellite Dynamics Toolbox (SDT)**

**Satellite Dynamics Toolbox (SDT)** is a MATLAB-based academic toolbox for linear spacecraft dynamics modeling, computing direct and indirect dynamic models of rigid and flexible spacecraft structures with parametric uncertainty support.

SDT typically supports:
- Linear dynamic modeling of spacecraft with main bodies and flexible appendages (solar panels, antennas).
- Kinematic models between body points, rotation transformations, and antisymmetric matrices.
- Parametric uncertainties compatible with MATLAB Robust Control Toolbox for robust control design.
- Data files for example spacecraft configurations with uncertain mechanical parameters.

## License and Cost

SDT is an academic/research toolbox freely available for download, typically under academic use terms. Included in larger SIMULINK libraries like SDTLIB.

## Limitations

SDT focuses on linear structural dynamics modeling rather than nonlinear orbital propagation, real-time simulation, or full mission operations. Requires MATLAB and expertise in robust control design.

## Useful References

- **[SDT Official Page (ISAE-SUPAERO)](https://pagespro.isae-supaero.fr/daniel-alazard/matlab-packages/satellite-dynamics-toolbox.html)**  
- **[SDT v1.3 Package Download](https://pagespro.isae-supaero.fr/daniel-alazard/matlab-packages/satellite-dynamics-toolbox.html)**  
- **[SDT User Guide and Examples](https://pagespro.isae-supaero.fr/daniel-alazard/matlab-packages/sdtlib.html)**  
- **[SDT in SIMULINK Library (SDTLIB)](https://pagespro.isae-supaero.fr/daniel-alazard/matlab-packages/sdtlib.html)**  
- **[Satellite Dynamics Toolbox Paper](https://arxiv.org/pdf/2303.15872.pdf)**

-------------------------------------------------------------

# **MuSCAT (Multi-Spacecraft Concept and Autonomy Tool)**

**MuSCAT** is NASA's open-source MATLAB simulation platform for low-fidelity multi-spacecraft mission concepts and autonomy algorithm testing, supporting both single and constellation missions with integrated subsystem modeling.

MuSCAT typically supports:
- Dual-loop architecture for efficient attitude dynamics and orbital mechanics simulation.
- Comprehensive spacecraft subsystems including navigation, ADCS, power, communications, and payloads.
- Real-time 3D orbit/attitude visualization with mission DART example included.
- Modular extension for custom autonomy algorithms and mission scenarios.

## License and Cost

MuSCAT is open-source software available on GitHub under NASA open source license, free to download, modify, and use for mission concept evaluation.

## Limitations

MuSCAT provides low-fidelity simulation for early-phase evaluation rather than high-fidelity flight software or hardware-in-the-loop testing. MATLAB expertise required.

## Useful References

- **[MuSCAT GitHub Repository](https://github.com/nasa/muscat)**  
- **[MuSCAT Documentation](https://github.com/nasa/muscat/tree/main/Documentation)**  
- **[MuSCAT Overview](https://ntrs.nasa.gov/api/citations/20220017761/downloads/Space_ROS_SciTech.pdf)**  
- **[NASA SmallSat Tools](https://www.nasa.gov/smallsat-institute/space-mission-design-tools/)**  
- **[MuSCAT Mission Examples](https://github.com/nasa/muscat/tree/main/Mission_Scenarios)**

-------------------------------------------------------------

[![WIP](https://img.shields.io/badge/Status-WORK%20IN%20PROGRESS-yellow.svg)](https://github.com/)




