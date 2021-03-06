# CS330
CS330 @SNHU 

Project Reflection

At the start of this term, my knowledge of OpenGL was close to zero. I knew of OpenGL and the applications that could be created using the given libraires. This course has
given me a better appreciation for modeling applications like Blender and Unity. I was eager to learn and apply the material taught in this course. After reviewing the 
requirements for the final project, I had several ideas of what I wanted to recreate. I wanted something big, yet somewhat simplistic. Of all my ideas, I finally decided to 
recreate a model of the house I grew up in. The use of different shapes, lines, and textures could be used to recreate such a structure. My application of knowledge has grown 
exponentially over the weeks. I have spent countless hours reading materials, watching videos, and seeking help from peers to complete my project. By following along with video 
and reading material, I was able to set up an environment to build my model. What started out as a simple triangle is now over 4500 lines of code that show a relatively accurate 
depiction of my childhood home. 

The model that is shown consists of several simplistic objects that combine to make complex objects. When I first started working on this project, I used one array of 
vertices and tried to recreate my model by making one very complex object. This array also included the texture coordinates. After a few weeks I ran into the problem of needing 
more textures, more shapes, and a need for separation. I made the change in my code to allow the use of multiple arrays for vertices, and later further separated these arrays into 
coordinates and texture coordinates. 
Within my code, each shape is separated into a different object structure that can be drawn and manipulated in a variety of ways. I set up a structure to include a vertex buffer, 
texture coordinates, a normal buffer (for lighting and shading), and a vertex array object. I also included a few methods to help bring everything together. Methods include 
uploading vertices, drawing an object, generation of normals for lighting, and a clean up method to deallocate resources once they have outlived their purpose. To create an object 
in my world, an object was declared. Next, an array of vec3 vertices was written to provide coordinates. To get the lighting, shading, and texture to work properly, an array of 
vec2 texture coordinates was written to be associated with each array of vertices. Each of the textures used in the project were then loaded into the application. Within the main 
loop, the draw function of the overhead structure could be called to place the object into the scene. The draw function took in the arrays of vertices, texture coordinates, a 
world location, a shader, and a texture. Using this information, I was able to place objects into a world and generate a large and complex looking model.
The mouse and keyboard are used for input to move around the world. The basic WASD controls are used to move their perspective direction. The mouse can change the viewing angle of 
the camera, and the scroll wheel can be used to speed up or slow down the speed of the camera. In addition to those controls, the left shift key and space bar can be used to move 
up or down the Y-axis. The model that has been created is hard to fit in its entirety onto the screen at one time. To resolve this issue, an orthographic view of the model can be 
view by pressing the ???p??? key.

Overall, this class was an absolute blast to participate in. I have enjoyed learning new and exciting concepts each week, and then given the ability to apply these 
concepts to recreate a piece of my childhood. 
