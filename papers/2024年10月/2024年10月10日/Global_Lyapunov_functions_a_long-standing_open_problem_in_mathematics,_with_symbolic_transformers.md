# 全局 Lyapunov 函数，一个数学界长期悬而未决的难题，与符号变换器紧密相关。

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Global Lyapunov functions: a long-standing open problem in mathematics, with symbolic transformers

# 摘要

> 尽管语言模型取得了显著进展，但在复杂推理任务（如高级数学）上仍显不足。我们探讨了一个长期未解的数学难题：寻找确保动力系统全局稳定性的Lyapunov函数。此问题尚无通用解法，现有算法仅适用于部分小型多项式系统。我们提出了一种从随机解生成训练样本的新方法，并证明在此类数据集上训练的序列到序列变换器不仅超越了算法求解器和人类在多项式系统上的表现，还能为非多项式系统发现新的Lyapunov函数。

> 
Abstract:Despite their spectacular progress, language models still struggle on complex reasoning tasks, such as advanced mathematics. We consider a long-standing open problem in mathematics: discovering a Lyapunov function that ensures the global stability of a dynamical system. This problem has no known general solution, and algorithmic solvers only exist for some small polynomial systems. We propose a new method for generating synthetic training samples from random solutions, and show that sequence-to-sequence transformers trained on such datasets perform better than algorithmic solvers and humans on polynomial systems, and can discover new Lyapunov functions for non-polynomial systems.
    

[Arxiv](https://arxiv.org/pdf/2410.08304)