# 用通俗易懂的方式：借助 LLM 提升 PDE 代理模型的文本处理能力

发布时间：2024年10月01日

`LLM应用`

> Explain Like I'm Five: Using LLMs to Improve PDE Surrogate Models with Text

# 摘要

> 在科学和工程领域，解决偏微分方程 (PDEs) 是常见任务。计算复杂性和数值求解器的编写难度推动了机器学习技术的发展，以快速生成解决方案。尽管许多现有方法仅依赖数值解场，但大型语言模型 (LLMs) 的兴起使得在多模态机器学习模型中轻松集成文本成为可能。我们利用预训练的 LLMs 将已知的系统信息集成到 PDE 学习中，结果表明，我们的多模态方法在多个方程的预测和展开性能上显著优于基线模型 FactFormer。进一步分析显示，预训练的 LLMs 提供了与文本提供的系统信息量一致的高度结构化潜在空间。

> Solving Partial Differential Equations (PDEs) is ubiquitous in science and engineering. Computational complexity and difficulty in writing numerical solvers has motivated the development of machine learning techniques to generate solutions quickly. Many existing methods are purely data driven, relying solely on numerical solution fields, rather than known system information such as boundary conditions and governing equations. However, the recent rise in popularity of Large Language Models (LLMs) has enabled easy integration of text in multimodal machine learning models. In this work, we use pretrained LLMs to integrate various amounts known system information into PDE learning. Our multimodal approach significantly outperforms our baseline model, FactFormer, in both next-step prediction and autoregressive rollout performance on the 2D Heat, Burgers, Navier-Stokes, and Shallow Water equations. Further analysis shows that pretrained LLMs provide highly structured latent space that is consistent with the amount of system information provided through text.

[Arxiv](https://arxiv.org/abs/2410.01137)