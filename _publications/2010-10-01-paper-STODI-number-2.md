---
title: "Stochastic Trajectory Optimization for Robotic Skill Acquisition From a Suboptimal Demonstration"
collection: publications
category: manuscripts
permalink: /publication/2024-08-06-paper-STODI-number-2
excerpt: "Learning from Demonstration (LfD) has emerged as a crucial method for robots to acquire new skills. However, when given suboptimal task trajectory demonstrations with shape characteristics reflecting human preferences but subpar dynamic attributes such as slow motion, robots not only need to mimic the behaviors but also optimize the dynamic performance. In this work, we leverage optimization-based methods to search for a superior-performing trajectory whose shape is similar to that of the demonstrated trajectory. Specifically, we use Dynamic Time Warping (DTW) to quantify the difference between two trajectories and combine it with additional performance metrics, such as collision cost, to construct the cost function. Moreover, we develop a multi-policy version of the Stochastic Trajectory Optimization for Motion Planning (STOMP), called MSTOMP, which is more stable and robust to parameter changes. To deal with the jitter in the demonstrated trajectory, we further utilize the gain-controlling method in the frequency domain to denoise the demonstration and propose a computationally more efficient metric, called Mean Square Error in the Spectrum (MSES), that measures the trajectories' differences in the frequency domain. We also theoretically highlight the connections between the time domain and the frequency domain methods. Finally, we verify our method in both simulation experiments and real-world experiments, showcasing its improved optimization performance and stability compared to existing methods."
date: 2025-04-11
venue: 'RA-L'
paperurl: 'https://arxiv.org/pdf/2408.03131'
citation: 'Ming, C., Wang, Z., Zhang, B., Duan, X., & He, J. (2024). Stochastic Trajectory Optimization for Demonstration Imitation. arXiv preprint arXiv:2408.03131.'
---
