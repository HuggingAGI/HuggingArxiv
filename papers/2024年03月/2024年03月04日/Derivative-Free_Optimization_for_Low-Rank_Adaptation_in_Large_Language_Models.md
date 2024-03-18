# [针对大型语言模型中的低秩适应问题，本研究探讨了无需依赖梯度信息的优化方法。](https://arxiv.org/abs/2403.01754)

发布时间：2024年03月04日

`LLM应用`

> Derivative-Free Optimization for Low-Rank Adaptation in Large Language Models

> 类似LoRA这样的参数高效微调技术只需调整少量参数即可媲美全模型微调的效果，但其过程仍需大量的计算资源进行梯度计算及全模型反向传播。近期研究着重于采用无梯度优化方法，以规避梯度计算，并在小样本场景下展现更强的稳健性。本篇论文将低秩模块插入到模型各个自注意力层之前，并交替运用两种无梯度优化策略对每一层的低秩模块进行优化。大量实验证明，相比现有基于梯度的参数高效微调方法以及无梯度优化方法，在处理各类任务和语言模型时，我们提出的方案在小样本设定下不仅取得了明显的性能提升，而且在内存占用和收敛速度上表现出了清晰的优势。

> Parameter-efficient tuning methods such as LoRA could achieve comparable performance to model tuning by tuning a small portion of the parameters. However, substantial computational resources are still required, as this process involves calculating gradients and performing back-propagation throughout the model. Much effort has recently been devoted to utilizing the derivative-free optimization method to eschew the computation of gradients and showcase an augmented level of robustness in few-shot settings. In this paper, we prepend the low-rank modules into each self-attention layer of the model and employ two derivative-free optimization methods to optimize these low-rank modules at each layer alternately. Extensive results on various tasks and language models demonstrate that our proposed method achieves substantial improvement and exhibits clear advantages in memory usage and convergence speed compared to existing gradient-based parameter-efficient tuning and derivative-free optimization methods in few-shot settings.

[Arxiv](https://arxiv.org/abs/2403.01754)