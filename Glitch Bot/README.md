# Description
One of our delivery robots is malfunctioning! The job of the robot is simple; it should follow a list of instructions in order to reach a target destination. 
The list of instructions is originally correct to get the robot to the target. However, something is going wrong as we upload the instructions into the robot’s memory. 
During the upload, one random instruction from the list takes on a different value than intended. 
Yes, there is always a single bad instruction in the robot’s memory and it always results in the robot arriving at an incorrect destination as it finishes executing the list of instructions.

The robot can execute the instructions “Left”, “Right”, and “Forward”. The “Left” and “Right” instructions do not result in spatial movement but result in a 90-degree turn in the corresponding direction. 
“Forward” is the only instruction that results in spatial movement, causing the robot to move one unit in the direction it is facing. 
The robot always starts at the origin (0,0) of a grid and faces north along the positive y-axis.

Given the coordinates of the target destination and the list of instructions that the robot has in its memory, you are to identify a correction to the instructions to help the robot reach the proper destination.

# Input
The first line of the input contains the x and y integer coordinates of the target destination. 
The following line contains an integer n representing the number of instructions in the list.
The remaining n lines each contain a single instruction. These instructions may be: “Left”, “Forward”, or “Right”.

# Output
Identify how to correct the robot’s instructions by printing the line number (starting at 1) of an incorrect input instruction, followed by an instruction substitution that would make the robot reach the target destination. If there are multiple ways to fix the instructions, report the fix that occurs for the earliest line number in the sequence of instructions. There is always exactly one unique earliest fix.
