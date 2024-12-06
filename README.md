# sonar msgs

## Overview

- The Sonar Interfaces package contains all services and message definitions designed for sonar-to-point-cloud and sonar-to-image conversion.

**Keywords:** ROS2, Services, Messages.

## License

The source code is released under a [Apache License 2.0](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/blob/master/LICENSE).

**Author:** SENAI CIMATEC Team\
**Affiliation:** Brazilian Institute of Robotics \
**Maintainer:** Autor, RBiM Team


The `sonar_msgs` package has been tested under:

- ROS 2

  - [![colcon-action-runner](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/actions/workflows/colcon-action-runner.yaml/badge.svg)](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/actions/workflows/colcon-action-runner.yaml) - [`Humble Hawksbill`](https://docs.ros.org/en/humble/Releases/Release-Humble-Hawksbill.html) and Ubuntu 22.04.1 LTS (Jammy Jellyfish).

### Projects Development Status

| Repository | Latest | Linters |  Doxygen |  Coverage |
|---         |---     |---    |--- |--- |
| `sonar_msgs`| [![Humble](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/actions/workflows/colcon-action-runner.yaml/badge.svg)](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/actions/workflows/colcon-action-runner.yaml) | [![lint-runner](https://github.com/Brazilian-Institute-of-Robotics//actions/workflows/runner-ci-lint.yaml/badge.svg)](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/actions/workflows/runner-ci-lint.yaml) | - | - |

### Dependencies

- N/a.

### Building and install
  - [Install ROS 2 packages](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html#id4)

- **Building with colcon**

  - To build from source, clone the latest version from this repository into your `colcon` workspace and compile the package using


```bash
cd YOUR_WORKSPACE
source /opt/ros/foxy/setup.bash
colcon build --packages-select sonar_msgs
source install/local_setup.bash
```

- **Building from autoproj**

  - See build configuration based on autoproj

  - After Installation and configuration of autoproj, run the following commands:

```sh
cd YOUR_WORKSPACE
source env.bash
amake sonar_msgs --verbose
source devel/setup.bash
```
### Unit Tests
- N/a.

## Launch file
- N/a.

## Bugs & Feature Requests

- Please report bugs and request features using the [Issue Tracker](https://github.com/Brazilian-Institute-of-Robotics/sonar_msgs/issues).
