# SFTMix：借助 Mixup 配方，提升语言模型的指令调优效果

发布时间：2024年10月07日

`LLM理论`

> SFTMix: Elevating Language Model Instruction Tuning with Mixup Recipe

# 摘要

> 为了在交互任务中引导大型语言模型 (LLM) 实现预期行为，指令调优阶段通常通过下一个标记预测 (NTP) 损失在指令-响应对上训练 LLM。以往提升指令调优性能的研究多强调高质量监督微调 (SFT) 数据集的必要性，这通常涉及昂贵的专有 LLM 数据过滤或人工注释的劳动密集型数据生成。然而，这些方法未能充分利用数据集的内在特性，导致高计算和劳动力成本，限制了可扩展性和性能提升。本文提出 SFTMix，一种无需精心策划数据集即可超越传统 NTP 范式的新方法。观察到 LLM 在语义空间中置信度不均，我们认为不同置信度的示例在指令调优过程中应扮演不同角色。基于此，SFTMix 利用训练动态识别不同置信度示例，并应用基于 Mixup 的正则化缓解对高置信度示例的过拟合，同时增强对低置信度示例的学习。这种方法使 SFTMix 在广泛的指令跟随和医疗领域 SFT 任务中显著优于 NTP，展示了其对多样 LLM 和任意规模数据集的适应性和可扩展性。全面的消融研究进一步验证了 SFTMix 设计的稳健性，凸显了其在更广泛 NLP 应用中跨不同 LLM 和数据集一致提升性能的多功能性。

> To induce desired behaviors in large language models (LLMs) for interaction-driven tasks, the instruction-tuning stage typically trains LLMs on instruction-response pairs using the next-token prediction (NTP) loss. Previous work aiming to improve instruction-tuning performance often emphasizes the need for higher-quality supervised fine-tuning (SFT) datasets, which typically involves expensive data filtering with proprietary LLMs or labor-intensive data generation by human annotators. However, these approaches do not fully leverage the datasets' intrinsic properties, resulting in high computational and labor costs, thereby limiting scalability and performance gains. In this paper, we propose SFTMix, a novel recipe that elevates instruction-tuning performance beyond the conventional NTP paradigm, without the need for well-curated datasets. Observing that LLMs exhibit uneven confidence across the semantic representation space, we argue that examples with different confidence levels should play distinct roles during the instruction-tuning process. Based on this insight, SFTMix leverages training dynamics to identify examples with varying confidence levels, then applies a Mixup-based regularization to mitigate overfitting on confident examples while propagating supervision signals to improve learning on relatively unconfident ones. This approach enables SFTMix to significantly outperform NTP across a wide range of instruction-following and healthcare domain-specific SFT tasks, demonstrating its adaptability to diverse LLM families and scalability to datasets of any size. Comprehensive ablation studies further verify the robustness of SFTMix's design choices, underscoring its versatility in consistently enhancing performance across different LLMs and datasets in broader natural language processing applications.

[Arxiv](https://arxiv.org/abs/2410.05248)