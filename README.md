# Pixelate
Pixelate is an event in TECHNEX(Technical fest of IIT BHU(Varanasi)). The event is about making a Robot which propagate through an arena using image processing and path planning to take the robot to its destination in real-time traffic.

The problem statement can be found on this.
 
# Code Description
 Created a python program which uses opencv to visualize and process the image and then planned the shortest path using Dijkstra Algorithm of data structure graph.

# Arena Description : 
The arena contains 12X12 square grids each of which contains following:
Patient location: There are two locations. They are represented by pink 
colored tile. Under each pink color, blue square and blue circle are hidden 
representing the status of the patient (covid/ non-covid).
Hospital: There are two hospitals. They are represented by blue square and 
blue circle shapes on light blue tiles, for each patient (covid/ non-covid)
Heavy traffic: They are represented by red colored tiles. 
Intermediate traffic: They are represented by yellow colored tiles.
Low traffic: They are represented by green colored tiles.
No traffic: They are represented by white colored tiles.
One-way: They are represented by blue triangle shapes on 
red/yellow/green/white tiles.
The bot(ambulance) has to start from the lowest right corner (dark green 
colored tile).
The bot has to end the task by delivering both the patients to their 
respective hospitals i.e., at blue circle or at blue square.
A video feed from the overhead camera will be provided to the team. The 
team's computer should autonomously instruct their bot throughout the 
arena in simulation world.


Some snapshots of the Practice Arena and main arena is shown Below
![map](https://user-images.githubusercontent.com/77740765/178116215-8070f62f-95fc-4b45-9bf4-79376ed4aee5.jpg)

