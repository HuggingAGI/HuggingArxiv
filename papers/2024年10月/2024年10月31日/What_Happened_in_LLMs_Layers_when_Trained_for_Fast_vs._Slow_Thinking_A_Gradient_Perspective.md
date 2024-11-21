# 从梯度视角探讨在为快速思考和慢速思考进行训练时，LLMs 层中的情况

发布时间：2024年10月31日

`LLM理论` `语言模型` `机器学习`

> What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective

# 摘要

> LLM 的后训练中究竟是什么造成了差异？我们从梯度的视角，探究大型语言模型（LLMs）中不同层的训练模式，在采用不同响应和初始模型进行训练时。鉴于当下在诸如思维链（CoT）和过程奖励等推理路径上训练 LLM 颇为流行，我们尤为关注快思考和慢思考对逐层梯度的影响。在我们的研究中，无 CoT 的快思考所产生的梯度比慢思考（详细的 CoT）更大，各层之间的梯度差异也更显著，这表明慢思考带来了学习的稳定性。而且，预训练的 LLM 受快思考不稳定性的影响小于指令调整的 LLM。此外，我们还研究了在运用慢思考与快思考路径训练不同 LLM 时，梯度模式能否反映响应的正确性。结果显示，慢思考的梯度能够区分正确和不相关的推理路径。作为对比，我们在非推理知识学习任务上开展了类似的梯度分析，然而，在这类任务中，单纯增加响应长度并不会引发慢思考的类似行为。我们的研究深化了对 LLM 训练的基本认识，为其效率和稳定性带来了全新的见解，为构建通用的 System-2 代理奠定了基础。我们的代码、数据和梯度统计信息可在以下网址获取：https://github.com/MingLiiii/Layer_Gradient。

> What makes a difference in the post-training of LLMs? We investigate the training patterns of different layers in large language models (LLMs), through the lens of gradient, when training with different responses and initial models. We are specifically interested in how fast vs. slow thinking affects the layer-wise gradients, given the recent popularity of training LLMs on reasoning paths such as chain-of-thoughts (CoT) and process rewards. In our study, fast thinking without CoT leads to larger gradients and larger differences of gradients across layers than slow thinking (Detailed CoT), indicating the learning stability brought by the latter. Moreover, pre-trained LLMs are less affected by the instability of fast thinking than instruction-tuned LLMs. Additionally, we study whether the gradient patterns can reflect the correctness of responses when training different LLMs using slow vs. fast thinking paths. The results show that the gradients of slow thinking can distinguish correct and irrelevant reasoning paths. As a comparison, we conduct similar gradient analyses on non-reasoning knowledge learning tasks, on which, however, trivially increasing the response length does not lead to similar behaviors of slow thinking. Our study strengthens fundamental understandings of LLM training and sheds novel insights on its efficiency and stability, which pave the way towards building a generalizable System-2 agent. Our code, data, and gradient statistics can be found in: https://github.com/MingLiiii/Layer_Gradient.

[Arxiv](https://arxiv.org/abs/2410.23743)