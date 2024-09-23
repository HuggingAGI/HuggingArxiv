# 状态空间模型、涌现性与遍历性：稳定预测究竟需要多少参数？

发布时间：2024年09月20日

`LLM理论` `人工智能` `机器学习`

> State space models, emergence, and ergodicity: How many parameters are needed for stable predictions?

# 摘要

> 执行特定任务需要多少参数？研究表明，当大型语言模型的参数达到一定规模时，通过自监督学习预训练的模型会展现出多步推理等新能力。我们尝试在简单理论模型中验证这一现象。结果显示，学习线性动力系统时，确实存在一个参数临界点，低于此点，模型无法在长序列中保持低误差。这意味着，处理长程相关任务时，模型需达到一定参数规模，类似于能力“涌现”。此外，我们还探讨了参数设置对学习效果的影响，发现对于不完全观察的随机游走问题，线性滤波器的长度必须超过特定阈值，才能有效学习。

> How many parameters are required for a model to execute a given task? It has been argued that large language models, pre-trained via self-supervised learning, exhibit emergent capabilities such as multi-step reasoning as their number of parameters reach a critical scale. In the present work, we explore whether this phenomenon can analogously be replicated in a simple theoretical model. We show that the problem of learning linear dynamical systems -- a simple instance of self-supervised learning -- exhibits a corresponding phase transition. Namely, for every non-ergodic linear system there exists a critical threshold such that a learner using fewer parameters than said threshold cannot achieve bounded error for large sequence lengths. Put differently, in our model we find that tasks exhibiting substantial long-range correlation require a certain critical number of parameters -- a phenomenon akin to emergence. We also investigate the role of the learner's parametrization and consider a simple version of a linear dynamical system with hidden state -- an imperfectly observed random walk in $\mathbb{R}$. For this situation, we show that there exists no learner using a linear filter which can succesfully learn the random walk unless the filter length exceeds a certain threshold depending on the effective memory length and horizon of the problem.

[Arxiv](https://arxiv.org/abs/2409.13421)