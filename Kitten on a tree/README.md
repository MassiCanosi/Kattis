# Input 

The input is a description of a single tree. The first line contains an integer K, denoting the branch on which the kitten got stuck. 
The next lines each contain two or more integers a,b1,b2. Each such line denotes a branching: the kitten can reach a from b1,b2,... on its way down. 
Thus, a will be closer to the root than any of the bi. 
The description ends with a line containing -1. Each branch bi will appear on exactly one line. All branch numbers are in the range 1...100, though not necessarily contiguous. 
You are guaranteed that there is a path from every listed branch to the root. The kitten will sit on a branch that has a number that is different than the root.

# Output
Output the path to the ground, starting with the branch on which the kitten sits.
