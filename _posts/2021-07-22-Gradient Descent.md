# Intuitive explanation of gradient descent

Recently, the temperature in Paris has been rising slightly, and my heating configuration is no longer satisfactory. Let's define a cost function J(θ): the difference between the actual and the desired temperature. The goal is to find the θ (knob configuration) that minimizes J.
The process works as follows:

The knob has two possible directions (left or right).
I start with a random turn and observe the resulting temperature.
If it's closer to my desired temperature, I continue in that direction. This is essentially the gradient part of gradient descent.

My adjustments should be proportional to the change in output temperature. The α (alpha) parameter controls this proportionality. In machine learning terms, this is our learning rate.
As I get closer to the desired output, I naturally tend to slow down, reducing the amplitude of my adjustments to avoid overshooting that perfect spot. This mirrors the behavior of gradient descent as it approaches the minimum of the cost function.
It's worth noting that gradient descent can be misleading in some cases:

Local minima: I might find a temperature that feels good but isn't the best possible.
Saddle points: For example, the perfect spot for my comfort might result in a high utility bill. If I'm concerned about the bill too, this introduces a multi-objective optimization problem.


<video width="100%" height="400" controls>
  <source src="/videos/GD_VIZ.mp4" type="video/mp4">
</video>
