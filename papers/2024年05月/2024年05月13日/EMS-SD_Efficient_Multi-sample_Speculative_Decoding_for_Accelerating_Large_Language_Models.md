# EMS-SD：加速大型语言模型的利器——高效多样本推测解码技术

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了大型语言模型（LLM）中的推测解码技术，特别是针对多样本推测解码的优化方法。它提出了一种新的方法来解决样本间令牌接受不一致的问题，这直接关系到LLM的推理速度和效率。因此，这篇论文的内容更偏向于LLM的理论研究，特别是关于解码策略的改进，而不是关于特定应用、代理（Agent）或检索增强生成（RAG）的研究。` `高性能计算`

> EMS-SD: Efficient Multi-sample Speculative Decoding for Accelerating Large Language Models

# 摘要

> 推测解码技术在提升大型语言模型推理速度方面扮演着关键角色。尽管研究者们致力于提高预测效率，但多样本推测解码因验证阶段批次内令牌接受数量的差异而未受重视。传统方法通过填充令牌来维持样本间新令牌数量的一致性，但这增加了计算和内存访问的负担，降低了加速比。我们提出了一种创新方法，无需额外开销即可解决不同样本间令牌接受不一致的问题，并能处理不同样本预测令牌不一致的情况，无需填充令牌。实验充分验证了我们方法的有效性，相关代码已公开于 https://github.com/niyunsheng/EMS-SD。

> Speculative decoding emerges as a pivotal technique for enhancing the inference speed of Large Language Models (LLMs). Despite recent research aiming to improve prediction efficiency, multi-sample speculative decoding has been overlooked due to varying numbers of accepted tokens within a batch in the verification phase. Vanilla method adds padding tokens in order to ensure that the number of new tokens remains consistent across samples. However, this increases the computational and memory access overhead, thereby reducing the speedup ratio. We propose a novel method that can resolve the issue of inconsistent tokens accepted by different samples without necessitating an increase in memory or computing overhead. Furthermore, our proposed method can handle the situation where the prediction tokens of different samples are inconsistent without the need to add padding tokens. Sufficient experiments demonstrate the efficacy of our method. Our code is available at https://github.com/niyunsheng/EMS-SD.

[Arxiv](https://arxiv.org/abs/2405.07542)