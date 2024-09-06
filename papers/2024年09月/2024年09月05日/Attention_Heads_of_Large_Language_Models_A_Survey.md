# 大型语言模型的注意力机制：全面调查

发布时间：2024年09月05日

`LLM理论` `人工智能`

> Attention Heads of Large Language Models: A Survey

# 摘要

> 自ChatGPT问世以来，大型语言模型（LLMs）虽在多任务中表现卓越，但仍如黑箱般神秘。其发展高度依赖数据驱动，限制了通过调整内部架构和推理路径来提升性能。为此，许多研究者开始深入探索LLMs的内部机制，特别是注意力头，以揭示其推理瓶颈。我们的研究聚焦于注意力头的可解释性和基本机制，将人类思维过程简化为四阶段：知识回忆、上下文识别、潜在推理和表达准备。通过此框架，我们系统梳理现有研究，分类特定注意力头的功能，并总结了无模型和需要模型两类实验方法。此外，我们概述了相关评估方法和基准，讨论了当前研究的局限性，并展望了未来方向。参考列表已在\url{https://github.com/IAAR-Shanghai/Awesome-Attention-Heads}开源。

> Since the advent of ChatGPT, Large Language Models (LLMs) have excelled in various tasks but remain largely as black-box systems. Consequently, their development relies heavily on data-driven approaches, limiting performance enhancement through changes in internal architecture and reasoning pathways. As a result, many researchers have begun exploring the potential internal mechanisms of LLMs, aiming to identify the essence of their reasoning bottlenecks, with most studies focusing on attention heads. Our survey aims to shed light on the internal reasoning processes of LLMs by concentrating on the interpretability and underlying mechanisms of attention heads. We first distill the human thought process into a four-stage framework: Knowledge Recalling, In-Context Identification, Latent Reasoning, and Expression Preparation. Using this framework, we systematically review existing research to identify and categorize the functions of specific attention heads. Furthermore, we summarize the experimental methodologies used to discover these special heads, dividing them into two categories: Modeling-Free methods and Modeling-Required methods. Also, we outline relevant evaluation methods and benchmarks. Finally, we discuss the limitations of current research and propose several potential future directions. Our reference list is open-sourced at \url{https://github.com/IAAR-Shanghai/Awesome-Attention-Heads}.

[Arxiv](https://arxiv.org/abs/2409.03752)