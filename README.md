# Instructions Before Use
- Clone this branch into the `src` directory of your workspace.
- Build your package with `catkin_make` or `catkin build` (whichever you used to build your workspace).
- Source your workspace.
- Make the `teleop_gui.py` file executable by running `sudo chmod +x /path/to/teleop_gui.py`.
- Run `rosrun ros-playground teleop_gui.py`.

#### Example Use
```
$ cd ~/my_ws/src
$ git clone --branch ros-noetic-devel https://github.com/shawbicc/ros-playground.git
$ cd ..
$ catkin_make
$ sudo chmod +x src/ros-playground/scripts/teleop_gui.py
$ source devel/setup.bash
$ rosrun ros-playground teleop_gui.py
```
