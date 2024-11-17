# SpecHub：为多稿推测解码提供可证明的加速

发布时间：2024年11月07日

`LLM应用` `模型推理`

> SpecHub: Provable Acceleration to Multi-Draft Speculative Decoding

# 摘要

> 大型语言模型（LLMs）对于推动自然语言处理（NLP）任务的发展至关重要，但其顺序生成令牌的方式限制了推理速度。多稿推测解码（MDSD）提供了颇具前景的解决方案，即利用较小的草案模型生成多个令牌序列，再由目标LLM并行验证。然而，当下的启发式方法，像递归拒绝采样（RRS），在后续草案中的接受率较低，限制了使用多份草案的优势。同时，具有成员成本的最优传输（OTM）理论上能提高接受率，但其计算成本过高，不适用于实时应用。我们推出了SpecHub，这是一种新颖且高效的MDSD采样验证方法，仅以线性计算开销就提升了接受率。通过将OTM问题简化为紧凑的线性规划模型，SpecHub大幅降低了计算复杂度。它还借助稀疏联合分布加快采样，将计算聚焦于高概率令牌序列。在大量实验中，Spechub每步比RRS和无替换的RRS始终多生成0.05 - 0.27和0.02 - 0.16个令牌。我们在url{https://github.com/MasterGodzilla/Speculative_decoding_OT}附上了代码。

> Large Language Models (LLMs) have become essential in advancing natural language processing (NLP) tasks, but their sequential token generation limits inference speed. Multi-Draft Speculative Decoding (MDSD) offers a promising solution by using a smaller draft model to generate multiple token sequences, which the target LLM verifies in parallel. However, current heuristic approaches, such as Recursive Rejection Sampling (RRS), suffer from low acceptance rates in subsequent drafts, limiting the advantages of using multiple drafts. Meanwhile, Optimal Transport with Membership Cost (OTM) can theoretically improve acceptance rates, but its computational cost is too high for real-time use. We present SpecHub, a novel, efficient sampling-verification method for MDSD that improves acceptance rates with only linear computational overhead. By simplifying the OTM problem into a compact Linear Programming model, SpecHub significantly reduces computational complexity. It further accelerates sampling by leveraging a sparse joint distribution, focusing computation on high-probability token sequences. In extensive experiments, Spechub consistently generates 0.05-0.27 and 0.02-0.16 more tokens per step than RRS and RRS without replacement. We attach our code at url{https://github.com/MasterGodzilla/Speculative_decoding_OT}.

[Arxiv](https://arxiv.org/abs/2411.05289)