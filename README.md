# im_practical_programming
This is a landing page for a collection of scripts and projects, some practical and useful day to day, others with no redeeming usefulness other than fun! See below projects and links:

## Big Projects

### all_seeing_drone  
A project to introduce autonomous movement and face-following for a robolink CoDrone. See the README [here](https://github.com/MZandtheRaspberryPi/all_seeing_drone).  

![Demo of Autonomous Drone](drone.gif)  
Bottom left: processed drone video with debug information  
Top left: cell phone camera in corner of room, showing drone flying  
Right: raw drone input video  
Notice it tracking me!

Here's a youtube video showing off the project. There's a link in the description of this video to another video that is more technical and shows some of the project work.
[Making a PB&J with autonomous drone camera-person](https://www.youtube.com/watch?v=P_NQB7phWnQ&t)  

### Spot Micro Robot
This was a fun project where I 3d printed the robot, planned the hardware, assembled, and used a fellow robot builder's ROS Repo to get it walking. I contributed a bit to the robot builder's ROS repo as well. Check it out [here](https://github.com/MZandtheRaspberryPi/spot_micro_demo).   
![spot_micro_demo](./spot_micro_demo.gif)   

### robo_arm
This is a robot arm project that has two capabilities. The first is an arduino based arm that can be controlled via onboard joysticks and displays output to an OLED screen as it moves in x, y, z space with an inverse kinematic model. The second is a ROS Powered version that uses rosserial to communicate with the master node, and allows publishing of messages on a topic to command the arm in x, y, z coordinates.
![roboarm](roboarm.gif)  

[Here](https://www.youtube.com/watch?v=9vvvBXWQKJA) is a demo of the arduino based version of the arm, and [here](https://www.youtube.com/watch?v=Fptv3H4Jj54) is a demo of the ros based version of the arm.  

### Buddy Robot Dance with ROS
This was a fun project to get a robot to dance using ROS. I used a robot from Slant Concepts and recoded it to work with ROS, via rosserial and a bluetooth connection. Check it out [here](https://github.com/MZandtheRaspberryPi/ros_buddy).    
![buddy_dance](./buddy_dance.gif)    

### Pi Watch    
This was a project to make a raspberry pi watch that can check buses near my apartment, show the weather, and turn off with button presses. Check out the repo [here](https://github.com/MZandtheRaspberryPi/pi_watch) and a video showing off the project [here](https://www.youtube.com/watch?v=JhEXCvS3W6M).    
![pi_watch.gif](./pi_watch.gif)   

## Smaller Projects

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
