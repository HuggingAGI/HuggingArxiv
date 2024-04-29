# 大型语言模型作为机械设计代理

发布时间：2024年04月26日

`分类：Agent

这篇论文提出了一种将大型语言模型（LLM）与有限元模块（FEM）相结合的创新方法，用于自动化机械设计过程。该方法利用LLM的推理能力来生成和优化设计，而FEM模块则提供关键反馈以指导LLM的学习过程。这种方法展示了LLM在自主开发和实施有效设计策略方面的潜力，因此可以归类为Agent领域。` `机械设计` `人工智能`

> Large Language Model Agent as a Mechanical Designer

# 摘要

> 传统机械设计依赖资深专家通过经验驱动的修改和有限元分析（FEA）来逐步完善设计，以满足特定需求。但这一过程不仅耗时，而且高度依赖于既有知识和经验。尽管众多机器学习模型被开发用以简化这一复杂且专家主导的迭代设计流程，它们往往需要庞大的训练数据集和高额的计算资源。特别是，基于深度学习的模型通常只适用于它们所训练的特定领域和任务，这限制了它们的通用性，从而在自动化效率和资源消耗之间形成了一种权衡。在本研究中，我们提出了一种创新的方法，将预训练的大型语言模型（LLM）与有限元模块（FEM）相结合。FEM模块对每个设计方案进行评估，并提供关键反馈，引导LLM进行持续的学习、规划、设计生成和优化，无需特定领域的训练。我们在桁架结构的迭代优化管理中证明了所提出框架的有效性，展示了其根据结构化反馈和标准进行设计推理和改进的能力。研究结果显示，基于LLM的智能体能够以高达90%的成功率生成符合自然语言规格的桁架设计，这一成功率会根据所施加的约束条件而变化。通过采用基于提示的优化技术，我们证明了基于LLM的智能体在提供解决方案与得分对时，能够展现出优化行为，以迭代方式精细化设计以满足特定规格。LLM智能体的这种能力，即基于其内在推理能力来生成可行的设计并进行优化，突显了它们在自主开发和实施有效设计策略方面的潜力。

> Conventional mechanical design paradigms rely on experts systematically refining concepts through experience-guided modification and FEA to meet specific requirements. However, this approach can be time-consuming and heavily dependent on prior knowledge and experience. While numerous machine learning models have been developed to streamline this intensive and expert-driven iterative process, these methods typically demand extensive training data and considerable computational resources. Furthermore, methods based on deep learning are usually restricted to the specific domains and tasks for which they were trained, limiting their applicability across different tasks. This creates a trade-off between the efficiency of automation and the demand for resources. In this study, we present a novel approach that integrates pre-trained LLMs with a FEM module. The FEM module evaluates each design and provides essential feedback, guiding the LLMs to continuously learn, plan, generate, and optimize designs without the need for domain-specific training. We demonstrate the effectiveness of our proposed framework in managing the iterative optimization of truss structures, showcasing its capability to reason about and refine designs according to structured feedback and criteria. Our results reveal that these LLM-based agents can successfully generate truss designs that comply with natural language specifications with a success rate of up to 90%, which varies according to the applied constraints. By employing prompt-based optimization techniques we show that LLM based agents exhibit optimization behavior when provided with solution-score pairs to iteratively refine designs to meet specifications. This ability of LLM agents to produce viable designs and optimize them based on their inherent reasoning capabilities highlights their potential to develop and implement effective design strategies autonomously.

[Arxiv](https://arxiv.org/abs/2404.17525)