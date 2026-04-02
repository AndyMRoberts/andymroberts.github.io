---
title: Papers
permalink: /papers/
---

{% include site-nav.html %}

### Embedded Computing for Environmental Sensing and Mapping in Agricultural Robots: A Power and Performance Analysis

_June 2025_

_Published as part of Sensors Applications Symposium Proceedings_

**Abstract**—Recent trends in agriculture show decreasing availability of
agricultural workers, coupled with reduction in productivity and yield
due to climate change. Autonomous agricultural robots are a suitable
technology to counter these issues, but in order to gain widespread use
they must be able to effectively localise themselves in complex rural
environments, whilst being able to run for long periods of time.This
paper aims to aid in the selection of Simultaneous Localisation And
Mapping (SLAM) variants and parameters when used in the agricultural
field in order to maximise range/operational time with minimal sacrifice
of effectiveness as evaluated by Percentage Tracked Path (PTP) and
Average Trajectory Error (ATE). We investigate some of the most
promising applications of ORB-SLAM algorithms, running on a low-
resource system, providing insights into the energy costs of increased real-
time performance in terms of Frames Per Second (FPS) achieved through
varying SLAM parameters. Our contributions are: a full Energy Per
Frame (EPF) analysis over all ORB-SLAM parameters; SLAM analysis
of a benchmark LFSD dataset, entirely performed on a common low-
resource robotics computer, Jetson Nano; evaluation of the determined
parameters to achieve highest PTP at lowest EPF; and live trials on the
Turtlebot robotic platform using the determined parameters. This work
demonstrates that the most power efficient and accurate performance of
the variants tested can be attained using ORB-SLAM3 with the number
of features reduced to 600. This improved on default parameter operation
by 20% on EPF and 8.21% on PTP. This outcome was corroborated in
live testing achieving a similar 14.4% EPF drop to 321.83 ± 46.14 mJ.
Therefore, utilising our power performance evaluation, power can be
optimised for real-time usage based on the parameters selection, enabling
a more accurate and power-efficient SLAM for longer operation time in
the field.

Links:
[PDF copy]({% link assets/paper1.pdf %}) · [IEEE Xplore](https://ieeexplore.ieee.org/document/11105118)
