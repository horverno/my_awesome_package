# `my_awesome_package` package
ROS 2 C++ package.
## Packages and build

It is assumed that the workspace is `~/ros2_ws/`.

### Clone the packages
``` r
cd ~/ros2_ws/src
git clone https://github.com/horverno/my_awesome_package
```

### Build ROS 2 packages
``` r
cd ~/ros2_ws
colcon build --packages-select my_awesome_package
```

Don't forget to `source` before ROS commands.

``` r
source ~/ros2_ws/install/local_setup.bash
```

``` r
ros2 launch my_awesome_package launch_example1.launch.py
```