## Figure 5
This figure covers the case of a nonlinear quadrotor model motion with a static target and sensor noise,<br>
5a. with Control 2 from Table 1 in the paper
5b. with Control 2 from Table 1 in the paper

Control is applied along the line-of-sights of the quadrotors and target. No lateral control is applied. The gains for the simulation are:<br>

<img src="https://render.githubusercontent.com/render/math?math=K_{P} = 0.2">
<img src="https://render.githubusercontent.com/render/math?math=K_{Pr} = 0.1">
<img src="https://render.githubusercontent.com/render/math?math=K_{D} = 0.9">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr} = 0.0">
<img src="https://render.githubusercontent.com/render/math?math=K_{P\alpha} = 0">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr\alpha} = 0">
<img src="https://render.githubusercontent.com/render/math?math=K_{D\alpha} = 0">


The position of the quadrotors (Q1 and Q2) are plotted in two-dimensional space over time, showing the trajectory, instantaneous velocity and acceleration input directions. The target (T) is displayed in green. The load is displayed as a black bar between the quadrotors, with green ends signifying an extension and magenta, a compression in the connecting ends. The circles about the target on which the quadrotors have to settle are also displayed for clarity.  The reference distances re:<br>

<img src="https://render.githubusercontent.com/render/math?math=r^d_{1,2} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,1} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,2} = 3">m

<img src="https://render.githubusercontent.com/render/math?math=v_x^a"> is the x-velocity of quadrotor relative to the air in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_y^a"> is the y-velocity of quadrotor relative to the air in inertial frame<br>

<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
