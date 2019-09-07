## ELAS - Cyphy(ARM)

ROS packages containing a wrapper for libelas, a stereo matching library. ARM-compatible implementation. Uses https://github.com/otim/SSE-to-NEON to translate SSE SIMD functionality to ARM-compatible NEON SIMD.

### Installation Instructions

To install the package, clone this repository into your workspace:

```
cd catkin_ws/src
git clone https://github.com/Nekhera/cyphy-elas-ros-arm.git
```

Then build the `libelas` and `elas_ros` packages:

```
catkin build 
```

An example launch file is provided in ``elas_ros/launch/elas.launch``. 
