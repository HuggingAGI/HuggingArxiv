# ExpLLM：探索面部表情识别中的思维链方法

发布时间：2024年09月04日

`LLM应用` `多媒体` `人工智能`

> ExpLLM: Towards Chain of Thought for Facial Expression Recognition

# 摘要

> 面部表情识别（FER）在多媒体领域至关重要，但深入分析表情成因对准确识别至关重要。现有基于面部动作单元（AUs）的方法虽提供AU信息，却忽视了AUs间的互动与关系。为此，我们提出ExpLLM方法，借助大型语言模型生成精准的面部表情识别思维链（CoT）。CoT机制从关键观察、整体情感解释和结论三方面设计，详细描述AU特征、情感主导及相互关系，最终得出表情标签。我们还开发了Exp-CoT引擎，用于构建表情CoT并生成训练数据。实验证明，ExpLLM在RAF-DB和AffectNet数据集上超越现有顶尖FER方法，尤其在微表情识别上，显著优于GPT-4o。

> Facial expression recognition (FER) is a critical task in multimedia with significant implications across various domains. However, analyzing the causes of facial expressions is essential for accurately recognizing them. Current approaches, such as those based on facial action units (AUs), typically provide AU names and intensities but lack insight into the interactions and relationships between AUs and the overall expression. In this paper, we propose a novel method called ExpLLM, which leverages large language models to generate an accurate chain of thought (CoT) for facial expression recognition. Specifically, we have designed the CoT mechanism from three key perspectives: key observations, overall emotional interpretation, and conclusion. The key observations describe the AU's name, intensity, and associated emotions. The overall emotional interpretation provides an analysis based on multiple AUs and their interactions, identifying the dominant emotions and their relationships. Finally, the conclusion presents the final expression label derived from the preceding analysis. Furthermore, we also introduce the Exp-CoT Engine, designed to construct this expression CoT and generate instruction-description data for training our ExpLLM. Extensive experiments on the RAF-DB and AffectNet datasets demonstrate that ExpLLM outperforms current state-of-the-art FER methods. ExpLLM also surpasses the latest GPT-4o in expression CoT generation, particularly in recognizing micro-expressions where GPT-4o frequently fails.

[Arxiv](https://arxiv.org/abs/2409.02828)