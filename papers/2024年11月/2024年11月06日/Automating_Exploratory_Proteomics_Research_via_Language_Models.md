# 通过语言模型实现探索性蛋白质组学研究的自动化

发布时间：2024年11月06日

`LLM应用` `蛋白质组学` `生物信息学`

> Automating Exploratory Proteomics Research via Language Models

# 摘要

> 随着人工智能的发展，它对科学的贡献正从模拟复杂问题发展到自动化整个研究过程并产生新的发现。实现这一进步既需要基于现实世界科学数据的专门通用模型，也需要反映人类科学方法的迭代、探索性框架。在本文中，我们介绍了 PROTEUS，这是一个从原始蛋白质组学数据进行科学发现的全自动系统。PROTEUS 使用大型语言模型（LLMs）进行分层规划，执行专门的生物信息学工具，并迭代优化分析工作流程以生成高质量的科学假设。该系统将蛋白质组学数据集作为输入，并在无人干预的情况下生成一整套研究目标、分析结果和新的生物学假设。我们在从各种生物样本（例如免疫细胞、肿瘤）和不同样本类型（单细胞和大量）收集的 12 个蛋白质组学数据集上对 PROTEUS 进行了评估，生成了 191 个科学假设。这些假设通过基于 5 个指标的自动 LLM 评分和人类专家的详细审查进行了评估。结果表明，PROTEUS 始终产生可靠、逻辑连贯的结果，与现有文献高度一致，同时还提出了新颖、可评估的假设。该系统灵活的架构有助于无缝集成各种分析工具，并适应不同的蛋白质组学数据类型。通过自动化复杂的蛋白质组学分析工作流程和假设生成，PROTEUS 有可能大大加快蛋白质组学研究中的科学发现速度，使研究人员能够有效地探索大规模数据集并发现生物学见解。

> With the development of artificial intelligence, its contribution to science is evolving from simulating a complex problem to automating entire research processes and producing novel discoveries. Achieving this advancement requires both specialized general models grounded in real-world scientific data and iterative, exploratory frameworks that mirror human scientific methodologies. In this paper, we present PROTEUS, a fully automated system for scientific discovery from raw proteomics data. PROTEUS uses large language models (LLMs) to perform hierarchical planning, execute specialized bioinformatics tools, and iteratively refine analysis workflows to generate high-quality scientific hypotheses. The system takes proteomics datasets as input and produces a comprehensive set of research objectives, analysis results, and novel biological hypotheses without human intervention. We evaluated PROTEUS on 12 proteomics datasets collected from various biological samples (e.g. immune cells, tumors) and different sample types (single-cell and bulk), generating 191 scientific hypotheses. These were assessed using both automatic LLM-based scoring on 5 metrics and detailed reviews from human experts. Results demonstrate that PROTEUS consistently produces reliable, logically coherent results that align well with existing literature while also proposing novel, evaluable hypotheses. The system's flexible architecture facilitates seamless integration of diverse analysis tools and adaptation to different proteomics data types. By automating complex proteomics analysis workflows and hypothesis generation, PROTEUS has the potential to considerably accelerate the pace of scientific discovery in proteomics research, enabling researchers to efficiently explore large-scale datasets and uncover biological insights.

[Arxiv](https://arxiv.org/abs/2411.03743)