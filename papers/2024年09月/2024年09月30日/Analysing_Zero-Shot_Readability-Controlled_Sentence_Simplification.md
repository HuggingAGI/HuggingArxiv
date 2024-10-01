# 探究零-shot 可读性调控下的句子简化

发布时间：2024年09月30日

`LLM应用`

> Analysing Zero-Shot Readability-Controlled Sentence Simplification

# 摘要

> 可读性控制的文本简化 (RCTS) 旨在降低文本可读性，同时保留其含义。然而，RCTS 模型依赖的平行语料库稀缺且难以整理，尤其是在句子级别。为减少对平行数据的依赖，我们尝试使用指令调整的大型语言模型进行零-shot RCTS。通过自动和手动评估，我们发现：(1) 不同上下文信息对生成所需可读性句子的影响，以及 (2) 在可读性和含义保留之间的权衡。结果表明，所有测试模型在简化句子（尤其是最低水平）时都遇到困难，主要因模型局限和源句子特征阻碍了有效改写。此外，实验还揭示了现有评估指标的不足，强调了开发专门针对 RCTS 的自动评估指标的必要性。

> Readability-controlled text simplification (RCTS) rewrites texts to lower readability levels while preserving their meaning. RCTS models often depend on parallel corpora with readability annotations on both source and target sides. Such datasets are scarce and difficult to curate, especially at the sentence level. To reduce reliance on parallel data, we explore using instruction-tuned large language models for zero-shot RCTS. Through automatic and manual evaluations, we examine: (1) how different types of contextual information affect a model's ability to generate sentences with the desired readability, and (2) the trade-off between achieving target readability and preserving meaning. Results show that all tested models struggle to simplify sentences (especially to the lowest levels) due to models' limitations and characteristics of the source sentences that impede adequate rewriting. Our experiments also highlight the need for better automatic evaluation metrics tailored to RCTS, as standard ones often misinterpret common simplification operations, and inaccurately assess readability and meaning preservation.

[Arxiv](https://arxiv.org/abs/2409.20246)