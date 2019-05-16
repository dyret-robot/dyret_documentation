# Dynamic Robot for Embodied Testing (`DyRET`)
<span><img src="http://robotikk.net/media/images/dyret_reconfig.gif" alt="DyRET" width="300" align="right" style="margin: 5px"/>

`DyRET` is a four legged (quadruped) robot designed to be a robust and versatile platform for evolutionary experiments with the unique capability of self-changing morphology. The robot runs on [ROS](https://ros.org), and uses [Gazebo](http://gazebosim.org/) for simulated experiments.

<a href="http://certificate.oshwa.org/"><img src="http://robotikk.net/media/images/dyret_oshw.png" alt="OSHW" width="180" style="margin: 20px" align="right"/></a>
## Documentation
The [wiki](https://github.com/dyret-robot/dyret_documentation/wiki)
contains all documentation for how to setup and interact with `DyRET`.

## License
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)  

`DyRET` is a certified open source hardware project, and both code and design is freely available. All software is available under the [GPL-3](http://www.gnu.org/licenses/gpl.html) license, and the hardware is available under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license. Please keep references to the `DyRET` project and cite the [fundamental paper](https://arxiv.org/pdf/1803.05629) if used in academic work. Bibtex reference is provided below:

~~~~~~~~
@inproceedings{nygaard_ICRA19,
  author        = {T{\o}nnes F. Nygaard and
                   Charles P. Martin and
                   Jim Torresen and
                   Kyrre Glette},
  title         = {{Self-Modifying Morphology Experiments with DyRET:
                   Dynamic Robot for Embodied Testing}},
  booktitle     = {{IEEE International Conference on Robotics and Automation (ICRA)}},
  year          = {2019},
  volume        = {},
  number        = {},
  pages         = {}
}
~~~~~~~~

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

## Media

Please visit our [Youtube channel](https://www.youtube.com/playlist?list=PLRBn4we2TECqjgtN5yU7JDioblYnBLBsU) for videos of `DyRET`.
Press photos and non-watermarked videos available to journalists and others on request.

[Techxplore.com](https://techxplore.com/news/2019-04-method-enable-robust-locomotion-quadruped.html), 16. april 2019  
Interview about our work integrating foot sensors on `DyRET`.

[Wired.com](https://www.wired.com/story/how-roboticists-are-copying-nature-to-make-fantastical-machines/), 28. june 2018  
Video about bio-mimicry including DyRET and other interesting robots.

[Nbcnews.com](https://www.nbcnews.com/mach/video/how-a-shape-shifting-robot-is-learning-from-its-mistakes-1263383619716), 25. june 2018   
Video showing DyRET and some outdoor experiments.

[Digitaltrends.com](https://www.digitaltrends.com/cool-tech/dyret-robot-learns-to-walk/), 23. may 2018  
Short interview about the DyRET robot and evolutionary robotics.

[Wired.com](https://www.wired.com/story/the-shape-shifting-robot-that-evolves-by-falling-down/), 18. may 2018  
Interview about the DyRET robot and our work at the University.

## Papers
Papers that describe or utilize `DyRET` for experiments. The list is reverse chronological order, and the platform paper is highlighted.

- [Evolved embodied phase coordination enables robust quadruped robot locomotion (to appear in GECCO 2019)](https://folk.uio.no/jorgehn/tegotae/)
- [**Self-Modifying Morphology Experiments with DyRET: Dynamic Robot for Embodied Testing (to appear in ICRA 2019)**](https://arxiv.org/pdf/1803.05629)
- [Evolving Robots on Easy Mode: Towards a Variable Complexity Controller for Quadrupeds (EvoStar 2019)](https://www.springerprofessional.de/en/evolving-robots-on-easy-mode-towards-a-variable-complexity-contr/16644622)
- [Dynamic mutation in MAP-Elites for robotic repertoire generation (ALIFE 2018)](https://www.mitpressjournals.org/doi/abs/10.1162/isal_a_00110)
- [Real-World Evolution Adapts Robot Morphology and Control to Hardware Limitations (GECCO 2018)](https://dl.acm.org/citation.cfm?id=3205567)
- [Combining MAP-Elites and Incremental Evolution to Generate Gaits for a Mammalian Quadruped Robot (EvoStar 2018)](https://link.springer.com/chapter/10.1007/978-3-319-77538-8_48)
- [Multi-objective Evolution of Fast and Stable Gaits on a Physical Quadruped Robotic Platform (ICES 2016)](https://ieeexplore.ieee.org/document/7850167/)


## Contact us
If you have suggestions or questions on the documentation or use of the robot, please create an issue on Github so answers and solutions can be shared with others.

For other inquiries, please send an email: [tonnesfn@ifi.uio.no](mailto:tonnesfn@ifi.uio.no)
