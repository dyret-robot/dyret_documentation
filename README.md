# `DyRET`
<img src="http://www.robotikk.net/images/dyret_reconfig.gif" alt="DyRET" width="300" align="right" />

`DyRET` is a four legged (quadruped) robot designed to be a robust and versatile platform for evolutionary experiments with the unique capability of self-changing morphology. The robot runs on [ROS](https://ros.org), and uses [Gazebo](http://gazebosim.org/) for simulated experiments.

## Documentation
The [wiki](https://github.com/dyret-robot/dyret_documentation/wiki)
contains all documentation for how to setup and interact with `DyRET`.

## License
DyRET is a fully open source project, and both code and design is freely available. All software is available under the [GPL-3](http://www.gnu.org/licenses/gpl.html) license, and the hardware is available under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license. Please keep references to the DyRET project and cite the [fundamental paper](https://arxiv.org/pdf/1803.05629) if used in academic work.

## Sub-repositories
The following packages are all based on [ROS](https://ros.org) and tested with [Kinetic](https://wiki.ros.org/kinetic), [Lunar](https://wiki.ros.org/lunar/) and [Melodic](https://wiki.ros.org/melodic). All documentation is on the common [wiki](https://github.com/dyret-robot/dyret_documentation/wiki), and not in individual repositories.

#### Software
- [`dyret_common`](https://github.com/dyret-robot/dyret_common)
    - This package contains the shared messages and services for `DyRET`.
- [`dyret_hardware`](https://github.com/dyret-robot/dyret_hardware)
    - ROS integration for real-world robot.
- [`dyret_simulation`](https://github.com/dyret-robot/dyret_simulation)
    - ROS/Gazebo simulation of `DyRET`.
- [`dyret_controller`](https://github.com/dyret-robot/dyret_controller)
    - Inverse kinematic controller for `DyRET`.

#### Hardware and firmware
- [`dyret_actuatorBoard`](https://github.com/dyret-robot/dyret_actuatorBoard)
    - This package contains the firmware and PCB design of the actuatorBoard.

The CAD design is currently available as a [zip-download](http://robotikk.net/sources/cad.zip), but future versions will be converted to a version-controlled release.

## Papers
Papers that describe or utilize `DyRET` for experiments. The list is chronological and important papers are highlighted.

- [Multi-objective Evolution of Fast and Stable Gaits on a Physical Quadruped Robotic Platform](http://heim.ifi.uio.no/kyrrehg/pubs/nygaard-ices2016.pdf)
- [Combining MAP-Elites and Incremental Evolution to Generate Gaits for a Mammalian Quadruped Robot](https://link.springer.com/chapter/10.1007/978-3-319-77538-8_48)
- [**Self-Modifying Morphology Experiments with DyRET: Dynamic Robot for Embodied Testing**](https://arxiv.org/pdf/1803.05629)
