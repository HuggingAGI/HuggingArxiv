# 量子玻尔兹曼机学习基态能量

发布时间：2024年10月16日

`其他` `量子计算`

> Quantum Boltzmann machine learning of ground-state energies

# 摘要

> 摘要：估计哈密顿量的基态能量是量子计算的一个基础任务。我们探讨了量子玻尔兹曼机在此任务中的表现，这是一种基于参数化热态的假设，且不受贫瘠高原问题的影响。我们设计了一种混合量子经典算法，并证明它能有效收敛于能量函数的 $\varepsilon$-近似驻点。该算法通过结合经典采样、哈密顿量模拟和阿达玛测试，克服了量子玻尔兹曼机学习中的关键障碍。此外，我们还计算了能量函数的梯度和 Hessian，并提供了 Hessian 矩阵元素的上界，以支持我们的理论分析。

> 
Abstract:Estimating the ground-state energy of Hamiltonians is a fundamental task for which it is believed that quantum computers can be helpful. Several approaches have been proposed toward this goal, including algorithms based on quantum phase estimation and hybrid quantum-classical optimizers involving parameterized quantum circuits, the latter falling under the umbrella of the variational quantum eigensolver. Here, we analyze the performance of quantum Boltzmann machines for this task, which is a less explored ansatz based on parameterized thermal states and which is not known to suffer from the barren-plateau problem. We delineate a hybrid quantum-classical algorithm for this task and rigorously prove that it converges to an $\varepsilon$-approximate stationary point of the energy function optimized over parameter space, while using a number of parameterized-thermal-state samples that is polynomial in $\varepsilon^{-1}$, the number of parameters, and the norm of the Hamiltonian being optimized. Our algorithm estimates the gradient of the energy function efficiently by means of a novel quantum circuit construction that combines classical sampling, Hamiltonian simulation, and the Hadamard test, thus overcoming a key obstacle to quantum Boltzmann machine learning that has been left open since [Amin \textit{et al.}, Phys.~Rev.~X \textbf{8}, 021050 (2018)]. Additionally supporting our main claims are calculations of the gradient and Hessian of the energy function, as well as an upper bound on the matrix elements of the latter that is used in the convergence analysis.
    

[Arxiv](https://arxiv.org/pdf/2410.12935)