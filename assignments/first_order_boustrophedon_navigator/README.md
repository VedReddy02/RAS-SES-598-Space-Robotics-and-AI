
Final Parameters

self.Kp_linear = 1.5   # Proportional gain for linear velocity, Increasing this parameter abrubtly would force the turtle to go in circles and making it very low would decrease the speed

self.Kd_linear = 0.09   # Derivative gain for linear velocity, Increasing this parameter would make the turtle move back and forth, which is not desired. This motion will not give us the required results

self.Kp_angular = 8.0  # Proportional gain for angular velocity, This parameter controls the turning of the turtle and a large value would make a sudden turn which could lead to intersections ans a low value would make a long turn which would make the trajectory inefficient

self.Kd_angular = 0.05  # Derivative gain for angular velocity, This parameter is responsible for quickly stabilizing the path just after turning, so a high value would bring in oscillations in the trajectory and a lower value would take it longer to stabilize

self.spacing = 0.5     # Spacing between lines, The spacing betweem lines is minimized such that there are no intersections and also not much of a gap between the lines of the trajuctory

Methodology

The method followed was to tune one parameter at a time and the following was done
1. Kp_linear was set to a high value which resulted in circular trajectory, not ideal. The value was brought down until the turtle followed the desired path.
2. Kd_linear was increased abruptly which caused the Turtle to move back and forth in random positions, the valur was decreased until the turtle was able to move in the desired trajectory, this trajectory was not efficient as the angular parameters still had to be tuned.
3. Kp_angular was set to a low value and this led to the turtle taking long turns and an inefficient trajectory, setting it to a high value caused the turtle to take quick turns and intersect with the path already traversed.
4. Kd_angular increasing this parameter caused a rapid oscillation in the trajectory when turning, to smoothen the trajectory this parameter was set to a lower value.

