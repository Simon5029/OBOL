---
layout: page
title: Energy
permalink: /energy/
---

This page contains information about energy industry models.

Here is a list of great energy industry models (AI generated content):

-------------------------------------------------------------

# **OSeMOSYS Energy Planning Model**

**OSeMOSYS** is an open-source systems optimization model generator for long-term energy planning, supporting capacity expansion, dispatch, and investment decisions across multiple energy sectors.

OSeMOSYS typically supports:
- Linear programming optimization for technology deployment, fuel supply, and emissions constraints.
- Multi-region, multi-year modeling with electricity, heat, transport, and industry sectors.
- Integration with GNU MathProg, Pyomo, PuLP solvers for flexible deployment.
- Scenario analysis for policy evaluation, decarbonization pathways, and cost optimization.

## License and Cost

OSeMOSYS is open-source under Apache 2.0 license, completely free across all platforms.

## Limitations

Full linear optimization model requires solver expertise. Primarily long-term planning rather than real-time operations.

## Useful References

- **[OSeMOSYS Official Website](https://www.osemosys.org)**
- **[OSeMOSYS GitHub Repository](https://github.com/OSeMOSYS/OSeMOSYS)**
- **[Documentation](https://osemosys.readthedocs.io)**
- **[Tutorials](https://github.com/OSeMOSYS/OSeMOSYS/wiki)**
- **[Community Forum](https://groups.google.com/g/osemosys)**

-------------------------------------------------------------

# **EnergyPlus Building Energy Simulator**

**EnergyPlus** is DOE's open-source whole building energy simulation engine for modeling thermal loads, HVAC systems, lighting, and renewable energy integration.

EnergyPlus typically supports:
- Detailed zone heat balance, HVAC equipment, and renewable systems modeling.
- Weather data integration, daylighting, and occupancy schedules.
- Co-simulation with OpenStudio, FMU, and Python scripting interfaces.
- Annual/hourly energy analysis for code compliance and performance optimization.

## License and Cost

EnergyPlus is open-source under public domain (unrestricted), free for all applications.

## Limitations

Steep learning curve for complex building models. Primarily thermal/energy analysis rather than electrical systems.

## Useful References

- **[EnergyPlus Official Website](https://energyplus.net)**
- **[EnergyPlus GitHub](https://github.com/NREL/EnergyPlus)**
- **[Documentation](https://energyplus.net/documentation)**
- **[Input/Output Reference](https://bigladdersoftware.com/epx/docs)**
- **[Weather Data](https://energyplus.net/weather)**

-------------------------------------------------------------

# **MATPOWER Power System Simulator**

**MATPOWER** is an open-source MATLAB package for steady-state power system simulation and optimization including optimal power flow and economic dispatch.

MATPOWER typically supports:
- AC/DC power flow, optimal power flow, DC OPF, and security-constrained OPF.
- Contingency analysis, available transfer capability, and voltage stability.
- Integration with PYPOWER (Python) and MIPS (multi-period OPF).
- Extensive case files for IEEE test systems and real-world networks.

## License and Cost

MATPOWER is BSD-style license, free for academic/commercial use.

## Limitations

Steady-state analysis only (no dynamic/transient stability). Requires MATLAB or Python environment.

## Useful References

- **[MATPOWER Official Website](https://matpower.org)**
- **[MATPOWER GitHub](https://github.com/MATPOWER/matpower)**
- **[User's Manual](https://matpower.org/docs/MATPOWER-manual.pdf)**
- **[Case Files](https://matpower.org/docs/ref/matpower5.0/caseformat.pdf)**
- **[PYPOWER](https://github.com/rwl/PYPOWER)**

-------------------------------------------------------------

# **PyPSA Power System Analysis**

**PyPSA** stands for Python for Power System Analysis, an open-source toolbox for simulating and optimizing modern power systems including HVDC and storage.

PyPSA typically supports:
- Linear optimal power flow, investment planning, and unit commitment.
- N-1 contingency analysis, stability-constrained OPF, and line switching.
- Sector coupling with heat, transport, and hydrogen networks.
- Network clustering for large-scale transmission grids and distribution networks.

## License and Cost

PyPSA is open-source under MIT license, completely free with Python ecosystem integration.

## Limitations

Requires Python/Atwood expertise. Linearized models may sacrifice some accuracy for speed.

## Useful References

- **[PyPSA Official Website](https://pypsa.org)**
- **[PyPSA GitHub](https://github.com/PyPSA/PyPSA)**
- **[Documentation](https://pypsa.readthedocs.io)**
- **[Examples Gallery](https://pypsa.readthedocs.io/en/latest/examples/)**
- **[Network Clustering](https://pypsa.readthedocs.io/en/latest/components.html)**

-------------------------------------------------------------

[![WIP](https://img.shields.io/badge/Status-WORK%20IN%20PROGRESS-yellow.svg)](https://github.com/)

