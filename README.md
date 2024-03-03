# Servus or Hey there!

Welcome to my Github ✨
I am about to finish my masters degree in CSE (Computational Science and Engineering) at [TU Wien](https://www.tuwien.at/) in Vienna, Austria. My B.Sc was in Mechanical Engineering and Management, also at TU Wien - I was part of exchange programs to [ETH Zürich](https://www.ethz.ch/), [Chalmers](https://www.chalmers.se/) and most recently a visiting researcher at the [University of California - Santa Barbara](https://www.ucsb.edu/) for my M.Sc thesis. 

Best way to reach out to me would be at [/in/grubeben](https://www.linkedin.com/in/benjamin-gruber-4817781a1/), even though I am not on the platform regularly.

Most of my university/internship projects are in private repos, but some are available here (_or somewhat available_ 🍳). My M.Sc. thesis which comprised
extensions to a hihgly-parallelized C-implementation of DNS (Direct Numerical Simulation) [code](https://github.com/metialex/PARTIES) for multiphase flows and computational investigation into ’particle retardation (suspension against gravitational force) in a vertically oscillating fluid’ will be linked here once published. The code is currently not made public by Prof. Meiburg's group (UCSB).

---

## 🏃[HPC - Comparison of doubly-pipelined and a binary-tree-based MPI_Allreduce](https://github.com/grubeben/HPC)🏃


As part of the High-Performance-Computing seminar held by Jesper Larsson-Träff at TU Wien, me and a fellow student worked on a complexity analysis and C++-implementations of the MPI_Allreduce operation based on arXiv:2109.12626. Our implementation achieved outperformance of 10-50% against the MPICH implementation on TU-Wien’s ’Hydra’ cluster which was available for the seminar.

You can find the porject report [here](https://github.com/grubeben/HPC/blob/main/PROJECT_REPORT.pdf).

<img src="https://github.com/grubeben/HPC/blob/main/hpc_benchmark.PNG?raw=true" width="500">

_performance comparison of custom implementation vs. MPICH library implementation_


---

## 🧮[HPC/GPU - Vectorized operations on an NVIDIA grpahic card](https://github.com/grubeben/194.077-Applied-Deep-Learning)🧮

asdfasdf

<img src="https://github.com/grubeben/194.077-Applied-Deep-Learning/blob/main/obs-samples/rewards_over_time_a2c_discrete.PNG?raw=true" width="500">

_The A2C-agents trainings success for different agent configurations_

---

## 🔒[HPC - A variety of shared-register lock implementations (omp)](https://github.com/grubeben/AMP)🔒

As part of the Applied Multiprocessor Programming seminar held by Jesper Larsson-Träff at TU Wien, me and a fellow student made this omp-standard based C-implementation of lock mechanisms proposed in literature (assuring singular access to register) for a finite number of threads. Performance analysis based on fairness, latency and throughput metric.

You can find the porject report [here](https://github.com/grubeben/AMP/blob/master/amp_report.pdf).

<img src="https://github.com/grubeben/AMP/blob/master/amp_treelock.PNG?raw=true" width="500">

_structure of an n-thread tree lock and the registers necessary for it's implementation_

---

## 🤖[Reinforcement Learning - Advantage-Actor-Critic (A2C) implementation](https://github.com/grubeben/194.077-Applied-Deep-Learning)🤖

In a prior internship with Bosch I implemented a ’Deep-Q’ reinforcement-learning algorithm to optimize energy-contribution from combustion- and electric engine in hybrid vehicles (code is unfortunately not publicly available). While the ’Deep-Q’ algorithm features a single neural network and is purely value-based (the algorithm learns the state or state-action value), I wanted to investifate policy-based reinforcement learning (the algorithm directly learns the policy rather than the state values). As part of my Applied Deep Learning seminar project at TU Wien I implemented an Advantage-Actor-Critic(A2C) agent which comprises two neural networks (the actor and the critic where the latter learns the state or state-action value and the former directly learns a policy). I employed two agent versions (discrete vs. continous state space) in a couple of openAI-gym environments and investigated how input normalization and activation functions change the learning speed. The continous-state-space version proved to be much harder to implement and struggles to arrive at a converged policy.

You can find a short video presentation of the porject [here](https://www.youtube.com/watch?v=bbEv1J6oSts).

<img src="https://github.com/grubeben/194.077-Applied-Deep-Learning/blob/main/obs-samples/rewards_over_time_a2c_discrete.PNG?raw=true" width="500">

_The A2C-agents trainings success for different agent configurations_



<!--
**grubeben/grubeben** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
