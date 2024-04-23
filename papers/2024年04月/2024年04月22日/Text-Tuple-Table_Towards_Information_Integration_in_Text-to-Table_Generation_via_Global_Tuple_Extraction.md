# Text-Tuple-Table：探索全局元组抽取在文本到表格生成中的信息整合之道

发布时间：2024年04月22日

`LLM应用` `文本摘要` `数据挖掘`

> Text-Tuple-Table: Towards Information Integration in Text-to-Table Generation via Global Tuple Extraction

# 摘要

> 近期，随着大型语言模型（LLMs）的兴起及其在文本摘要和文本挖掘等下游任务中的潜在优势，将繁复的文本信息精炼为简洁、有序的表格成为了研究热点。传统方法通常仅复制文本内容来创建表格，这限制了其在更广泛场景中的应用能力。真实世界的文本到表格转换任务要求具备信息抽取、推理和整合的能力，但目前这一领域缺乏相应的数据集和方法论支持。本文提出了LiveSum，一个新颖的基准数据集，旨在生成基于实时解说文本的竞赛摘要表。我们对当前顶级的LLMs在这一任务上的表现进行了评估，包括微调和零样本两种设置，并提出了一个创新的$T^3$（文本-元组-表格）流程以提升性能。广泛的实验结果显示，即便是经过微调的LLMs在处理这一任务时仍面临挑战，而我们的方法能够在无需显式训练的情况下显著提升性能。进一步分析表明，我们的方法具备强大的泛化能力，在多个文本到表格的数据集上超越了现有技术。相关代码和数据集已在 https://github.com/HKUST-KnowComp/LiveSum-TTT 上发布。

> The task of condensing large chunks of textual information into concise and structured tables has gained attention recently due to the emergence of Large Language Models (LLMs) and their potential benefit for downstream tasks, such as text summarization and text mining. Previous approaches often generate tables that directly replicate information from the text, limiting their applicability in broader contexts, as text-to-table generation in real-life scenarios necessitates information extraction, reasoning, and integration. However, there is a lack of both datasets and methodologies towards this task. In this paper, we introduce LiveSum, a new benchmark dataset created for generating summary tables of competitions based on real-time commentary texts. We evaluate the performances of state-of-the-art LLMs on this task in both fine-tuning and zero-shot settings, and additionally propose a novel pipeline called $T^3$(Text-Tuple-Table) to improve their performances. Extensive experimental results demonstrate that LLMs still struggle with this task even after fine-tuning, while our approach can offer substantial performance gains without explicit training. Further analyses demonstrate that our method exhibits strong generalization abilities, surpassing previous approaches on several other text-to-table datasets. Our code and data can be found at https://github.com/HKUST-KnowComp/LiveSum-TTT.

[Arxiv](https://arxiv.org/abs/2404.14215)