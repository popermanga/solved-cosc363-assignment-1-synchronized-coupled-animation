Download Link: https://assignmentchef.com/product/solved-cosc363-assignment-1-synchronized-coupled-animation
<br>
<h2>1.  Introduction</h2>

Synchronized coupled animations are formed by combining two or more different animation sequences in such a way that the objects move in a specific pattern producing an interesting and visually appealing motion. Examples of such animations can be found in the following YouTube videos:

<a href="https://www.youtube.com/watch?v=2zmkQr2j7z8">https://www.youtube.com/watch?v=2zmkQr2j7z8</a>  <a href="https://www.youtube.com/watch?v=V-cCrX7vw8Q">https://www.youtube.com/watch?v=V</a><a href="https://www.youtube.com/watch?v=V-cCrX7vw8Q">–</a><a href="https://www.youtube.com/watch?v=V-cCrX7vw8Q">cCrX7vw8Q</a>

Several other sophisticated and more complex forms of synchronized animations can be found here: <a href="https://youtu.be/SZtTupRKSKY">https://youtu.be/SZtTupRKSKY</a>

Examples of synchornized animations will also be shown during lectures when the assignment tasks are discussed.

<h2>2.  Task Description</h2>

In this assignment, you will develop a graphics application using OpenGL-2 to display a scene, which among other things contains a synchronized animation model as the centerpiece. You are not required to create highly complex models or animation sequences for this assignment.  The assignment task can be broadly divided into four sections:

Minimum requirements (10 marks):  The scene should contain a set of minimum features as outlined in Section 3.

Extra features (5 marks):  You can implement a set of extra features and gain up to a maximum of 5 marks. A few examples of such features are given in Section 4.

Rendering quality (3 marks):  Up to 3 marks are allocated for the overall rendering quality of the scene, including animations (see Section 5).

Report (2 marks):  You should also prepare a brief report containing a few screenshots and a description of the scene  (see Section 6).

3.  Minimum Requirements

3.1 The scene should contain a few models that continuously move according to a synchronized animation sequence.  The models could be constructed using a set of polygonal primitives, GLUT objects or surface design methods (see Section 7).

3.2  At least one of the objects must be modelled as a sweep surface.

3.3    The viewer must be able to navigate the camera through the scene using arrow keys. The up and down arrow keys must move the camera forward and backward respectively, the left arrow key should change the direction of motion towards left by a certain angle, and the right arrow key should change the direction of motion towards right. You may define additional functions for processing keyboard, special key, and mouse inputs as needed.  Please do not use passive mouse motion function or the idle function for user interaction.

3.4    At least three different textures must be used in the scene. It is not necessary to texture map all surfaces.  Please do not use very large images (&gt;10MB) as textures.  The textures used in a skymap will be counted as one texture.

<h2>4.  Extra Features</h2>

A list of possible features, and the approximate marks they would each gain if implemented correctly (subject to a maximum of 5 marks) are given below.

<ul>

 <li>Planar shadows cast by at least one object (1 mark)</li>

 <li>A spot light on a moving/rotating object (1 mark). The movement of the spotlight should be clearly visible.</li>

 <li>Physics based (e.g. gravity) animation. Give relevant equations in your report. (12 marks depending on the complexity of the Physics model)</li>

 <li>A surface shape generated using a mathematical formula (e.g. paraboloids) or a complex design process. Please provide sufficient details in the report. (1-3 marks depending on the complexity of the model)</li>

 <li>Collision detection (1 mark)</li>

 <li>Sky box (1 mark)</li>

 <li>Particle systems (1-2 marks depending on the complexity of the model)</li>

 <li>(This is not a program feature) You will be given an extra mark if you also include a proper CmakeLists.txt  file that builds the executable from the source code,  along with your submitted files.</li>

</ul>

The marks associated with each feature should be taken to be indicative of the time and/or effort required to implement that feature. The list given above should not be taken as the complete set of features that can be implemented.

<h2>5.  Rendering Quality</h2>

In the context of this assignment, rendering quality refers to the visual aesthetic quality of the models and animations displayed by the program. For example, slow and jittery animations, incorrectly rendered sky boxes and shadows, and improper illumination may cause marks to be deducted for poor rendering quality.  <u>6.  Report (Max. marks: 2,  Max. number of pages: 4)</u>

The report should include the following sections:

<ul>

 <li>Your name and student number.</li>

 <li>A brief description of the scene.</li>

 <li>At least two screenshots showing important aspects of the scene or animations.</li>

 <li>A brief description of each extra feature implemented, including relevant equations. Please also include any diagrams, sketches etc. used in the design of the models.</li>

 <li>A full list of control functions (keyboard, mouse, special keys) defined for interacting with the scene.</li>

 <li>Build commands or instructions for compiling and running the program.</li>

 <li>References to sources of textures, algorithms, equations etc., used in your work. You need not include references to material provided in the course (lab/lecture material).</li>

</ul>

You may include more than 4 pages in the report, only if absolutely necessary. Please submit your report as a single <strong>PDF</strong> file.

<h2>7.  Models and Animations</h2>




The object models in the scene may be constructed using any of the following methods:

<ul>

 <li>By transforming and combining a set of (at least three) GLUT/GLU objects such as spheres, cubes, cylinders etc. to form a composite model.</li>

 <li>By using a set of polygonal surfaces comprising of quads and triangles.</li>

 <li>By using surface generation methods such as sweep surfaces, surfaces of revolution etc.</li>

</ul>

You are not required to design or use highly complex mesh models for this assignment. Designing objects using modeling packages such as Max, Blender, Lightwave, etc., will not give you any extra points.  Downloading pre-built mesh models from the Internet and using them in the program will also not give you any marks.

You may use parts of lab code and resources (models, images, image loading functions).  Models and animations developed in the lab will give you marks only if significant changes or enhancements have been made to them.




<ol start="8">

 <li><u> Program Development:</u></li>

</ol>

<ul>

 <li>Please do not use source codes of programs from online repositories, tutorials, and books.</li>

 <li>Develop your program in C/C++ language using only OpenGL 2 API. Please do not use OpenGL 4 code (vertex/fragment shaders etc.), or extensions (e.g. ARB, EXT etc.) that are not part of the standard OpenGL API.</li>

 <li><strong>Please make sure that your program can be compiled and run on CSSE lab machines. </strong></li>

 <li>Your submission will not be marked for code readability or optimization. However, you are encouraged to prepare well documented and readable code.</li>

 <li>You will gain marks only for objects/features that are correctly and clearly displayed. A particular feature may be implemented correctly in code, but if its effect is not clearly seen on the screen, you will not receive marks for that feature.</li>

</ul>