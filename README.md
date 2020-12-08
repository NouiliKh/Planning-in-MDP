# Planning-in-MDP
Use planning to solve DieN problem

# Description
You are given an N-sided die, along with a corresponding Boolean mask vector, is_bad_side (i.e., a vector of ones and zeros). You can assume that 1<N≤N≤30, and the vector is_bad_side is also of size N and 1 indexed (since there is no 0 side on the die). The game of DieN is played as follows:

You start with 0 dollars.

At any time you have the option to roll the die or to quit the game.

### ROLL:

If you roll a number not in is_bad_side, you receive that many dollars (e.g., if you roll the number 2 and 2 is not a bad side -- meaning the second element of the vector is_bad_side is 0, then you receive 2 dollars). 

If you roll a number in is_bad_side, then you lose all the money obtained in previous rolls and the game ends.

### QUIT:

You keep all the money gained from previous rolls and the game ends.
