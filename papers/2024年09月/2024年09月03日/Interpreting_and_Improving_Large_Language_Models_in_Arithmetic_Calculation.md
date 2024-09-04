# 探究与提升大型语言模型在算术运算中的解释性与性能

发布时间：2024年09月03日

`LLM理论` `人工智能`

> Interpreting and Improving Large Language Models in Arithmetic Calculation

# 摘要

> 大型语言模型（LLM）在众多领域展现出卓越潜力，尤其在处理复杂推理任务如数学计算方面。然而，即便是最基础的算术运算，LLM 的内在工作机制仍充满谜团，这使得确保其可靠性颇具挑战。本研究深入剖析了 LLM 进行计算的特定机制，发现其频繁依赖一小部分（不足 5%）的注意力头，这些头在计算过程中对操作数和运算符的聚焦至关重要。这些信息随后通过多层感知器（MLP）处理，逐步导向最终答案。有趣的是，这些关键的头/MLP 虽在特定数据集上识别，却展现出跨数据集和任务的可迁移性。基于此，我们探讨了针对性微调这些核心组件以提升 LLM 计算性能的可能性，并实证发现，这种精准调整不仅能显著增强数学能力，还不会影响其在非数学任务上的表现。本研究为揭示 LLM 在算术计算方面的深层能力奠定了基础，为未来探索更复杂数学任务铺平了道路。

> Large language models (LLMs) have demonstrated remarkable potential across numerous applications and have shown an emergent ability to tackle complex reasoning tasks, such as mathematical computations. However, even for the simplest arithmetic calculations, the intrinsic mechanisms behind LLMs remain mysterious, making it challenging to ensure reliability. In this work, we delve into uncovering a specific mechanism by which LLMs execute calculations. Through comprehensive experiments, we find that LLMs frequently involve a small fraction (< 5%) of attention heads, which play a pivotal role in focusing on operands and operators during calculation processes. Subsequently, the information from these operands is processed through multi-layer perceptrons (MLPs), progressively leading to the final solution. These pivotal heads/MLPs, though identified on a specific dataset, exhibit transferability across different datasets and even distinct tasks. This insight prompted us to investigate the potential benefits of selectively fine-tuning these essential heads/MLPs to boost the LLMs' computational performance. We empirically find that such precise tuning can yield notable enhancements on mathematical prowess, without compromising the performance on non-mathematical tasks. Our work serves as a preliminary exploration into the arithmetic calculation abilities inherent in LLMs, laying a solid foundation to reveal more intricate mathematical tasks.

[Arxiv](https://arxiv.org/abs/2409.01659)