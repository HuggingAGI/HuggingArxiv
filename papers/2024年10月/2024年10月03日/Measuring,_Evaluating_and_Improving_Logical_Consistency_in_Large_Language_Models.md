# 探索、评估并提升大型语言模型中的逻辑一致性

发布时间：2024年10月03日

`LLM理论` `人工智能` `逻辑推理`

> Measuring, Evaluating and Improving Logical Consistency in Large Language Models

# 摘要

> 近期研究显示，大语言模型（LLM）在与人类偏好对齐方面取得了显著进展。然而，LLM 在决策时仍存在不一致和偏见。我们聚焦于研究 LLM 的逻辑一致性，以构建更可靠的系统。通过传递性、交换性和否定不变性三个基本代理，我们量化了逻辑一致性，并评估了其对整体鲁棒性的影响。此外，我们提出了一种数据增强技术，在不牺牲与人类偏好对齐的前提下，提升 LLM 的逻辑一致性。最后，我们发现逻辑一致性对基于 LLM 的逻辑依赖算法性能有显著影响。

> Recent research in Large Language Models (LLMs) has shown promising progress related to LLM alignment with human preferences. LLM-empowered decision-making systems are expected to be predictable, reliable and trustworthy, which implies being free from paradoxes or contradictions that could undermine their credibility and validity. However, LLMs still exhibit inconsistent and biased behaviour when making decisions or judgements. In this work, we focus on studying logical consistency of LLMs as a prerequisite for more reliable and trustworthy systems. Logical consistency ensures that decisions are based on a stable and coherent understanding of the problem, reducing the risk of erratic or contradictory outputs. We first propose a universal framework to quantify the logical consistency via three fundamental proxies: transitivity, commutativity and negation invariance. We then evaluate logical consistency, using the defined measures, of a wide range of LLMs, demonstrating that it can serve as a strong proxy for overall robustness. Additionally, we introduce a data refinement and augmentation technique that enhances the logical consistency of LLMs without sacrificing alignment to human preferences. It augments noisy and sparse pairwise-comparison annotations by estimating a partially or totally ordered preference rankings using rank aggregation methods. Finally, we show that logical consistency impacts the performance of LLM-based logic-dependent algorithms, where LLMs serve as logical operators.

[Arxiv](https://arxiv.org/abs/2410.02205)