# 4-legged-robot-model
Working on python3

-pybullet and numpy needed to run the simulation.

(run: walking_simulation_example.py)
_______________________________________________________________________

-pybullet, numpy, evdev, pyserial and simple-pid needed to run the robot.

(run: walking_robot.py)
_______________________________________________________________________

more info at: https://www.youtube.com/channel/UCBpFFCjtieDb8WiO7yLvaBw

   https://hackaday.io/project/171456-diy-hobby-servos-quadruped-robot


Here is a simple diagram of how the robot is working:
![alt text](https://github.com/miguelasd688/Quadruped-dog-like-robot/blob/master/esquema.png)

# Comments:

Dependencies:
   pybullet (install it with pip3 install)

Linux old glsl version error workaround:

$glxinfo | grep OpenGL
OpenGL vendor string: Intel Open Source Technology Center
OpenGL renderer string: Mesa DRI Intel(R) 965GM 
OpenGL version string: 2.1 Mesa 19.3.3
OpenGL shading language version string: 1.20
OpenGL extensions:
OpenGL ES profile version string: OpenGL ES 2.0 Mesa 19.3.3
OpenGL ES profile shading language version string: OpenGL ES GLSL ES 1.0.16
OpenGL ES profile extensions:

$MESA_GL_VERSION_OVERRIDE=4.3 MESA_GLSL_VERSION_OVERRIDE=430 python3 walking_simulation_example.py 

glsl versions: https://github.com/mattdesl/lwjgl-basics/wiki/glsl-versions#glsl-versions

