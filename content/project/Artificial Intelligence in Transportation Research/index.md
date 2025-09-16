---
title: Artificial Intelligence in Transportation Research
summary: Apply reinforcement learning to autonomous driving decision-making, enabling AVs to drive adaptively in traffic.
date: 2019-06-01
# external_link: https://github.com/pytorch/pytorch
tags:
  - Reinforcement learning
  - Deep learning
  - Driving behavior modeling
---
<div align="justify">My research applies advanced artificial intelligence to revolutionize autonomous vehicle behavior and decision-making in transportation systems. The central challenge I address is that traditional approaches treat driving behaviors as isolated processes, failing to capture the interconnected nature of real-world traffic dynamics. Through deep learning and reinforcement learning techniques, I develop AI systems that understand and replicate the integrated, adaptive decision-making that characterizes skilled human driving.</div>


<h3> Reinforcement Learning for Decision-Making</h3>
<img src="basic_DRL.jpg" alt="DRL-based decision making">
<div align="justify">While autonomous vehicle perception has advanced rapidly, decision-making capabilities remain underdeveloped. I address this through a comprehensive framework combining deep reinforcement learning with high-fidelity simulation environments. This enables autonomous vehicles to learn optimal decision strategies that achieve nearly eight percent efficiency improvements over established adaptive cruise control systems while maintaining safety and comfort.<br>
<img src="DRL_result.jpg" alt="DRL-based decision making">
Extending to complex multi-lane scenarios, my integrated models achieve additional performance gains by coordinating longitudinal and lateral movements as unified decision processes.</div>


<h3> Hierarchical AI Integration</h3>
<img src="TFA_DRL.svg" alt="Hierarchical DRL with rule-based models for AV decision-making">
<div align="justify">Recognizing the need for both learning capability and interpretability in safety-critical applications, I have developed hierarchical frameworks that strategically combine reinforcement learning with rule-based methods. Through the concept of Instantaneous Desired Speed as an intermediate action, high-level AI algorithms focus on strategic decisions while low-level systems handle tactical execution. This approach maintains the adaptability of machine learning while preserving the transparency of traditional control systems.<br>
<img src="TFA_results.svg" alt="Results of TFA strategy">
My Traffic Flow Adaptive strategy extends this hierarchical approach to system-level optimization, enabling individually controlled autonomous vehicles to coordinate for improved overall traffic flow. This shift from isolated decision-making to collaborative traffic participation represents a crucial advancement toward practical autonomous vehicle deployment.</div>

<h3> Research Impact</h3>
<div align="justify">Through rigorous validation using real-world data and comprehensive benchmarking, my research demonstrates that artificial intelligence can create autonomous driving systems that are both more human-like and more efficient than existing approaches. By developing models that integrate multiple driving behaviors, learn from experience, and maintain interpretability, I am establishing the foundation for autonomous vehicles that can operate effectively in mixed traffic environments alongside human drivers. This work contributes directly to the vision of intelligent transportation systems where AI-enabled vehicles enhance both individual mobility and overall traffic system performance.</div>

<h3> References</h3>
<div align="justify">
<cite> 
<ul>
<li>Ye, Y.*, <b>Zhang, X.</b>*, Sun, J., 2019. Automated vehicle’s behavior decision making using deep reinforcement learning and high-fidelity simulation environment. Transportation Research Part C: Emerging Technologies 107, 155–170.</li>
<li><b>Zhang, X.</b>, Sun, Jie, Wang, Y., Sun, Jian, 2023. A Hierarchical Framework for Multi-Lane Autonomous Driving Based on Reinforcement Learning. IEEE Open Journal of Intelligent Transportation Systems 4, 626–638.</li></ul> 
</cite>
</div>
<!-- PyTorch is a Python package that provides tensor computation (like NumPy) with strong GPU acceleration. -->

<!--more-->
