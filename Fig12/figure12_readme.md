## Figure 12
This figure covers the case of a nonlinear quadrotor model motion with quadrotors circling a static target with <img src="https://render.githubusercontent.com/render/math?math=\bar{\omega} = 0.1"> rad/s, with wind  <img src="https://render.githubusercontent.com/render/math?math=v_a = [2,2,0]^T"> m/s and sensor noise<br>

<img src="https://render.githubusercontent.com/render/math?math=K_{P} = 0.2">
<img src="https://render.githubusercontent.com/render/math?math=K_{Pr} = 0.1">
<img src="https://render.githubusercontent.com/render/math?math=K_{D} = 0.9">
<img src="https://render.githubusercontent.com/render/math?math=K_{P\alpha} = 0">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr\alpha} = 0">
<img src="https://render.githubusercontent.com/render/math?math=K_{D\alpha} = 0.2">

12a. Control law: Full information control, <img src="https://render.githubusercontent.com/render/math?math=K_{Dr} = 0.5"><br>
12b. Control law: 4.4 from Table 4, <img src="https://render.githubusercontent.com/render/math?math=K_{Dr} = 0"><br>

Control is applied along the line-of-sights of the quadrotors and target and in the lateral directions.

The position of the quadrotors (Q1 and Q2) are plotted in two-dimensional space over time, showing the trajectory, instantaneous velocity and acceleration input directions. The target (T) is displayed in green. The load is displayed as a black bar between the quadrotors, with green ends signifying an extension and magenta, a compression in the connecting ends. The circles about the target on which the quadrotors have to settle are also displayed for clarity. The reference ditances to be maintained are:<br>


<img src="https://render.githubusercontent.com/render/math?math=r^d_{1,2} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,1} = 2">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,2} = 3">m

<img src="https://render.githubusercontent.com/render/math?math=v_x^a"> is the x-velocity of quadrotor relative to the air in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_y^a"> is the y-velocity of quadrotor relative to the air in inertial frame<br>

<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
