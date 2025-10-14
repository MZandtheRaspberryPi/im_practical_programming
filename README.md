# im_practical_programming
This is a landing page for a collection of scripts and projects, some practical and useful day to day, others with no redeeming usefulness other than fun! See below projects and links:

## Big Projects

### quadruped_control via MPC
This was a fun project where I designed and implemented a controller using the unicycle model and model predictive control (MPC) for a quadruped. See a video demo [here](https://youtu.be/lkiq3odg65g).

![quad_traj](./quad_demo.png)

![quad_traj_plot](./2025_03_28_01-56-58-11.9.png)

### quadruped autonomy
This was a fun project where I created software and integrated existing software to enable an autonomy stack for the Unitree Go1 Robot. I also designed and fabricated the sensor backpack including picking hardware components and integrating them. See a video demo [here](https://youtube.com/shorts/0-Z05GkkNnk?feature=share). It uses the CMU Navigation Framework [here](https://www.cmu-exploration.com/) as a base with some glue of other modules to hold it together.

This was the first test of the system. Note the crane for safety.
![quad_auto_first_test](./20250311_171321.jpg)

This is an example of what the quadruped sees:
![quad_what_sees](./20250311_205157.jpg)

I did this in simulation before doing it in the real world. You can see a sim demo [here](https://youtu.be/hgMfq3n4iZc).
![spot_what_sees](./spot_demo_nav.png)

### Travelling Salesman with Drones
This was a project I did to solve the Travelling Salesman problem in 3D with aerial robotics. Find the code [here](https://github.com/MZandtheRaspberryPi/mapping_path_planning). I used Gazebo to simulate the system and a C++ library I created to solve a path to take pictures of aruco markers scattered throughout the environment. I wrapped the C++ library with a ROS2 interface. See a video demo [here](https://youtu.be/jcM5ZJ5zUu0).

![with_gazebo](full_path_with_Gazebo.png)  
![aruco](arucos.png)  
![profiling](runtimes_objectives.png)  

### drone_swarm
This was a group project I did to control swarms of drones through various obstacles. I implemented a model predictive controller for a flexible number of drones that tracked reference trajectories, allowing transitions between formations like squares and arrows while tracking. See a video demo [here](https://youtu.be/StXTDl_aGLg).  
![swarm1](swarm1.PNG)  
![swarm2](swarm2.PNG)
![swarmmpc1](mpc_tuning.png)  
![swarmmpc2](mpc_diagram.PNG)  

### state estimation with UKF
This is a project where I designed a circuit board and programmed it with a state estimator and a fluid simulator as a gift for a professor. See a video demo [here](https://www.youtube.com/shorts/ypMqFLmJ22k) and the repo [here](https://github.com/MZandtheRaspberryPi/cuppa).  
![cuppa_Gif](cuppa_gif.gif)  

### digital_compass
This is a project where I designed, manufactured, and coded a digital compass that uses an inertial measurement unit (IMU) to estimate orientation in 3d-space. I implemented an extended kalman filter to (EKF) to do the estimation. Find the repo [here](https://github.com/MZandtheRaspberryPi/digital_compass). A video explanation is available [here](https://www.youtube.com/shorts/Pg_2u4VAHLg) and a video demo is available [here](https://www.youtube.com/shorts/pv6mBfAY-nU).  
![compass_pic](IMG_0004.jpg)  
![compass_pic_2](IMG_20231012_140624.jpg)  
![compass_demo](82od5m.gif)  

### quadruped_learning
This is a project where I taught a robot dog to walk in simulation. I used imitation learning and inverse reinforcement learning. Find a video demo [here](https://www.youtube.com/watch?v=ahcJJIknLHg) and the repo [here](https://github.com/MZandtheRaspberryPi/quadruped_learning).  
![motion_retargeting](example_motion_retargeting.png)  

### robodanceproject.com
This is a project where I implemented a front end in Angular and a back end in C++ to explore and visualize forward kinematics for a quadruped robot.  I deployed this using Amazon Web Service's Lightsail. Find the repo [here](https://github.com/MZandtheRaspberryPi/doggy_dance_project). 
![robo_dance](robo_dance_project.png)  

### think_like_an_octopus
This was an in-depth blog post I wrote around options for python multiprocessing including threading, multiprocessing, calling C++ code, and numpy. Find the repo [here](https://github.com/MZandtheRaspberryPi/think_like_an_octopus) with a .pdf and links to the post.  
![octopus_blog_pic](octopus_blog.PNG)  

### robo_tentacle
This is a project where I designed a soft robotic manipulator based on continuum manipulators. I then made the mould, the robot by casting sillicon, and got it to pick objects up. See a video demo [here](https://youtube.com/shorts/yAXXw5yY0Hg?feature=share).

![robopickup](./robot_tentacle1.png)
![robohold](./robo_tentacle2.png)

### led_catan

This was a project where I designed and fabricated a Settlers of Catan inspired game board. It used custom circuit boards for hexagonal tiles underneath a 3d-printed game board that diffused the lights. It can randomize the board, and remembers the current game board if a power-outtage occurs.

![catan](./20251011_211733.jpg)

### mycobot
I prepared a robot arm to pick and place objects and use computer vision for students to use in a hackathon. See more details [here](https://github.com/MZandtheRaspberryPi/mycobot).
![full_setup](./20240926_173535.jpg)
![demo_pic](./demo_pic_cobot.png)

### crystal_ball
This was a fun project where I made an orb that mounted to a cane like a witch's staff. Find the repo [here](https://github.com/MZandtheRaspberryPi/crystal_ball) with a write up and more pictures.
![witch_staff](witch_staff.jpg)

### toulouse_rover
This was a fun project I did to build an autonomous car, using a lidar. I did the robot design, hardware, and software by myself. It supports kinematics for differential drive, skid steering, and omni wheels, and a fourth fixed slow speed mode which is good for autonomous driving. It uses ROS and hector_mapping as well as move_it to do mapping and path planning. You can find more details [here](https://github.com/MZandtheRaspberryPi/toulouse_rover), and see a video explanation [here](https://youtu.be/9rG0YduM39s).    

![toulouse](./20220618_103051.jpg)
![autonomous_toulouse](./toulouse_demo.gif)

### buddy_singer
a repository to get a robot to sing from MIDI files. See a video demo [here](https://www.youtube.com/shorts/IcYGP01VqKk).
![singing_screenshot](./singing_buddy.PNG)

### all_seeing_drone  
A project to introduce autonomous movement and face-following for a robolink CoDrone. I used the CoDrone API which lets you command roll, pitch, yaw, and throttle, but built a lot of functionality on top of that to do tracking, and in some cases rewrote bits of the CoDrone API to work with my needs. See the README [here](https://github.com/MZandtheRaspberryPi/all_seeing_drone).  

![Demo of Autonomous Drone](drone.gif)  
Bottom left: processed drone video with debug information  
Top left: cell phone camera in corner of room, showing drone flying  
Right: raw drone input video  
Notice it tracking me!

Here's a youtube video showing off the project. There's a link in the description of this video to another video that is more technical and shows some of the project work.
[Making a PB&J with autonomous drone camera-person](https://www.youtube.com/watch?v=P_NQB7phWnQ&t)  

### great_ball_project
This project uses Asyncronous Real-Time Communication (via the python aiortc library) to send video from a server to a client. This video is of a green ball bouncing. The client then uses computer vision to find the center of the ball and send it back to the server which displays an error from the true value.    

Libraries used in include aiortc, numpy, opencv-python, and multiprocessing. In the below GIF, the window on the right has the raw frames from the server. The image on the left is overlaying a small blue dot on the calculated center, for display purposes. Unit tests, logging, config files, and more were added for code quality. Docker images and a deployment using Minikube were done as well.    
![great_ball_proj](great_ball_demo.gif)  

### holiday_project_2023
I designed a custom circuit and printer circuit board using a 555 timer and a 4017 decade counter to be my christmas cards for 2023. You can find the files [here](https://github.com/MZandtheRaspberryPi/holiday_project_2023) and a video demo [here](https://youtube.com/shorts/1BrFW9uY18g?feature=share).  
![pcb_render](render_pcb_snowflakev62.png)  
![pcb_gif](holiday_proj_2023.gif)  

### my_bittle
This is a project where I integrated a camera sensor, a robot dog, and a raspberry pi to control the dog with computer vision. You can see a video demo [here](). You can find one python library I created to control the robot dog [here](https://pypi.org/project/my-bittle/) and another python library to get images from the camera [here](https://pypi.org/project/my-mu3/). The demo code for integration is [here](https://github.com/MZandtheRaspberryPi/bittle_demo). A writeup blog post is [here](https://www.hackster.io/mzandtheraspberrypi/robot-dog-sees-me-64e658).  

![bittle-demo](./bittle-demo.gif)


### Spot Micro Robot
This was a fun project where I 3d printed the robot, planned the hardware, assembled, and used a fellow robot builder's ROS Repo to get it walking. I contributed a bit to the robot builder's ROS repo as well. It was mainly a hardware and electronics project for me. Check it out [here](https://github.com/MZandtheRaspberryPi/spot_micro_demo).   
![spot_micro_demo](./spot_micro_demo.gif)   

### robo_arm
This is a robot arm project that I built from the ground up, including the software. It has two capabilities. The first is an arduino based arm that can be controlled via onboard joysticks and displays output to an OLED screen as it moves in x, y, z space with an inverse kinematic model. The second is a ROS Powered version that uses rosserial to communicate with the master node, and allows publishing of messages on a topic to command the arm in x, y, z coordinates. You can get to the repo [here](https://github.com/MZandtheRaspberryPi/robo_arm).  
![roboarm](roboarm.gif)  

[Here](https://www.youtube.com/watch?v=9vvvBXWQKJA) is a demo of the arduino based version of the arm, and [here](https://www.youtube.com/watch?v=Fptv3H4Jj54) is a demo of the ros based version of the arm.  

### prod_disaster_counter 
This was a fun project to make a little device that can count things for people, like days in a row they've meditated, practiced a musical instrument, or gone for a walk. I made two versions of this. The first was hastily done on a prototyping board, the second was designed and manufactured to be prettier and more functional. You can find the documentation including cad, ecad, and code [here](https://github.com/MZandtheRaspberryPi/prod_disaster_counter).  

You can see a video demo [here](https://www.youtube.com/watch?v=l-LTvP333-I).  
![demo_gif](./ezgif.com-gif-maker.gif)  

### Ultrasonic Bat
This was a project I organized and led with a group of friends. It is a small bat to hang on a christmas tree or put on a desk, that has ultrasonic sensors, RGB lights in the wings, and an OLED screen for a face. It can react when it sees things in front of it! I did all the 3d design and printing, as well as some of the software work relating to the oled and facial animations. I also coordinated with the hardware group, the software group, and the design group to make sure all the intermediate pieces worked together in the end product. You can find more info [here](https://github.com/MZandtheRaspberryPi/holiday_project_2022/).  
![ultrasonic bat](20221215_195046.jpg)  

### magic_box
This was a magical light box I built for a friend getting married. It has animations, looks pretty, and lets the user set the color for some of the animaetions. You can get to the repo with more details [here](https://github.com/MZandtheRaspberryPi/magic_box).  
![magic box 1](20220318_081823_cropped.jpg)  
![magic box 2](20220316_223055.jpg)  

### Buddy Robot Dance with ROS
This was a fun project to get a robot to dance using ROS. I used a robot from Slant Concepts and re-coded it to work with ROS, via rosserial and a bluetooth connection. Check it out [here](https://github.com/MZandtheRaspberryPi/ros_buddy).    
![buddy_dance](./buddy_dance.gif)    

### go2 wheels backback
I seem to build a lot of robot backpacks, with sensors and such to do autonomy. See another video demo [here](https://youtu.be/0aYjFsQXcZs).

![go2backpack](./go2backpack.png)

### Pi Watch    
This was a project to make a raspberry pi watch that can check buses near my apartment, show the weather, and turn off with button presses. Check out the repo [here](https://github.com/MZandtheRaspberryPi/pi_watch) and a video showing off the project [here](https://www.youtube.com/watch?v=JhEXCvS3W6M).    
![pi_watch.gif](./pi_watch.gif)   

### Tableau Wine Night
This was a fun project to create a dataset from a winetasting I did among friends. From there I analyzed the data, created metrics, and presented an interactive visualization on it via Tableau Public. Find it [here](https://public.tableau.com/app/profile/michael.ziegltrum/viz/WineNight/TheStoryofWineNight).  
![wine_night](./wine_night.PNG)  


## Smaller Projects

### bike_mudgaurd
I did some 3d-modelling and manufacturing to create a (not great) mudgaurd for my bike. Currently on v2. Find the repo [here](https://github.com/MZandtheRaspberryPi/bike_mudgaurd).  
![mudgaurd](./20240810_105704.jpg)  

### headless_pi_setup
A guide on how to setup a Raspberry Pi with an emphasis on security, without a keyboard or display for the Pi. See the guide [here](https://github.com/MZandtheRaspberryPi/pi_headless_setup)!   
![pi_guide.png](./pi_guide.png)    

### Alexa and Raspberry Pi Lamp
A demo on how to control a Raspberry Pi Lamp using an Echo Dot. See the repo with links to guides [here](https://github.com/MZandtheRaspberryPi/alexa_lamp).    
![alexa_light_demo](./alexa_light_demo.gif)

### Mood Lamp Guide
Here's a guide that is more a collection of tutorials to help you get your raspberry pi mood lamp kit from pimoroni up and running. Check it out [here](https://github.com/MZandtheRaspberryPi/mood_lamp_guide/blob/main/README.md).    
![alexa_light_demo](./alexa_light_demo.gif)

### Minecraft Server on your Pi
This has some links to guides to setup a minecraft server on your pi, as well as some tips on running the server and extra commands! Check it out [here](https://github.com/MZandtheRaspberryPi/pi_minecraft/blob/main/README.md).     
![minecraft](./minecraft.png)

### R2D2 Sculpture with Amazon Echo Inside
This was a fun project to slice and print out some models I found and assemble them. Check it out [here](https://github.com/MZandtheRaspberryPi/r2d2_echo_stand/blob/main/README.md).     
![r2d2](./20210220_140757.jpg)  
