# 从探索到精通：借助自我驱动交互，让 LLM 掌握工具。

发布时间：2024年10月10日

`LLM应用` `人工智能` `软件开发`

> From Exploration to Mastery: Enabling LLMs to Master Tools via Self-Driven Interactions

# 摘要

> 工具学习让大型语言模型（LLM）通过调用工具与外界互动，有效缓解了预训练数据的局限。工具文档在此过程中至关重要，为LLM提供使用指南，促进工具的有效利用。本文聚焦于现有工具文档的不完善和不准确导致的LLM与外部工具间的理解鸿沟。我们提出新框架DRAFT，通过分析LLM与工具交互的反馈和轨迹，动态优化工具文档。该方法采用试错策略，包括经验收集、学习与文档重写三个阶段，迭代提升文档质量。同时，通过多样性探索策略和工具自适应终止机制，防止过拟合并提高效率。实验证明，DRAFT的反馈驱动优化显著改善了文档质量，使LLM更深入理解并更有效使用工具。特别地，我们的方法优化后的工具文档展现出强大的跨模型泛化能力。

> Tool learning enables Large Language Models (LLMs) to interact with external environments by invoking tools, serving as an effective strategy to mitigate the limitations inherent in their pre-training data. In this process, tool documentation plays a crucial role by providing usage instructions for LLMs, thereby facilitating effective tool utilization. This paper concentrates on the critical challenge of bridging the comprehension gap between LLMs and external tools due to the inadequacies and inaccuracies inherent in existing human-centric tool documentation. We propose a novel framework, DRAFT, aimed at Dynamically Refining tool documentation through the Analysis of Feedback and Trails emanating from LLMs' interactions with external tools. This methodology pivots on an innovative trial-and-error approach, consisting of three distinct learning phases: experience gathering, learning from experience, and documentation rewriting, to iteratively enhance the tool documentation. This process is further optimized by implementing a diversity-promoting exploration strategy to ensure explorative diversity and a tool-adaptive termination mechanism to prevent overfitting while enhancing efficiency. Extensive experiments on multiple datasets demonstrate that DRAFT's iterative, feedback-based refinement significantly ameliorates documentation quality, fostering a deeper comprehension and more effective utilization of tools by LLMs. Notably, our analysis reveals that the tool documentation refined via our approach demonstrates robust cross-model generalization capabilities.

[Arxiv](https://arxiv.org/abs/2410.08197)