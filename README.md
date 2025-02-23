# Assignment-4-Advanced-Techniques
Assignment #4 – Advanced Techniques


**Download Link:https://programming.engineering/product/assignment-4-advanced-techniques/**

Description
5/5 – (2 votes)
In this assignment, you will implement a 3D scene that incorporates advanced effects. Your program must retain the following features from A1-A3: at least three objects, camera control, skybox, a positional or spot light that can be moved around, and at least one 2D texture that is directly related to an object’s shape. You may keep or change the implementation of any of the features from how you did them before, as long as each capability is present. A matrix stack can be used but is not required.

Design your graphical elements so that they are logical and make visual sense. Part of your grade will be based on your successful application of the chosen techniques to build a coherent scene.

Design your graphical elements so that they don’t just copy the book’s examples verbatim. Part of your grade will be on whether you were able to achieve an original use of the chosen techniques.

In addition, your program is to include the following new features:

Shadow-Mapping

At least THREE objects must participate in shadow-mapping, either casting shadows, or having shadows cast on them. You should attempt to reduce shadow-mapping artifacts, but some amount of artifacts is acceptable.

Your SkyBox must not be one of the ones from the book

(some of you have already satisfied this requirement)

plus, FOUR of the following eight choices:

o Normal/Bump Mapping (procedural, or with a normal map image – for a use other than simulating water)

o Environment Mapping (such as for generating a mirror or chrome object, for a use other than simulating water)

o Fog and Blending/Transparency (to get credit for this one, need to do both – and for a use other than simulating water)

o Geometry shader for primitive modification (or deletion, or addition) o Tessellation shader in conjunction with a height map

or – Cubic Bezier surface via Tessellation (with GL_FILL and color or texture) or – Some other non-trivial use of Tessellation

o Stereoscopy with red/cyan glasses, or splitscreen (e.g. Google Cardboard) o 3D Texture or Perlin Noise use (for a use other than simulating water)

o Simulated water with reflection/refraction and fresnel effect

Additional Notes

The skybox images should be correctly oriented and without obvious seams. Lighting and shadows should not be applied to the skybox. If your scene takes place in a room box, include a skybox outside of the room box, and a way of going outside of the room to see the skybox.

It isn’t required that every feature you include be present simultaneously in your scene. You can instead use buttons or other controls to show the features, or alternate between them. However, that isn’t required either – it usually is more interesting if they are all present at once.

Your program must be contained in a package whose name is “a4”. Otherwise, requirements for compiling and running your program are the same as before.

The same requirements as before with respect to submitted content continues to apply. Any textures, normal maps, models, height maps, etc. must be accounted for in your accompanying document. If you made them yourself, or if they came from the CSc-155 textbook, just state that. Any other such asset must be correctly attributed to the source in your code and your report, as well as a brief (one sentence) description of how its use is allowed under its license. Include either a link directly to the license or a screenshot of the relevant license verbiage.

Grading will be as follows:

2.0 points for shadow-mapping

4.0 points for the four remaining requirements (one point each)

2.0 points for other existing requirements (skybox, models, camera control, lighting, etc.)

1.0 point for the readme document

1.0 point for submitting on time

Inadequately attributing assets (as described above) is deducted separately.

Deliverables

This is an INDIVIDUAL assignment. You may use models and textures from the web, only as described above. You may use code from the textbook, but you may not use code obtained from the web or elsewhere.

Submit to Canvas a single ZIP folder containing all of the following:

All program, data, and .bat files necessary to run your program, in the required hierarchy

a .PDF report file consisting of the following numbered items:

one or more screenshot(s) of your running program, showing as many features as possible

a brief description of your scene

a list of which objects participate in shadow-mapping

a list of the four features you chose to implement, clearly describing how to recognize them.

a list of user controls (such as for moving the camera or light(s))

a list of which requirements you were NOT able to get fully working

a list of any features you implemented that went beyond the assignment requirements

a list of assets you used (i.e., models, textures, normal maps, height maps, etc.), with citation and permission/licensing information about those sources

indicate on which RVR-5029 (remote) machine you tested your program

2
