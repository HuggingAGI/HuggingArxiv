# 应对领域转移的经典策略：利用知识先验优化医学图像分析

发布时间：2024年05月23日

`LLM应用

理由：这篇论文主要探讨了如何通过知识增强瓶颈（KnoBo）模型，利用自然语言表述的明确医学知识先验来提高深度网络在医学图像分析中的泛化能力和领域适应性。这种方法涉及利用检索增强的语言模型来构建概念空间，并自动训练以识别临床相关因素。因此，这项工作属于大型语言模型（LLM）的应用范畴，特别是在医学图像分析领域的应用。` `图像分析`

> A Textbook Remedy for Domain Shifts: Knowledge Priors for Medical Image Analysis

# 摘要

> 深度网络虽在自然图像分析上大放异彩，但在医学扫描领域却常遇意外挫折。我们深入探讨了这一难题，特别关注模型对数据来源（如不同医院）或人口统计变量（如性别、种族）引起的领域变化的敏感性，以胸部X光和皮肤病变图像为例。实验表明，现有视觉模型在面对这些变化时，缺乏足够的架构先验以确保泛化能力。受医学教育的启发，我们提出将深度网络赋予基于自然语言表述的明确医学知识先验。为此，我们开发了知识增强瓶颈（KnoBo），一种概念瓶颈模型，它通过医学教科书或PubMed中的知识先验，约束模型仅使用临床相关因素进行推理。KnoBo利用检索增强的语言模型构建合适的概念空间，并自动训练以识别这些概念。我们在20个数据集上广泛测试了不同知识资源和架构在领域变化中的表现。综合评估显示，在两种成像模式下，KnoBo在混淆数据集上的表现平均超越微调模型32.4%。最终评估表明，PubMed是提升医学模型领域适应性的有力资源，无论在信息多样性还是预测准确性上都表现卓越。

> While deep networks have achieved broad success in analyzing natural images, when applied to medical scans, they often fail in unexcepted situations. We investigate this challenge and focus on model sensitivity to domain shifts, such as data sampled from different hospitals or data confounded by demographic variables such as sex, race, etc, in the context of chest X-rays and skin lesion images. A key finding we show empirically is that existing visual backbones lack an appropriate prior from the architecture for reliable generalization in these settings. Taking inspiration from medical training, we propose giving deep networks a prior grounded in explicit medical knowledge communicated in natural language. To this end, we introduce Knowledge-enhanced Bottlenecks (KnoBo), a class of concept bottleneck models that incorporates knowledge priors that constrain it to reason with clinically relevant factors found in medical textbooks or PubMed. KnoBo uses retrieval-augmented language models to design an appropriate concept space paired with an automatic training procedure for recognizing the concept. We evaluate different resources of knowledge and recognition architectures on a broad range of domain shifts across 20 datasets. In our comprehensive evaluation with two imaging modalities, KnoBo outperforms fine-tuned models on confounded datasets by 32.4% on average. Finally, evaluations reveal that PubMed is a promising resource for making medical models less sensitive to domain shift, outperforming other resources on both diversity of information and final prediction performance.

[Arxiv](https://arxiv.org/abs/2405.14839)