# AutoTurb：借助大型语言模型，自动探索湍流闭包的代数模型

发布时间：2024年10月14日

`LLM应用` `流体力学` `计算流体动力学`

> AutoTurb: Using Large Language Models for Automatic Algebraic Model Discovery of Turbulence Closure

# 摘要

> 符号回归 (SR) 方法广泛用于探索显式代数雷诺应力模型 (EARSM)，以闭合雷诺平均 Navier-Stokes (RANS) 方程的湍流。推导出的 EARSM 易于在现有计算流体动力学 (CFD) 代码中实现，并有助于识别物理可解释的湍流模型。然而，现有 SR 方法如遗传编程、稀疏回归或人工神经网络，需要用户定义的操作符、候选库或复杂优化算法。本研究提出了一种利用 LLM 自动发现修正 RSM 代数表达式的新框架。雷诺应力的直接观测和 CFD 模拟的间接输出均参与训练，确保数据一致性并避免数值刚性。鉴于 LLM 的灵活性，目标函数中额外施加了功能复杂性和收敛性约束。采用进化搜索进行全局优化。该方法在 Re = 10,595 的周期性山丘分离流中进行了测试，并在不同雷诺数和几何形状的 2D 湍流分离流中验证了其泛化能力。结果显示，修正的 RANS 显著提升了雷诺应力和平均速度场的预测精度。与其他代数模型相比，所发现模型在准确性和泛化能力上表现更优。本研究为利用 LLM 改进特定流类的湍流建模提供了新的思路。

> Symbolic regression (SR) methods have been extensively investigated to explore explicit algebraic Reynolds stress models (EARSM) for turbulence closure of Reynolds-averaged Navier-Stokes (RANS) equations. The deduced EARSM can be readily implemented in existing computational fluid dynamic (CFD) codes and promotes the identification of physically interpretable turbulence models. The existing SR methods, such as genetic programming, sparse regression, or artificial neural networks, require user-defined functional operators, a library of candidates, or complex optimization algorithms. In this work, a novel framework using LLMs to automatically discover algebraic expressions for correcting the RSM is proposed. The direct observation of Reynolds stress and the indirect output of the CFD simulation are both involved in the training process to guarantee data consistency and avoid numerical stiffness. Constraints of functional complexity and convergence are supplementally imposed in the objective function on account of the tremendous flexibility of LLMs. The evolutionary search is employed for global optimization. The proposed method is performed for separated flow over periodic hills at Re = 10,595. The generalizability of the discovered model is verified on a set of 2D turbulent separated flow configurations with different Reynolds numbers and geometries. It is demonstrated that the corrective RANS can improve the prediction for both the Reynolds stress and mean velocity fields. Compared with algebraic models discovered by other works, the discovered model performs better in accuracy and generalization capability. The proposed approach provides a promising paradigm for using LLMs to improve turbulence modeling for a given class of flows.

[Arxiv](https://arxiv.org/abs/2410.10657)