# Rasterization, OpenGL, and GLSL

![dragon](screenshots/dragon.png)

The code structure is similar to the ray tracing project. The `camera` class loads the camera configurations and store the view and projection matrices. The shape classes loads `param1` and `param2` and generate tessellation for the four implicit shapes. Files in the utils folder parse the scenefile, get the scene data, and load the shader files. The `realtime` class has `intializeGL` and `paintGL` methods, which stores the four shapes on the GPU based on `param1` and `param2` and iterates through the scene objects and render it on the screen using the vertex shader (object space -> world space & projection plane) and fragment shader (phong lighting computation) in the resources/shaders directory. 

Apart from the four simple shapes, the code also supports mesh input. A pre-existing .obj mesh loader called `tinyObjLoader` is used. I also implemented an .obj file loader from scratch, which I named it by `randyObjLoader` in the `utils` folder.

The code also supports point and spot lights, real-time movement in the scene using the keyboard and mouse, and a post-processing stage with an invert filter and a sharpen kernel filter.

The shader also supports object textures.

### Remark:
<b style="red">IMPORTANT: DON'T BE LAZY. ALWAYS CHECK THE RETURN VALUE OF</b> `glGetUniformLocation` <b>BEFORE SENDING THE VARIABLES TO THE GPU.</b>
<details>
<summary>LESSON</summary>
I debugged for many hours checking what is wrong with my specular light output. Finally, I find that when getting the `directionToCamera` value using `camPosition - worldSpacePosition3D`, I send the camera eyePos value to a variable called `camPos` but not `camPosition`, which caused camPosition to be something else! To avoid this, I think I should check the `glGetUniformLocation` first. If the location value is not `-1`, then I can proceed to send the variable to the GPU.
</details>

## Reference
[https://cs1230.graphics/projects](https://cs1230.graphics/projects).
