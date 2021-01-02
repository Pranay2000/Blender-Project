# Character Animation in Blender    <img src="http://thilakanathanstudios.com/wp-content/uploads/2015/09/basicworkflow_thumbnail.jpg" align="right" width="300" height="250" />
## Title: Naruto Shippuden Fight Scene

Designed a model of a fight scene between two characters on Blender.
- For the characters, reference images are used and hence a wireframe has been created whereas for the weapons lighting, different types of mesh are used, provided animation, etc.
-	Different kinds of Blender tools are used for the creation of the characters like extrude, resize, adding modifiers, providing subdivisions, and many more.

-----------------------
## STEPS For Creation of Chidori: 
- First, take a ico-sphere and give it some subdivision surface to make it smooth. Add modifier displace and provide the type as clouds.
- Create an empty to make it move on the surface and provide the necessary rotations.(The empty object will help to animate the structure of it).
- Add a cylinder and increase the number of cuts of it and again add the same modifier that is displace and the type as clouds. Provide the necessary scaling, size and geometry to make it look more like a lightning beam emitting from a particular source.
- Create multiple copies with different strength and sizes. We can also join two different cylinder to look like a beams of lightning and scale it accordingly.
- To simulate energy from it, go onto the graph editor and add noise modifier to each of the cylinders(or the hence created lightning beams) on the X Euler Rotation.
- Provide colour to the ico-sphere and adjust the properties like RGB properties and curves, noise texture, blur effect in the node editor window. 
- Render the animation.
![Alt text](https://github.com/Pranay2000/Blender-Project/blob/master/Reports/SS/Chidori.PNG)

----------------------------
## STEPS For Creation of Rasengan:
- With the cube as start point delete all the vertices except one i.e. a singular vertex and create a new particle system.
- Add an low poly ico-sphere in another layer and make the vertex dupli the ico- sphere object and make it emit from verts.
- Add a new blue coloured material to the ico-sphere. 
- To animate it, add rotations by going to the graph editor and adding a generator modifier which provides a constant line that rotates.
- Create duplicates of it by pressing ctrl+d and pressing r to rotate it. Make duplicates till it forms a complete sphere or has a ball like structure.
- Play the animation.
![Alt text](https://github.com/Pranay2000/Blender-Project/blob/master/Reports/SS/Rasengan.PNG)

-----------------------------
## STEPS For Creation of Characters:
- Merge the vertices of the cube at the centre and add the modifiers mirror, skin and subdivision surface respectively in the order mirror, skin and subdivision surface.
- Add reference images for the front and side view of the characters. Open the wireframe and do the first extrusion around the lower part of the body. Make the centre vertex as root point.
- Keep on extruding and scaling from the both the front and the side view to give a particular structure to the character.
- After the lower body is fully created, Extrude the upper part and resize, scale for the hands, skull and the neck.
![Alt text](https://github.com/Pranay2000/Blender-Project/blob/master/Reports/SS/Character%20Modeling.PNG)

-----------------------------
After the creation of characters and the weapons add a particular background image to the scene. The Final model is designed by importing every .blend file in one single file and the entire scene is rendered.
![Alt text](https://github.com/Pranay2000/Blender-Project/blob/master/Reports/SS/Final%20Model.PNG)

-----------------------------
## Future Improvements
- Sculting and texturing can be added to the modelled characters.
- Providing movement to the characters and final Rendering for more realism.
