# VTechAGP：一个从学术到大众的文本释义数据集和基准模型

发布时间：2024年11月07日

`LLM应用` `文本释义`

> VTechAGP: An Academic-to-General-Audience Text Paraphrase Dataset and Benchmark Models

# 摘要

> 现有的文本简化或释义数据集主要关注一般领域中的句子级文本生成。这些数据集通常在开发时未使用领域知识。在本文中，我们发布了一个新的数据集 VTechAGP，这是第一个面向学术到普通受众的文本释义数据集，由来自 8 所学院超过 25 年创作的 4,938 个文档级的论文和学位论文的学术和普通受众摘要对组成。我们还提出了一种新颖的动态软提示生成语言模型 DSPT5。在训练时，我们利用对比生成损失函数来学习动态提示中的关键词向量。在推理时，我们在语义和结构层面采用众包采样解码策略来进一步选择最佳输出候选。我们从多个角度评估了 DSPT5 和各种最先进的大型语言模型（LLM）。结果表明，最先进的 LLM 未能提供令人满意的结果，而轻量级的 DSPT5 可以取得有竞争力的结果。据我们所知，我们是第一个为学术到普通受众的文本释义数据集构建基准数据集和解决方案的。

> Existing text simplification or paraphrase datasets mainly focus on sentence-level text generation in a general domain. These datasets are typically developed without using domain knowledge. In this paper, we release a novel dataset, VTechAGP, which is the first academic-to-general-audience text paraphrase dataset consisting of 4,938 document-level these and dissertation academic and general-audience abstract pairs from 8 colleges authored over 25 years. We also propose a novel dynamic soft prompt generative language model, DSPT5. For training, we leverage a contrastive-generative loss function to learn the keyword vectors in the dynamic prompt. For inference, we adopt a crowd-sampling decoding strategy at both semantic and structural levels to further select the best output candidate. We evaluate DSPT5 and various state-of-the-art large language models (LLMs) from multiple perspectives. Results demonstrate that the SOTA LLMs does not provide satisfactory outcomes, while the lightweight DSPT5 can achieve competitive results. To the best of our knowledge, we are the first to build a benchmark dataset and solutions for academic-to-general-audience text paraphrase dataset.

[Arxiv](https://arxiv.org/abs/2411.04825)