# Trajectory-Planning
Implementing a basic trajectory planner using polynomial functions \
If the jupyter notebook doesn't load, use the notebook viewer: **[nbviewer](https://nbviewer.jupyter.org/github/BonJovi1/Trajectory-Planning/blob/master/code.ipynb)** 

The Question:

A service robot wakes up in a room at coordinates (3, 0) at to = 0. Within the room, the robot has to visit the point (1, 2.5) in order to collect a cookie for his friend. The robot then has to move to the other end of the room at (9, 5) to give his friend the cookie, at tf = 5. In addition, the robot must not crash into his friend, so his end speed must be equal to 0. Assume the robot is holonomic i.e. he can move along the x and y directions independently. Sample t from to to tf in increments of 0.1.

- Compute the trajectory for this desired motion profile using a polynomial function of degree four. Recall that this amounts to formulating a linear system Ax = b based on the given constraints, for both x and y, and simply solving for the coefficients of the polynomial function. Plot the obtained trajectory indicating the start, end, and waypoint clearly. Also plot the corresponding velocity and acceleration profiles.

- Next, compute the trajectory as a fifth degree Bernstein polynomial, i.e. as a linear combination of the Bernstein basis polynomials. Plot the obtained trajectory indicating the start, end and waypoint clearly. Also plot the corresponding velocity and acceleration profiles.

- To complicate things, an evil robot of radius 2 units appears at (5, 4) to steal his cookie. The robot, whose radius is 1 unit, must avoid this evil robot in order to successfully deliver the cookie. Describe how you would compute a trajectory accordingly. 
