### Nonlinear Contouring MPC

🏁 I was involved in developing a raceline optimization based on a minimum curvature trajectory to reduce steering effort and generate a smoother target path for the controller.

![Raceline Optimization](/media/control/rl.png)

⚙️ Implemented a GGV based velocity planner using raceline curvature to compute the maximum feasible speed along the track while respecting the vehicle dynamic limits.

![Velocity Planner](/media/control/vel1.png)

📐 Integrating these features into the NMPC controller enabled optimal racing trajectory tracking while still respecting physical constraints of the car.

![NMPC Control](/media/control/vel2.png)

🚀 When comparing against the previous controller without raceline optimization and without velocity planning, performance and efficiency improved significantly.

![NMPC Control Result](/media/control/results.png)
