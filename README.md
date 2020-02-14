# Project 2, Go Chase It!
## Udacity Robotics Software Engineer Nanodegree
Go Chase It! project of the Robotics Software Engineer Nanodegree program from Udacity.

## How to Launch the simulation?

#### Create a catkin_ws, feel free to skip if you already have one!
```sh
$ cd /home/workspace/
$ mkdir -p /home/workspace/catkin_ws/src/
$ cd catkin_ws/src/
$ catkin_init_workspace
$ cd ..
```

#### Clone the package in catkin_ws/src/
```sh
$ cd /home/workspace/catkin_ws/src/
$ git clone https://github.com/willhunt/robo_nd_project2.git robo_nd_project2
```

#### Build the `obo_nd_project2` package
```sh
$ cd /home/workspace/catkin_ws/ 
$ catkin_make
```

#### After building the package, source your environment
```sh
$ cd /home/workspace/catkin_ws/
$ source devel/setup.bash
```

#### Make sure to check and install any missing dependencies
```sh
$ rosdep install -i obo_nd_project2
```

#### Once the `robo_nd_project2` package has been built, you can launch the simulation environment using
```sh
$ roslaunch obo_nd_project2 world.launch
```


