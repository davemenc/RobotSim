# RobotSim
This is a simulator of robots. It is primarily to test things like navigation. It will start simple (i.e. inaccurate) but get more sophisticated over time. 

## Structure
I haven't put in a word of code yet but I know how it will work and I know already that it will be confusing. It comes in two parts: the robotbrain and the house. In the house are all the robot sensors and the robot motion and everything else having to do with the pysical robot. This might seem wrong but it's because the "house" is the physical universe including everything about the robot that's physical.

The robotbrain is ONLY about how the robot brain deals with information that comes from the sensors and how it tries to move in response. The robot doesn't REALLY know where it is, it only knows what it's sensors tell it and it must deduce from the sensors where it is. Likewise, it can only tell the treads to move, it doesn't really know how far they go. 

So what the Robot_Brain thinks it knows and what the House thinks is true may be really different. And this is the point: we want to get our robot so it can correctly figure out what to do. 

## The House
There are 3 parts to the house. The physical structure of the house, the position of the robot and the simulation of the robot. The first two are just data; all the work happens in the third. The robot says "what does this sensor say" and the house sends back and answer. THe robot says "move forward 3 steps" and the house has to figure out how far that is and change the location of the robot (as well as checking to see if it's fallen down the toilet).

## Representation
THe first question is how should the house be represented. 

One way is a map. The house is laid out in a big cartesion coordinate map. 

# Other Stuff
Ok, I'm supposed to talk about how to run this and how to contribute but there's NOTHING HERE yet. Only aspirations so far...
