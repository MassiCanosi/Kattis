# Description 
Oh, no. Atli has just painted himself into a corner. He has been playing the video game Planetaris and decided to start a war against his friend Finni. 
The downside is Finni had a considerably larger spaceship fleet than Atli expected. Atli now needs your help to turn the tide, by determining how many fights Atli can win.
Each space fight takes place in a solar system. This early in Planetaris all the spaceships are identical. 
Since Atli spent most of his Intergalactic Super Kurrency (ISK) on an eavesdropping station he knows to which solar systems Finni’s fleets are going and how many ships are in each fleet. 
If Atli sends fewer ships than Finni to a particular solar system he will lose and Finni gains control of the solar system. 
If they send the same number of ships there will be no ships left over to claim the system, so there is no winner. 
However if Atli sends more ships than Finni to a system he wins the battle and gains control of that solar system.

# Input
The first line of the input contains two integers 1 <= n <= 10^5 and 0 <= a <= 10^9, where n is the number of solar systems and ais the total number of ships Atli has at his disposal. 
The next line contains n integers 0 <= ei <= 10^9, where ei indicates Finni is sending ei ships to the ith solar system.

# Output
The only line of the output should contain an integer indicating the largest number of battles Atli can win if he plays optimally.
