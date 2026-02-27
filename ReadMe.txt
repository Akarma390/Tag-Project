Used the scripts
	Evade 
	Obstacle Avoider
	Flee
	Wander

Evade
-Changed the target variables to public and set them to the "target" balls

Obstacle Avoider
	Bounding radius: 20
	Game object: Maze

Flee
    Default

Wander
	Wander radius: 8
	Wander distance: 10
	Wander Jitter: 40
	Starting velocity: 3



I added the changes to evade as it wasn't picking a target and wasn't giving any feedback. It will now try to distance and predict other balls movement.

Added Obstacle avoider to prevent the ball from getting stuck on the maze walls and slowing down this gives it a better escape vector. 

Added flee so it'd distance more with the evade maneuver.

Increased the wander variables as the ball would often go for a corner or go very slowly to the wander point. The increase in distance and jitter made the movement more unpredictable and helped create move distance from the it ball. 



