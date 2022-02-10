<<<<<<< HEAD
Hello, my name is Jon Falasca and I am a Master's student at the University of Clemson. This repository will contain files that I create for my course in Autonomy. 


=======
In this workspace I have included 3 python scripts. To run these scripts you can follow the same general process. Begin by opening a terminal and running roscore. Then, open a new terminal to open turtlesim by inputing the command "rosrun turtlesim turtlesim_node". Lasty, open one more terminal where you can run the script by inputing the command "rosrun assignment2_ws name.py" where name is the name of the script you would like to run. If this is unclear/hard to follow there is a folder title videos in which this process is shown for each script. 

The first script is called circle.py. This script moves the turtle in turtlesim in a circle of a set radius. The radius of the circle the turtle travels along is determined by the linear speed and the angular speed that are set within the code. Currently, the linear speed is set to 3 and the angular speed is set to 2.5. With these velocities, the turtle travels in circle that has a radius of 1.2 units. If you want to change the radius of this circle simply use the relationship r=v/w. In this equation v represents the linear velocity and w represents the angular velocity.

This is a screenshot of the trajectory of the turtle:


The second script is called square_openloop.py. In this script the turtle in turtlesim travels in a square with a linear velocity and angular velocity of 0.2. Additionally, the turtle is set to move in a 2x2 square. At the bottom of the script the function handle_move_square is what commands the turtle to move in the square. The first input of this function tells the turtle the size of the square, and the second input tells the turtle how many times it should move in a square. 

Here is a screenshot of the trajectory when running square_openloop:


Lasty, the third script is called square_closedloop. This script also commands the turtle to move in the shape of a square. However, the coordinates of the four corners of the square were predetermined. These coordinates are (5,5) ->(8,5) -> (8,8) -> (5,8) -> (5,5). In this script the linear spped and the angular speed are calculated using these coordinates and are controlled by a P-controller. The P-controller proportionally scales the linear and angular speed by multiplying these values by a constant number. The linear speed and the angular speed have separate controllers so they can be tuned individually. Tuning is done by adjusting the constant value that is mulitplying the speed you want to adjsut. 

Here is a screenshot of the trajectory when running square_closedloop:
>>>>>>> Files for Assignment 2
