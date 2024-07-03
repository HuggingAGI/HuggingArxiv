# 你的大型语言模型是真才实学，还是仅仅在选择题上作弊？

发布时间：2024年07月02日

`LLM应用` `人工智能`

> Is Your Large Language Model Knowledgeable or a Choices-Only Cheater?

# 摘要

> 最新研究发现，大型语言模型 (LLMs) 能仅凭选项解答多项选择题，但这会否导致其在 MCQA 排行榜上的名次主要取决于仅选项的能力？为探究此问题，我们运用图挖掘技术，从现有 MCQA 数据集中提取对比集，以检测 LLMs 是否过度依赖仅选项的捷径。与以往依赖人工标注或可能偏差的模型生成数据不同，我们在 UnifiedQA 上构建了一个包含 820 个问题的对比集，该数据集涵盖六个高仅选项准确性的常识推理数据集。经过验证，我们测试了 12 个 LLMs，结果显示这些模型在同时提供问题和选项时并未过度依赖仅选项捷径。因此，尽管 MCQA 对高仅选项准确性敏感，我们认为 LLMs 在 MCQA 排行榜上的高排名并非仅因它们能利用仅选项的捷径。

> Recent work shows that large language models (LLMs) can answer multiple-choice questions using only the choices, but does this mean that MCQA leaderboard rankings of LLMs are largely influenced by abilities in choices-only settings? To answer this, we use a contrast set that probes if LLMs over-rely on choices-only shortcuts in MCQA. While previous works build contrast sets via expensive human annotations or model-generated data which can be biased, we employ graph mining to extract contrast sets from existing MCQA datasets. We use our method on UnifiedQA, a group of six commonsense reasoning datasets with high choices-only accuracy, to build an 820-question contrast set. After validating our contrast set, we test 12 LLMs, finding that these models do not exhibit reliance on choice-only shortcuts when given both the question and choices. Thus, despite the susceptibility~of MCQA to high choices-only accuracy, we argue that LLMs are not obtaining high ranks on MCQA leaderboards just due to their ability to exploit choices-only shortcuts.

[Arxiv](https://arxiv.org/abs/2407.01992)