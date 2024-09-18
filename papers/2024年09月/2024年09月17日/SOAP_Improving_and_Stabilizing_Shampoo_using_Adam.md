# SOAP：借助 Adam 优化 Shampoo，提升其稳定性和效果

发布时间：2024年09月17日

`LLM理论` `人工智能`

> SOAP: Improving and Stabilizing Shampoo using Adam

# 摘要

> 越来越多的证据表明，Shampoo 在深度学习优化任务中比 Adam 更胜一筹。然而，Shampoo 的额外超参数和计算开销使其不如 Adam 简洁。本研究揭示了 Shampoo 与 Adafactor 之间的内在联系，并设计出一种更高效的算法：SOAP。SOAP 通过在旋转空间中运行 Adam，仅引入一个额外超参数，显著提升了计算效率。实验表明，在大规模语言模型预训练中，SOAP 不仅减少了迭代次数和时间，还超越了 AdamW 和 Shampoo 的表现。SOAP 的代码已公开，供大家探索和应用。

> There is growing evidence of the effectiveness of Shampoo, a higher-order preconditioning method, over Adam in deep learning optimization tasks. However, Shampoo's drawbacks include additional hyperparameters and computational overhead when compared to Adam, which only updates running averages of first- and second-moment quantities. This work establishes a formal connection between Shampoo (implemented with the 1/2 power) and Adafactor -- a memory-efficient approximation of Adam -- showing that Shampoo is equivalent to running Adafactor in the eigenbasis of Shampoo's preconditioner. This insight leads to the design of a simpler and computationally efficient algorithm: $\textbf{S}$hampo$\textbf{O}$ with $\textbf{A}$dam in the $\textbf{P}$reconditioner's eigenbasis (SOAP).
  With regards to improving Shampoo's computational efficiency, the most straightforward approach would be to simply compute Shampoo's eigendecomposition less frequently. Unfortunately, as our empirical results show, this leads to performance degradation that worsens with this frequency. SOAP mitigates this degradation by continually updating the running average of the second moment, just as Adam does, but in the current (slowly changing) coordinate basis. Furthermore, since SOAP is equivalent to running Adam in a rotated space, it introduces only one additional hyperparameter (the preconditioning frequency) compared to Adam. We empirically evaluate SOAP on language model pre-training with 360m and 660m sized models. In the large batch regime, SOAP reduces the number of iterations by over 40% and wall clock time by over 35% compared to AdamW, with approximately 20% improvements in both metrics compared to Shampoo. An implementation of SOAP is available at https://github.com/nikhilvyas/SOAP.

[Arxiv](https://arxiv.org/abs/2409.11321)