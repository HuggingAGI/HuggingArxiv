# 探讨检索增强与参数高效微调在保护隐私前提下，如何个性化大型语言模型。

发布时间：2024年09月14日

`LLM应用` `隐私保护` `人工智能`

> Comparing Retrieval-Augmentation and Parameter-Efficient Fine-Tuning for Privacy-Preserving Personalization of Large Language Models

# 摘要

> 个性化 LLM 的隐私保护方法研究尚浅。主流观点有两种：一是通过检索用户信息增强输入提示，生成个性化输出（RAG 方法）；二是针对每位用户进行参数高效微调，兼顾效率与空间（PEFT 方法）。本文首次系统对比了这两种方法在多样数据集上的表现。结果显示，RAG 和 PEFT 方法分别比非个性化 LLM 提升 14.92% 和 1.07%。结合两者，提升可达 15.98%。此外，用户数据越多，PEFT 效果越好，表明 RAG 更适合数据有限的新用户。

> Privacy-preserving methods for personalizing large language models (LLMs) are relatively under-explored. There are two schools of thought on this topic: (1) generating personalized outputs by personalizing the input prompt through retrieval augmentation from the user's personal information (RAG-based methods), and (2) parameter-efficient fine-tuning of LLMs per user that considers efficiency and space limitations (PEFT-based methods). This paper presents the first systematic comparison between two approaches on a wide range of personalization tasks using seven diverse datasets. Our results indicate that RAG-based and PEFT-based personalization methods on average yield 14.92% and 1.07% improvements over the non-personalized LLM, respectively. We find that combining RAG with PEFT elevates these improvements to 15.98%. Additionally, we identify a positive correlation between the amount of user data and PEFT's effectiveness, indicating that RAG is a better choice for cold-start users (i.e., user's with limited personal data).

[Arxiv](https://arxiv.org/abs/2409.09510)