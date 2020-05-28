# Final Project - Spring Car

<b>Task:</b> Seeing how important it is to understand the meaning of Rapid Prototyping, the
Final Project consists of creating a prototype of a specific mechanism.

The final project that I chose for the 3DMP Course is a Spring Car, which I need to model starting from the following sources: <br>
	a.	[Youtube video](https://www.youtube.com/watch?v=pX1OS6-TNw8&feature=youtu.be) <br>
	b.	[Thingiverse design](https://www.thingiverse.com/thing:3328754) <br>
	c.	[MyMiniFactory design](https://www.myminifactory.com/object/3d-print-dual-mode-spring-motor-rolling-chassis-26862) <br> 
	My direct reference was the MyMiniFactory design.
	
	I chose this design because I found it quite easy and fun to do. I also remembered playing with this kind of spring cars when I was a child and it was interesting for me to create a prototype of something that I am actually familiar with and to understand how it actually works.
	This particular model of a spring car works based on friction, which triggers the spring. The spring changes its form a little bit and, when the car is places on the ground, without being touched, it will want to go beck to its initial state, therefore making the car move forwards. This happens when the car is rubbed with the ground or when the knob is rotated. Therefore, the mechanism can be "powered" from two sources.
	
	The components of this car are: <br>
	- 1 [pawl](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Pawl.stl) <br>
	- 1 [spring](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Spring.stl) <br>
	- 4 wheels: 2 [front wheels](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Front%20Wheel.stl) and 2 [rear wheels](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Rear%20Wheel.stl) <br>
	- 4 gears: [large gear idler](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Large%20Gear%20Idler.stl), [small gear idler](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Small%20Gear%20Idler.stl), [rear axle gear](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Rear%20Axle%20Gear.stl), [gear pawl](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Gear%20Pawl.stl) <br>
	- 1 chassis made of 2 components: [left chassis](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Left%20Chassis.stl) and [right chassis](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Right%20Chassis.stl) <br>
	- 4 axles: [front axle](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Front%20Axle.stl), [rear axle](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Rear%20Axle.stl), [axle with knob](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Knob%20and%20Axle.stl), [axle gear idler - small](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/stl%20files/Axle%20Gear%20Idler%20-%20Small.stl). <br><br><br>
	
	This mechanism uses rotational joints: of course, each gear needs to rotate with their axles, as well as the rear wheels, which are moved because of the rotation of the rear axle. I did not use any joints for the front wheels, because they are not simply powered by the rotation of the components of the mechanisms (for example, if it were to rotate any of the gears, axles, the knob or the rear wheels, all these components would move together, but the front wheels wouldn't; they only rotate when in contact with the ground). The pawl and the knob also have a rotational motion. For the Fusion prototype, I didn't need to add any motion to the spring. <br><br>
	
	As stated earlier, the car's mechanism is powered by the rotation of the knob or oh the rear wheels (though if we would rotate any gear, the whole assembly would also move). Let's assume the rotation start from the knob. The know is rotated by hand. On its axle there is the pawl, which will rotate with the knob axle and determine the rotation of the gear outside of it. This gear starts to rotate, powering the other gears that are each a bit more in the rear part of the car. When the rear axle gear starts rotating, it rotates with the axle that it is fixated on, and the rotation of this axes makes the rear wheels to (surprise!) rotate! Besides this mechanism, we have the spring, that has two fixating parts: one fixated on the knob axle and one on an extrusion of the left chassis. Its position doesn't change, it doesn't really rotate as the other components do, but, as all springs do, it will change its shape a little bit, as it gets more tensioned while the center part)fixated on the knob axle) rotates. When there is no more rotation. the spring releases its tension, making the car move on its own.  <br>
	If it were to power the mechanism by rotating it's rear wheels (let's say, rubbing it against a surface), the story would be simililar with the one already presented, only backwards. <br><br> 
	
In this directory, you can currently find: <br>
a. The [canvases](https://github.com/Ana-Mares/3DMP/tree/master/Final%20Project%20-%20Spring%20Car/Canvases) I made for the project, with png files. <br>
b. The [f3d files](https://github.com/Ana-Mares/3DMP/tree/master/Final%20Project%20-%20Spring%20Car/f3d%20files) showing my progression over time. <br>
c. The [images and videos](https://github.com/Ana-Mares/3DMP/tree/master/Final%20Project%20-%20Spring%20Car/Images%20%26%20Videos) of the complete project, with png and mp4 files.<br>
d. The [gcode file](https://github.com/Ana-Mares/3DMP/tree/master/Final%20Project%20-%20Spring%20Car/gcode%20files) made in PrusaSlicer with al the components.<br>
e. The [stl files](https://github.com/Ana-Mares/3DMP/tree/master/Final%20Project%20-%20Spring%20Car/stl%20files) for each individual component and for the assembly as a whole.  <br><br>

## Checkpoint 1
<b>Tasks:</b>
1. Create a new folder, in your 3DMP GitHub repository, with the name of your mechanism. Inside of it, make sure you have the canvases and the .f3d file of your project, and a short description of the mechanism (the readme).
2. Divide your project into components. Before designing the mechanism, create an empty component for each part of your project. This will help you to organize your project and understand how to make it step by step. (Course 8.5 video shows you how to do that)
3. Do the tasks established with your teaching assistant at the Office Hours. Also, redo the canvases if your teaching assistant asked you to.

Luckily enough, my canvases were good to go so I didn't have to redo them. 
The first thing I did was to make an empty component for each of the pieces in my design. For the first three components made (the left and right chassis and the large gear idler, I made additional canvases to help me in Fusion. After that, I figured out that it would be easier to just sketch in Fusion, without any more canvases. I measured my dimensions based on the .stl files from MyMiniFactory, in an attempt to be as close to reality as possible. I modelled around half of the components for my project, which can be seen from the [f3d file](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/f3d%20files/Spring%20Car%20progress%2010.05.f3d) uploaded on the 10th of May, before the office hours. 

## Checkpoint 2
<b>Tasks:</b>
1. Do the tasks established with your teaching assistant at the Office Hours.
2. Update the .f3d file.
3. Update the readme, describing the current progress.
4. Any extra work will be rewarded (we encourage you to design as much as you can regarding that in the last week you will have other exams and it will be hard to work on this project as well). <br>

For this week, I continued modelling the components and making the necessary adjustments and fixes regarding positioning or dimensions (which was quite troublesome), making sure everything is perfectly in place and ready to be 3D printed. I added all the remaining components and also appearance, as you can see from this [f3d file](https://github.com/Ana-Mares/3DMP/blob/master/Final%20Project%20-%20Spring%20Car/f3d%20files/Spring%20Car%20progress%2018.05.f3d). <br>
I also took time to update the README file, so that my progression over time is more clear.

## Checkpoint 3
<b>Tasks:</b>
1. Start the design from the canvases or the sketches created by yourself for Homework no.6. (1 point)
2. Respect FUSION RULE NUMBER ONE. (1.5 points)
3. Save multiple versions and suggestively name them. (1 point)
4. Properly use and name bodies, components, joints, construction planes, etc. (1.5 points)
5. Render the object applying appearance and scene (color scene or environment). (0.5 points)
6. Save the renderings as photos and as a VIDEO / GIF Render. Upload them to GitHub as well. (0.5 points)
7. Add joints, motion links and joint limits. (1.5 points)
8. Create motion studies. (0.5 points)
9. The mechanism needs to work properly! (1.5 points)
10. Add a detailed readme in the project folder. The readme needs to
contain: (0.5 points)
	a. the mechanism's name
	b. a short description and why you chose this mechanism
	c. how it works and which are the main components/joints that are participating in the motion
	d. what joint / component do you need to power, or what motion study do you need to play to see the motion
	e. what file types do you have in your repo (.f3d, .stl, .gcode,.stp, .igs, etc)
	f. which software did you use to design and render the mechanism
	g. resources (very important!!!)
	h. mention of the mechanism's author/creator (very important!!!)
	
There is a link where you can learn how to make a readme look like a readme: https://www.makeareadme.com/
Good to do: (MENTION AT THE PRESENTATION ANY EXTRA WORK)
	● Create the model having in mind that it needs to be 3D printed.
(extra points)
	● Be creative! (extra points)
