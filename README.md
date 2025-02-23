# VEX-VR-Retry

The robot used python to solve the maze, return home, map the maze and print the map in the concole. 

The robot uses the left-hand-wall rule to explore the maze until it finds the end. The end is identified by the red square which the down eye can see. 

The robot then returns home following the most efficient path. 

The robot then explores every part of the maze untill it is all mapped using coordinates. 

When the entire maze has been mapped the robot returns home.

When the robot has returned home the maze is printed in the console using + for corners, --- for horizontal walls, | for vertical walls, S for the start, E for the end and ● for the exit route. 
