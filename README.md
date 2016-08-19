# ps4_ros
Sony PlayStation 4 DualShock®4 node joy_msg to twist_msg

# Installation
1. Install __ds4dr__: `$sudo pip install ds4drv` 
1. Install __ros-joy__: http://wiki.ros.org/joy
1. Go into pairing mode with PS4: Playstation button + share button for ~5 sec
1. Run `ds4drv` from command line
  1. This will output something like _Created devices /dev/input/jsX
  1. __/dev/input/jsX__ is important
  1. `$sudo chmod a+rw /dev/input/jsX`
1. _to be continued_
