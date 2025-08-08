# Tower_of_Hanoi

# Overview

The Tower of Hanoi is a classic problem in computer science and mathematics. The objective is to move a stack of disks from one peg (source) to another peg (target), using a third peg (auxiliary) as needed. The following rules must be followed:

Only one disk can be moved at a time.
Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty peg.
No larger disk may be placed on top of a smaller disk.

# Key Components

NUMBER_OF_DISKS: This variable defines how many disks will be used in the simulation.
A, B, C: These lists represent the three pegs. A is the source peg, B is the auxiliary peg, and C is the target peg.
move(n, source, auxiliary, target): This recursive function performs the main logic of moving the disks:
Base case: If n is less than or equal to 0, the function returns without doing anything.
The function first moves n - 1 disks from the source peg to the auxiliary peg.
It then moves the nth disk from the source peg to the target peg.
Finally, it moves the n - 1 disks from the auxiliary peg to the target peg.
