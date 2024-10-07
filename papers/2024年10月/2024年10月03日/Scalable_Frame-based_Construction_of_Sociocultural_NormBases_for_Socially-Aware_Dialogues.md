# 构建可扩展的社会文化规范库，助力社会意识对话

发布时间：2024年10月03日

`LLM应用` `社交互动` `机器学习`

> Scalable Frame-based Construction of Sociocultural NormBases for Socially-Aware Dialogues

# 摘要

> 社会文化规范在社交互动中指导个人行为，强调尊重、合作和适当行为，有助于对话信息检索、上下文信息检索和增强的机器学习任务。我们提出一种可扩展方法，利用大型语言模型构建社会文化规范库，用于社会意识对话。我们构建了全面且公开的中文社会文化规范库，通过丰富的上下文框架约束生成过程，减少幻觉，提取高质量的自然语言规范陈述。由于真实对话标注不易得，我们使用合成数据。实证结果显示，合成数据得出的规范质量与真实对话相当，且带框架标注的真实数据提取的规范质量更高。我们还展示了这些规范在检索增强生成模型中的有效性，用于推理多个对话任务。

> Sociocultural norms serve as guiding principles for personal conduct in social interactions, emphasizing respect, cooperation, and appropriate behavior, which is able to benefit tasks including conversational information retrieval, contextual information retrieval and retrieval-enhanced machine learning. We propose a scalable approach for constructing a Sociocultural Norm (SCN) Base using Large Language Models (LLMs) for socially aware dialogues. We construct a comprehensive and publicly accessible Chinese Sociocultural NormBase. Our approach utilizes socially aware dialogues, enriched with contextual frames, as the primary data source to constrain the generating process and reduce the hallucinations. This enables extracting of high-quality and nuanced natural-language norm statements, leveraging the pragmatic implications of utterances with respect to the situation. As real dialogue annotated with gold frames are not readily available, we propose using synthetic data. Our empirical results show: (i) the quality of the SCNs derived from synthetic data is comparable to that from real dialogues annotated with gold frames, and (ii) the quality of the SCNs extracted from real data, annotated with either silver (predicted) or gold frames, surpasses that without the frame annotations. We further show the effectiveness of the extracted SCNs in a RAG-based (Retrieval-Augmented Generation) model to reason about multiple downstream dialogue tasks.

[Arxiv](https://arxiv.org/abs/2410.03049)