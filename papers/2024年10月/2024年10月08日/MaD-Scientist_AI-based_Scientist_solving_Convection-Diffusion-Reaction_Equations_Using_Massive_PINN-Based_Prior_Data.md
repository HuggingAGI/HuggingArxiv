# MaD-Scientist：这位 AI 科学家利用海量 PINN 先验数据，轻松破解对流-扩散-反应方程难题。

发布时间：2024年10月08日

`LLM应用` `科学研究` `人工智能`

> MaD-Scientist: AI-based Scientist solving Convection-Diffusion-Reaction Equations Using Massive PINN-Based Prior Data

# 摘要

> 像 ChatGPT 这样的大型语言模型 (LLM) 展示了，即使训练数据带有噪声，通过 in-context learning (ICL) 和预训练技术，它们也能有效应对新任务。基于此，我们探索是否可以将类似方法应用于科学基础模型 (SFM)。我们的研究步骤如下：首先，我们收集低成本的基于物理信息神经网络 (PINN) 的近似先验数据，这些数据以偏微分方程 (PDE) 解的形式存在；接着，我们使用具有自注意和交叉注意机制的 Transformer 架构，在零-shot 设置下预测 PDE 解，无需控制方程的知识；最后，我们在一维对流-扩散-反应方程上进行实验，证明即使使用近似先验数据，预训练依然稳健，对测试准确性影响甚微。这一发现为使用现实、低成本数据预训练 SFM 提供了可能，支持了 SFM 可以像 LLM 一样改进的猜想，尽管完全清理互联网上的海量数据几乎不可能。

> Large language models (LLMs), like ChatGPT, have shown that even trained with noisy prior data, they can generalize effectively to new tasks through in-context learning (ICL) and pre-training techniques. Motivated by this, we explore whether a similar approach can be applied to scientific foundation models (SFMs). Our methodology is structured as follows: (i) we collect low-cost physics-informed neural network (PINN)-based approximated prior data in the form of solutions to partial differential equations (PDEs) constructed through an arbitrary linear combination of mathematical dictionaries; (ii) we utilize Transformer architectures with self and cross-attention mechanisms to predict PDE solutions without knowledge of the governing equations in a zero-shot setting; (iii) we provide experimental evidence on the one-dimensional convection-diffusion-reaction equation, which demonstrate that pre-training remains robust even with approximated prior data, with only marginal impacts on test accuracy. Notably, this finding opens the path to pre-training SFMs with realistic, low-cost data instead of (or in conjunction with) numerical high-cost data. These results support the conjecture that SFMs can improve in a manner similar to LLMs, where fully cleaning the vast set of sentences crawled from the Internet is nearly impossible.

[Arxiv](https://arxiv.org/abs/2410.06442)