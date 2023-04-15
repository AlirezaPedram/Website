---
layout: page
permalink: /Research/
---
**Doctorial Dissertation:** <p align = "justify"> My research focuses on developing theoretical foundations and computational methods that enable autonomous systems to operate safely in uncertain, complex environments with minimum perception effort. The following are some of the projects I have been working on for the past few years.</p>

***
<center> <h3>Rationally Inattentive Vision and Planning </h3> </center>
<p align = "justify">
This research is motivated by the increasing need for simultaneous perception and action planning in modern information-rich autonomy. Due to the wide availability of low-cost and high-performance sensing devices, 
obtaining a large amount of sensor data has become easier in many applications. Nevertheless, operating a sensor at its full capacity may not be the best strategy for resource-constrained robots, especially if it drains 
its scarce power or computational resources with little benefit. As sensor modalities increase, how to achieve a given task with minimum perceptual resources, e.g., with reduced sensing/communication frequencies or sensor gains, becomes increasingly relevant. 
</p>
<p align = "justify">
In the first phase of this project, we propose a task-dependent attention allocation for vision-based autonomous navigation inspired from attention mechanisms in humans. The proposed mechanism helps the robot to analyze the visual information relevant to the task at hand while neglecting the rest of the available data. In the second phase, we develop a framework to predict and incorporate the perception cost in the motion planning stage, which help the autonomous agent to find motion plans that can be executed with both minimum control and perception efforts. We modify existing motion-planning algorithms (like sampling-based methods) to be able to integrate the perception effort.    
</p>
<p align="center">
<img src="../capture.png" width="800" />
</p>
<p align="center">
Optimal path plans obtained for different values of perception effort intensity &alpha;.
</p>

<span style="line-height: 0;">_Related Publications:_</span>\\
<b> A Smoothing Algorithm for Minimum Sensing Path Plans in Gaussian Belief Space</b> AR. Pedram , T. Tanaka, American Control Conference, 2023 <a href='https://arxiv.org/pdf/2303.07326.pdf'>[Link]</a>\\
<b> Gaussian Belief Space Path Planning for Minimum Sensing Navigation</b>,  AR. Pedram , R. Funada, T. Tanaka, IEEE Transactions on Robotics, 2022  <a href = 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10001826&tag=1'>[Link]</a>\\
<b>Dynamic Allocation of Visual Attention for Vision-based Autonomous Navigation under Data Rate Constraints</b>, AR. Pedram, R. Funada, T. Tanaka, IEEE Conference on Decision and Control, 2021 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9683570)\\'>[Link]</a>\\
<b>Rationally Inattentive Path-Planning via RRT*</b>, AR. Pedram, J. Stefan, R. Funada, T. Tanaka, American Control Conference, 2021 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9483305'>[Link]</a>
{: style="text-align: justify"}
***

<center> <h3> Feedback Capacity of Gaussian Channels with Memory: Implications in Autonomy </h3> </center>
<p align = "justify">
In this research, we study the information-theoretic problem of computing the capacity of  Gaussian channels with partial feedback whose dynamics are expressed as a linear state-space system, where we seek the maximum number of bits that could be communicated reliably with bounded input power. We show this problem appears in different contexts of autonomy, like in the identification of linear dynamic systems and in the privacy of linear dynamic systems in the cloud-based control setting. In this project, I establish several theoretical results. For instance,  I show the identification rate of linear dynamic systems is fundamentally upper bounded by a linear function of the identification step, and no policy can achieve a super-linear convergence rate.  I  illustrate the privacy of dynamical systems in cloud-based settings is not necessarily a monotone function of the noise levels of privacy masks. I also show both input and out masks are required, as opposed to static
date-base setting.  
</p>
<span style="line-height: 0;">_Related Publications:_</span>\\
<b>Optimized Data Rate Allocation for Dynamic Sensor Fusion over Resource Constrained Communication Networks</b>, H. Jung, AR. Pedram,  T. Cuvelier, T. Tanaka,  International Journal of Robust and Nonlinear Control, 2023  <a href='https://onlinelibrary.wiley.com/doi/pdf/10.1002/rnc.6076'>[Link]</a>\\
<b>Online Parameter Identification of Linear Dynamical Systems through the Lens of Feedback Channel Coding Theory</b>, AR. Pedram, T. Tanaka,  American Control Conference, 2020  <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9147986)\\'>[Link]</a>\\
<b> Bidirectional Information Flow and the Roles of Privacy Masks in Cloud-Based Control </b>, AR. Pedram, T. Tanaka, M. Hale, IEEE Information Theory Workshop, 2019 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8989371)\\'>[Link]</a>\\
<b> Some Results on the Computation of Feedback Capacity of Gaussian Channels with Memory</b>, AR. Pedram, T. Tanaka, Allerton Conference on Communication, Control,
and Computing, 2018 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8636014 '>[Link]</a>
{: style="text-align: justify"}
***

<center> <h3>Linearly Solvable Mean-Field Traffic Routing Games</h3> </center>
<p align = "justify"> In this project, we study the strategic behavior of drivers travelling over an urban traffic network in the limit of many drivers.
We propose an incentive mechanism (toll charge) which is congestion-dependent and affine in the logarithm of the number of drivers taking the same route. We apply the mean-field game (MFG) theory to this problem and show that the backward Hamilton-Jacobi-Bellman and forward Fokker-Planck-Kolmogorov equations can be solved independently. We show a mean-field equilibrium (MEF) is obtained through a linearly-solvable set of equations, and the MFE is strongly time-consistent.  We extend the results for multi-team settings. 
</p>
<p align="center">
<img src="../game.png" width="600" />
</p>
<p align="center">
Optimal density propagation of team one (red) and team two (blue) in a sample environment.
</p>
<span style="line-height: 0;">_Related Publications:_</span>\\
<b>Linearly Solvable Mean-Field Traffic Routing Games</b>, T. Tanaka, E. Nekouei, AR. Pedram, KH. Johansson, IEEE Transactions on Automatic Control, 2020 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9061051)\\'>[Link]</a>\\
<b> Linearly-Solvable Mean-Field Approximation for Multi-Team Road Traffic Games</b>, AR. Pedram, T. Tanaka, IEEE Conference on Decision and Control, 2019 <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9029579)\\'>[Link]</a>
{: style="text-align: justify"}
***



