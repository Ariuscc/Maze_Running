The Maze-Running game

The project is based on object-oriented C++ using OpenGl and GLFW as well as non-commercial libraries: 

-stb_image for texturing objects, allows loading .jpg .png files,

-GLM for modeling and transformation of three-dimensional objects,

-GLAD for loading/storing pointers

In addition, we wrote our own libraries:

-camera.h is responsible for the operation of the first-person camera,

-shader_m.h is responsible for loading shaders from files (files with extensions .vs and . fs) and managing them

![image](https://github.com/user-attachments/assets/4a57f8ad-21fe-4b67-ab1f-c41e0945b203)

Game elements: 

-three-dimensional objects: cubic dices with box texture and transparent red “X”,

-map: complicated maze composed of these three-dimensional objects, built based on the following layout:

![image](https://github.com/user-attachments/assets/67a139b9-2e9c-4630-bc00-4b3ace3f3ddb)

-collision model: when we collide with the wall we are slightly bounced, 

-free camera: we can move around the map with the WSAD keys and look around freely in the three-dimensional space with the mouse, 

-to win you need to pass the maze from the starting point to the finish line.

Good luck!
