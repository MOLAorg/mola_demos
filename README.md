# mola_demos
Demo and example launch files for MOLA

Note that there are launch files for both, ROS 2 and standalone builds of MOLA. 

## Examples and demos

Write me!


## Build and install
Refer to the [root MOLA repository](https://github.com/MOLAorg/mola).

## Docs and examples
See this package page [in the documentation](https://docs.mola-slam.org/latest/modules.html).


### Read an external Ouster lidar into MOLA

```bash
# In one terminal
mola-cli -c  $(ros2 pkg prefix --share mola_demos)/launch/ros2_ouster_just_view.yaml

# In another terminal:
ros2 bag play my_lidar_dataset.mcap
```


## License
This package is released under the BSD-3 license.
