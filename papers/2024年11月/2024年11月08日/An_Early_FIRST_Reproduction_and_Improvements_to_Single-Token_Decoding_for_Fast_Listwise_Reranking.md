# 早期的首次复制以及对用于快速列表重排序的单令牌解码的改进

发布时间：2024年11月08日

`LLM应用` `信息检索` `重排序`

> An Early FIRST Reproduction and Improvements to Single-Token Decoding for Fast Listwise Reranking

# 摘要

> 最近的进展表明，大型语言模型（LLMs）作为列表重排序器表现出色，但它们的高计算需求仍然是广泛采用的障碍。此外，传统的语言建模（LM）目标不太适合重排序任务。FIRST 是一种新颖的方法，通过整合排序学习目标和仅利用第一个生成的标记的对数几率来应对这些挑战，从而与传统的 LLM 重排序器相比，显著降低了推理延迟。在这项研究中，我们将 FIRST 的评估扩展到 TREC 深度学习数据集（DL19-22），验证了其在不同领域的稳健性。我们研究了不同的第一阶段检索器对 FIRST 重排序器的影响，观察到收益递减和与传统 LLM 重排序器一致的模式。通过将 FIRST 目标应用于更广泛的骨干模型，我们实现了超越原始实现的有效性。我们的实验证实，使用单标记对数几率的快速重排序不会损害域外重排序质量。为了更好地量化原始研究中的计算节省，我们测量并比较延迟，发现在各种模型和基准中获得了 21％-42％的增益。此外，虽然 LM 训练隐式地改进了零样本单标记重排序，但我们的实验也提出了关于 LM 预训练是否可能阻碍随后使用 FIRST 目标进行微调的问题。这些发现为未来应用中更高效和有效的列表重排序铺平了道路。

> Recent advances have demonstrated that large language models (LLMs) excel as listwise rerankers, but their high computational demands remain a barrier to widespread adoption. Further, the traditional language modeling (LM) objective is not ideally suited for reranking tasks. FIRST is a novel approach that addresses these challenges by integrating a learning-to-rank objective and leveraging the logits of only the first generated token, thereby significantly reducing inference latency compared to traditional LLM rerankers. In this study, we extend the evaluation of FIRST to the TREC Deep Learning datasets (DL19-22), validating its robustness across diverse domains. We investigate the influence of different first-stage retrievers on FIRST rerankers, observing diminishing returns and patterns consistent with traditional LLM rerankers. Through applying the FIRST objective to a broader range of backbone models, we achieve effectiveness surpassing the original implementation. Our experiments confirm that fast reranking with single-token logits does not compromise out-of-domain reranking quality. To better quantify the computational savings in the original study, we measure and compare latency to find a 21%-42% gain across various models and benchmarks. Moreover, while LM training implicitly improves zero-shot single-token reranking, our experiments also raise questions about whether LM pre-training may hinder subsequent fine-tuning with the FIRST objective. These findings pave the way for more efficient and effective listwise reranking in future applications.

[Arxiv](https://arxiv.org/abs/2411.05508)