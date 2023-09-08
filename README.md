# RayTracing-Projects

![800px-BallsRender-1](https://user-images.githubusercontent.com/3434843/194641709-6a8db346-a841-426d-8c5f-f2c3245436f1.png)

<br>

This GitHub repo is for demonstrating how to set up and maintain your 1st repo on GitHub.  Beginning with creating a GitHub account, installing Git on our local development machines, and using the awesome VSCode-GitHub integration feature, everything that you see here (folder structure, images, Readme, Live Demos hosted on GitHub Pages, etc.) was done on camera in this [YouTube episode](https://youtu.be/IdF_hbKsi3c?list=PL3NuKUKozjGTJRKB4duG2dxpyUu_Pj7jV)

<br>

That episode is part of my YouTube video series called <strong>The <em>Joy</em> Of Ray Tracing </strong> in which we start from scratch and make several types of Ray Tracers: <br>

[The Joy of Ray Tracing Video Series](https://www.youtube.com/playlist?list=PL3NuKUKozjGTJRKB4duG2dxpyUu_Pj7jV)

<br>

The companion GitHub repository for this entire YouTube series is located at: <br>

[The Joy of Ray Tracing companion code repo](https://github.com/erichlof/Joy-of-Ray-Tracing)

<br>

<h2> Live Demos </h2>

* [My Webpage](https://erichlof.github.io/RayTracing-Projects/myWebpage.html) Creates a Canvas element
* [Styled Canvas](https://erichlof.github.io/RayTracing-Projects/styledCanvas.html) Uses CSS to make the Canvas full screen
* [Interactive Page](https://erichlof.github.io/RayTracing-Projects/interactivePage.html) Uses addEventListeners to make page interactive
* [Simple Button Input](https://erichlof.github.io/RayTracing-Projects/simpleButton.html) Adds a simple button to randomize width and height of rectangles
* [Randomized Colors](https://erichlof.github.io/RayTracing-Projects/randomColors.html) Creates a unique random color (rgb) for each rectangle
* [Pixel Loop](https://erichlof.github.io/RayTracing-Projects/pixelLoop.html) Loops over each and every pixel on the screen and sets that pixel to a unique rgb color
* [Ray Direction Visualizer](https://erichlof.github.io/RayTracing-Projects/rayDirections.html) Using our new Vector3 library, assigns a unique ray direction vector to each pixel. The rgb colors represent the ray direction vector components(red=x, green=y, blue=z) of each pixel
* [Ray-Plane Intersection](https://erichlof.github.io/RayTracing-Projects/intersectPlane.html) Tests if each pixel's ray intersects with a plane. Our new dot product function aids in this ray-plane intersection, and our new 'mix' function allows smooth blending between 2 color vectors (the ground blends with horizon in the distance, and horizon blends with blue sky as height increases) 
* [Ray-Sphere Intersection](https://erichlof.github.io/RayTracing-Projects/intersectSphere.html) Tests if each pixel's ray intersects with a sphere. Our new solveQuadratic function handles the implicit equation of a sphere (x^2 + y^2 + z^2 - r^2 = 0), which is quadratic (degree 2) and must have both roots found (t0 and t1), in order to render the sphere
