# 用于全光矩阵-矩阵乘法的光子脉动阵列

发布时间：2024年10月28日

`其他` `机器学习` `光子计算`

> Photonic systolic array for all-optical matrix-matrix multiplication

# 摘要

> 收缩阵列在并行化矩阵-矩阵乘法（MMM）方面表现出色，通过一系列处理元素中的同步、类似心跳的数据流实现高效运算。尽管波导交叉开关阵列和基于马赫-曾德尔干涉仪的网格等光学结构可视为收缩阵列的光子等价物，但用于乘法的两个输入矩阵存在差异，一个用光信号，另一个用系统定义的参数，这在现代机器学习任务（如评估大型语言模型中的注意力分数）中形成了瓶颈。在此，我们提出一种完全用光信号进行 MMM 的光子收缩阵列，在每个阵列单元采用零差检测。基于伴随的紧凑片上自由形式光学模块设计，能精确控制光流，无需庞大的波导耦合方案。对 4×4 光子收缩阵列的操作进行了数值验证，达到 6.2 PMACs/mm²/s 的理论计算密度。此设计为迈向适用于现代 AI 工作负载的实用光子计算硬件迈出了重要一步。

> Systolic arrays have proven to be highly efficient for parallelized matrix-matrix multiplication (MMM), utilizing synchronized, heartbeat-like data flows across an array of processing elements. While optical structures such as waveguide crossbar arrays and Mach-Zehnder interferometer-based meshes serve as photonic equivalents to the systolic arrays, the disparity between the two input matrices for multiplication -- one using optical signals and the other with system-defined parameters -- gives rise to a bottleneck in modern machine-learning tasks, such as evaluating attention scores in large language models. Here, we propose a photonic systolic array that performs MMM entirely with optical signals, utilizing homodyne detection at each array cell. Adjoint-based design of compact on-chip freeform optical modules enables precise control of light flow without bulky waveguide coupling schemes. The operation of a $4\times4$ photonic systolic array is numerically verified, achieving a theoretical computation density of $6.2~\mathrm{PMACs}/\mathrm{mm}^2/\mathrm{s}$. This design marks a significant step toward practical photonic computing hardware for modern AI workloads.

[Arxiv](https://arxiv.org/abs/2410.21671)