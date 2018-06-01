<img src="https://i.imgur.com/eRFsYHL.jpg" alt="DyRET" width="300" align="right" />

`DyRET` is a four legged (quadruped) robot designed to be a versatile experiment platform for evolutionary experiments with the unique capability of changing morphology! The robot supports [ROS](https://ros.org) and [Gazebo](http://gazebosim.org/) is supported for simulated experiments.

## Documentation
The [wiki](https://github.com/dyret-robot/dyret_documentation/wiki)
contains documentation for how to interact with `DyRET`.

## Software
The following packages are all based on [ROS](https://ros.org) and tested with [Kinetic](https://wiki.ros.org/kinetic), [Lunar](https://wiki.ros.org/lunar/) and [Melodic](https://wiki.ros.org/melodic)
- [`dyret_common`](https://github.uio.no/robin/dyret_common)
    - This package contains the shared messages and services for `DyRET`.
- [`dyret_hardware`](https://github.uio.no/robin/dyret_hardware)
    - ROS integration for real-world robot.
- [`dyret_simulation`](https://github.uio.no/robin/dyret_simulation)
    - ROS/Gazebo simulation of `DyRET`.
- [`dyret_controller`](https://github.uio.no/robin/dyret_controller)
    - Inverse kinematic controller for `DyRET`.

## Papers
Papers that describe or utilize `DyRET` for experiments. The list is chronological and important papers should be highlighted.

- [Multi-objective Evolution of Fast and Stable Gaits on a Physical Quadruped Robotic Platform](http://heim.ifi.uio.no/kyrrehg/pubs/nygaard-ices2016.pdf)
- [Combining MAP-Elites and Incremental Evolution to Generate Gaits for a Mammalian Quadruped Robot](https://link.springer.com/chapter/10.1007/978-3-319-77538-8_48)
- [**Self-Modifying Morphology Experiments with DyRET: Dynamic Robot for Embodied Testing**](https://arxiv.org/pdf/1803.05629)

