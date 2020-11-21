## Figure 22
This figure covers the case of a Nonlinear model of quadrotor motion and a target moving in lawnmower pattern with pass length L = 20 m and radius of the circular ends <img src="https://render.githubusercontent.com/render/math?math=r_L = 2"> m and with constant speed <img src="https://render.githubusercontent.com/render/math?math=\|v_T\| = 0.5"> m/s. Wind with velocity <img src="https://render.githubusercontent.com/render/math?math=v_a = [2,2,0]^T">m/s and sensor noise are considered here. Control is applied along the line-of-sights of the quadrotors and target and in the corresponding lateral directions. The quadrotors are placed on either side of the target, such that the three are collinear. The gains for the simulation are:<br>

<img src="https://render.githubusercontent.com/render/math?math=K_{P} = 1">
<img src="https://render.githubusercontent.com/render/math?math=K_{Pr} = 1.5">
<img src="https://render.githubusercontent.com/render/math?math=K_{D} = 2">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr} = 2">
<img src="https://render.githubusercontent.com/render/math?math=K_{P\alpha} = 0">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr\alpha} = 2">
<img src="https://render.githubusercontent.com/render/math?math=K_{D\alpha} = 0.4">

The position of the quadrotors (Q1 and Q2) are plotted in two-dimensional space over time, showing the trajectory, instantaneous velocity and acceleration input directions. The target (T) is displayed in green. The load is displayed as a black bar between the quadrotors, with green ends signifying an extension and magenta, a compression in the connecting ends. The circles about the target on which the quadrotors have to settle are also displayed for clarity. The reference distances and angales are:<br>

<img src="https://render.githubusercontent.com/render/math?math=r^d_{1,2} = 4">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,1} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,2} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=v_x^a"> is the x-velocity of quadrotor relative to the air in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_y^a"> is the y-velocity of quadrotor relative to the air in inertial frame<br>

<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
