# CS 330: Computational Graphics and Visualization

This repository contains my work for CS 330: Computational Graphics and Visualization at Southern New Hampshire University. Throughout this course, I used C++ and OpenGL to learn how to create, texture, light, render, and navigate three-dimensional scenes.

## Final Project

For my final project, I recreated a 3D desktop workspace based on a 2D reference image. My completed scene includes:

- Coffee mug with visible coffee
- Spiral notebook
- Pencil
- Keyboard
- Computer mouse
- Desktop surface

The scene was created using low-polygon primitive shapes including planes, cylinders, tapered cylinders, boxes, cones, toruses, and spheres. I combined multiple primitive shapes to create more complex and recognizable objects.

## Design and Development

One of the biggest parts of this project was learning how small changes in scale, rotation, position, color, and lighting can completely change the appearance of a 3D scene.

Several objects required multiple revisions. For example, I adjusted the size and position of the pencil body so that the tip and eraser appeared connected instead of looking like separate pieces. I also repositioned the notebook spirals so they aligned correctly with the edge of the paper.

Color was another important design decision. Originally, several objects were similar shades of white, which caused the keyboard, notebook, mouse, and desktop to blend together. I changed the keyboard to a cooler gray-blue and used slightly different tones for the other objects to create better separation.

Lighting also required a lot of experimentation. I used multiple light sources and adjusted the ambient, diffuse, and specular components of the Phong lighting model. This helped create more depth while avoiding areas that were either too dark or overly bright.

## Camera Controls

The application allows the user to explore the scene using keyboard and mouse controls:

- **W / A / S / D** - Move forward, left, backward, and right
- **Q / E** - Move vertically
- **Mouse movement** - Change camera orientation using pitch and yaw
- **Mouse scroll** - Adjust movement speed
- **Projection control** - Switch between perspective and orthographic views

These controls allow the scene to be viewed from different positions and angles rather than from one fixed viewpoint.

## What I Learned

This project helped me better understand how computational graphics are built from several systems working together. I gained experience with:

- Creating 3D objects from primitive meshes
- Working with X, Y, and Z coordinates
- Scaling, rotating, and translating objects
- Applying textures to 3D models
- Working with materials and shaders
- Using ambient, diffuse, and specular lighting
- Creating multiple light sources
- Implementing interactive camera movement
- Switching between perspective and orthographic projections
- Debugging C++ and OpenGL applications
- Organizing graphics code into reusable functions

One of my biggest takeaways was how much trial and error is involved in creating a convincing 3D scene. Even small changes to an object's position or lighting values could make a noticeable difference in the final result.

## How Do I Approach Designing Software?

I usually begin by breaking a larger problem into smaller pieces. For this project, instead of thinking about the entire desktop scene at once, I looked at each real-world object and considered which basic 3D shapes could be combined to recreate it.

My design process also became more iterative throughout the course. I would build an object, run the program, evaluate the result, and then adjust its transformations, materials, textures, or lighting. This approach helped me gradually improve the scene without trying to solve every problem at once.

The project also reinforced the importance of modular design. Functions for transformations, materials, textures, lighting, and scene preparation made it easier to change individual parts of the program without affecting everything else.

## How Do I Approach Developing Programs?

Working on this project strengthened my approach to development and debugging. I learned that visual programming requires frequent testing because code can compile successfully while the visual result is still incorrect.

When something did not look right, I tried to isolate one variable at a time. For example, I adjusted an object's scale or position before changing several other properties at once. This made it easier to understand which changes were actually improving the scene.

These strategies can be applied to future projects outside of computer graphics as well. Breaking problems into smaller components, testing frequently, using reusable functions, and making incremental changes are useful practices for software development in general.

## How Can Computer Science Help Me Reach My Goals?

Computational graphics gave me another perspective on how computer science can be used to represent information visually and interactively. Although my future work may not focus specifically on 3D graphics, the skills I practiced in this course connect to many other areas of computer science.

Working with coordinate systems, transformations, visualization, C++, debugging, and modular program design can support future work in software development, simulation, data visualization, and other applications where information needs to be presented visually.

This course also strengthened my ability to take an idea, break it into manageable pieces, develop a working solution, and continue refining it based on the results.
