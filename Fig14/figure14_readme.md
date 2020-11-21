## Figure 14
This figure covers the case of a Nonlinear model of quadrotor motion and a moving target with velocity <img src="https://render.githubusercontent.com/render/math?math=v = [2,1]"> m/s. Wind <img src="https://render.githubusercontent.com/render/math?math=v_a = [2,2,0]^T">m/s and sensor noise are considered here. Control is applied along the line-of-sights of the quadrotors and target and in the corresponding lateral directions. The quadrotors are required to be at desired angular positions about the target. The gains for the simulation are:<br>

<img src="https://render.githubusercontent.com/render/math?math=K_{P} = 0.3">
<img src="https://render.githubusercontent.com/render/math?math=K_{Pr} = 1">
<img src="https://render.githubusercontent.com/render/math?math=K_{D} = 0.9">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr} = 1.8">
<img src="https://render.githubusercontent.com/render/math?math=K_{P\alpha} = 0.3">
<img src="https://render.githubusercontent.com/render/math?math=K_{Dr\alpha} = 0.2">
<img src="https://render.githubusercontent.com/render/math?math=K_{D\alpha} = 0.2">

The position of the quadrotors (Q1 and Q2) are plotted in two-dimensional space over time, showing the trajectory, instantaneous velocity and acceleration input directions. The target (T) is displayed in green. The load is displayed as a black bar between the quadrotors, with green ends signifying an extension and magenta, a compression in the connecting ends. The circles about the target on which the quadrotors have to settle are also displayed for clarity. The reference distances and angales are:<br>

<img src="https://render.githubusercontent.com/render/math?math=r^d_{1,2} = 4">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,1} = 6">m

<img src="https://render.githubusercontent.com/render/math?math=r^d_{T,2} = 4">m

<img src="https://render.githubusercontent.com/render/math?math=\gamma_{1,T} = 150\circ">

<img src="https://render.githubusercontent.com/render/math?math=\gamma_{1,T} = 191.4\circ">



<img src="https://render.githubusercontent.com/render/math?math=v_x^a"> is the x-velocity of quadrotor relative to the air in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_y^a"> is the y-velocity of quadrotor relative to the air in inertial frame<br>

<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
<img src="https://render.githubusercontent.com/render/math?math=v_x^g"> is the x-velocity of target relative to the ground in inertial frame<br>
