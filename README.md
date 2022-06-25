# Raygun Coding Challenge: Overview

Create a function solution(dimensions, your_position, trainer_position, distance) that takes three
arrays as input (dimensions, your_position, trainer_position) and one integer as arguments and returns a certain
integer (described below).

Explanation: Given a grid, or room, of size dimensions, a starting position (your_position) and a target position (trainer_position), 
determine how many directions (represented as a vector) a laser can be fired from the starting position to hit the target position
where the laser can travel a certain distance (distance) and reflect from edges of the grid (or walls of the room) while avoiding hitting the starting position.

For example, given a room of size [2,3], a starting position of [1,1], target position of [1,2] and max laser distance of 3,
there are 3 directions the laser can be aimed to hit the target position represented as vectors: [0,1], [-2,1], [2,1]

solution([2,3], [1,1], [1,2], 3) should return integer 3.

## Code and Resources Used
**Python:** Python 3.8.10 <br/>
**Packages:** none <br/>
