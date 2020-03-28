# Project 2, Go Chase It!
## Udacity Robotics Software Engineer Nanodegree
Go Chase It! project of the Robotics Software Engineer Nanodegree program from Udacity.

## How to Launch the simulation?

#### Clone the package in catkin_ws/src/
```sh
$ cd /home/<project folder>/
$ git clone https://github.com/willhunt/robo_nd_project2.git robo_nd_project2
```

#### Build the `robo_nd_project2` package
```sh
$ cd /home/<project folder>/ 
$ catkin_make
```

#### After building the package, source your environment
```sh
$ cd /home/<project folder>/
$ source devel/setup.bash
```

#### Make sure to check and install any missing dependencies
```sh
$ rosdep install -i my_robot
$ rosdep install -i ball_chaser
```

#### Once the `robo_nd_project2` package has been built, you can launch the simulation environment using:
```sh
$ roslaunch my_robot world.launch
```

#### In a new terminal launch the ball chaser node:
```sh
$ cd /home/<project folder>/
$ source devel/setup.bash
$ cd roslaunch ball_chaser ball_chaser.launch
```

#### Optionally view the RGB camera feed, in a new terminal enter:
```sh
$ cd /home/<project folder>/
$ source devel/setup.bash
$ rosrun rqt_image_view rqt_image_view  
```

