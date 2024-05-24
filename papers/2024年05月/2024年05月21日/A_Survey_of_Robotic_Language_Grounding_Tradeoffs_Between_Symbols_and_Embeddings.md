# 机器人语言基础研究综述：探讨符号与嵌入之间的取舍

发布时间：2024年05月21日

`Agent

这篇论文主要探讨了大型语言模型在机器人领域的应用，特别是在语言理解和机器人行为指导方面的研究。它分析了将语言映射到正式表示与高维向量空间两种方法的优缺点，并提出了未来研究的方向。这表明论文关注的是如何利用大型语言模型来增强机器人的语言理解和决策能力，因此属于Agent分类，即研究如何构建和优化能够理解和执行语言指令的智能代理。` `机器人技术`

> A Survey of Robotic Language Grounding: Tradeoffs Between Symbols and Embeddings

# 摘要

> 借助大型语言模型，机器人对语言的理解能力达到了前所未有的灵活性和高效性。本综述梳理了近期研究，将其置于两个极端之间：一方面是语言与人工定义的意义的正式表示之间的映射，另一方面则是语言与直接指导机器人低级策略的高维向量空间之间的映射。采用正式表示确保了语言意义的精确表达，简化了学习问题的复杂度，并构建了可解释性和安全性的框架。而将语言及感知数据嵌入高维空间的方法，虽避免了人工符号结构的限制，展现出更广泛的适用性，但同时也增加了数据和计算的需求。本文探讨了两种方法的优势与取舍，并展望了未来研究方向，旨在融合两者的优势，实现更优的解决方案。

> With large language models, robots can understand language more flexibly and more capable than ever before. This survey reviews recent literature and situates it into a spectrum with two poles: 1) mapping between language and some manually defined formal representation of meaning, and 2) mapping between language and high-dimensional vector spaces that translate directly to low-level robot policy. Using a formal representation allows the meaning of the language to be precisely represented, limits the size of the learning problem, and leads to a framework for interpretability and formal safety guarantees. Methods that embed language and perceptual data into high-dimensional spaces avoid this manually specified symbolic structure and thus have the potential to be more general when fed enough data but require more data and computing to train. We discuss the benefits and tradeoffs of each approach and finish by providing directions for future work that achieves the best of both worlds.

[Arxiv](https://arxiv.org/abs/2405.13245)