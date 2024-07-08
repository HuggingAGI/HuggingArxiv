# EventChat：一款由大型语言模型驱动，专为中小企业背景下探索休闲活动而设计的对话推荐系统，其核心在于实现与用户为中心的评估。

发布时间：2024年07月05日

`LLM应用` `中小企业` `电子商务`

> EventChat: Implementation and user-centric evaluation of a large language model-driven conversational recommender system for exploring leisure events in an SME context

# 摘要

> 大型语言模型（LLM）在对话推荐系统（CRS）的战略潜力方面取得了显著进展。然而，当前研究主要聚焦于技术实施，而非终端用户评估或企业战略影响，尤其是对构成全球经济基石的中小型企业（SME）。本文详细阐述了LLM驱动的CRS在SME环境中的设计及其现场表现，结合客观系统指标与主观用户评价。同时，我们提出了一种简化的修订版ResQue模型，以促进这一快速发展领域的可复制性。研究显示，尽管用户体验良好（推荐准确率达85.5%），但延迟、成本和质量问题仍制约着商业可行性。例如，每次交互成本中位数为$0.04，延迟达5.7秒，凸显了成本效益与响应时间的重要性。此外，依赖基于提示的学习与ChatGPT等方法，在实际生产环境中难以确保高质量输出。针对SME部署LLM驱动的CRS，本文提出了战略考量，特别是在当前技术环境下的权衡选择。

> Large language models (LLMs) present an enormous evolution in the strategic potential of conversational recommender systems (CRS). Yet to date, research has predominantly focused upon technical frameworks to implement LLM-driven CRS, rather than end-user evaluations or strategic implications for firms, particularly from the perspective of a small to medium enterprises (SME) that makeup the bedrock of the global economy. In the current paper, we detail the design of an LLM-driven CRS in an SME setting, and its subsequent performance in the field using both objective system metrics and subjective user evaluations. While doing so, we additionally outline a short-form revised ResQue model for evaluating LLM-driven CRS, enabling replicability in a rapidly evolving field. Our results reveal good system performance from a user experience perspective (85.5% recommendation accuracy) but underscore latency, cost, and quality issues challenging business viability. Notably, with a median cost of $0.04 per interaction and a latency of 5.7s, cost-effectiveness and response time emerge as crucial areas for achieving a more user-friendly and economically viable LLM-driven CRS for SME settings. One major driver of these costs is the use of an advanced LLM as a ranker within the retrieval-augmented generation (RAG) technique. Our results additionally indicate that relying solely on approaches such as Prompt-based learning with ChatGPT as the underlying LLM makes it challenging to achieve satisfying quality in a production environment. Strategic considerations for SMEs deploying an LLM-driven CRS are outlined, particularly considering trade-offs in the current technical landscape.

[Arxiv](https://arxiv.org/abs/2407.04472)