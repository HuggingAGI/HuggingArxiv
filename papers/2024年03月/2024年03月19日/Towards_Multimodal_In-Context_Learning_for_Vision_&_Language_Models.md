# 致力于探索视觉与语言模型的多模态上下文学习方法，旨在提升模型在不同模态信息融合下的泛化和理解能力。

发布时间：2024年03月19日

`LLM应用` `视觉模型`

> Towards Multimodal In-Context Learning for Vision & Language Models

# 摘要

> 随着能深刻理解人类语言的大型语言模型（LLMs）的出现，研究人员已成功地让非语言模态的数据变得“易懂”，主要通过将其转化为一连串类似语言的嵌入标记输入到LLM中。然而，LLM的关键能力之一——上下文学习（ICL）尚未充分地迁移到新兴的视觉语言模型（VLMs），尤其是如何借助上下文图像+文本示例指导VLM完成特定下游任务或构建目标输出结构。在本研究中，我们深度剖析了当前顶尖VLMs在遵循ICL指令方面的局限性，发现其在这方面的表现并不理想。即便一些经历过大规模混合模态预训练，被设计成能融合图片与文本信息的模型，在接收到少量示例（ICL）演示时，也往往表现欠佳，这很可能是由于它们缺少针对ICL指令的针对性调优。为此，我们提出了一项简洁而效果显著的方案：在通用VLM对齐框架中融入ICL支持体系、方法及学习路径。通过实验、分析和优选有效数据组合，我们成功提升了VLMs在各类ICL基准上的性能，最高可达21.03%，平均提升11.3%，远超现有的最强VLM基线。同时，我们还引入了针对VLMs ICL能力评估的新基准，并探讨了它们相对于先前方法的优势所在。

> Inspired by the emergence of Large Language Models (LLMs) that can truly understand human language, significant progress has been made in aligning other, non-language, modalities to be `understandable' by an LLM, primarily via converting their samples into a sequence of embedded language-like tokens directly fed into the LLM (decoder) input stream. However, so far limited attention has been given to transferring (and evaluating) one of the core LLM capabilities to the emerging VLMs, namely the In-Context Learning (ICL) ability, or in other words to guide VLMs to desired target downstream tasks or output structure using in-context image+text demonstrations. In this work, we dive deeper into analyzing the capabilities of some of the state-of-the-art VLMs to follow ICL instructions, discovering them to be somewhat lacking. We discover that even models that underwent large-scale mixed modality pre-training and were implicitly guided to make use of interleaved image and text information (intended to consume helpful context from multiple images) under-perform when prompted with few-shot (ICL) demonstrations, likely due to their lack of `direct' ICL instruction tuning. To test this conjecture, we propose a simple, yet surprisingly effective, strategy of extending a common VLM alignment framework with ICL support, methodology, and curriculum. We explore, analyze, and provide insights into effective data mixes, leading up to a significant 21.03% (and 11.3% on average) ICL performance boost over the strongest VLM baselines and a variety of ICL benchmarks. We also contribute new benchmarks for ICL evaluation in VLMs and discuss their advantages over the prior art.

[Arxiv](https://arxiv.org/abs/2403.12736)