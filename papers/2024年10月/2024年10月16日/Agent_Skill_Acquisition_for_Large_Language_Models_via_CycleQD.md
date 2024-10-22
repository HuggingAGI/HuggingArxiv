# 利用 CycleQD 提升大型语言模型的代理技能

发布时间：2024年10月16日

`LLM理论` `人工智能` `软件开发`

> Agent Skill Acquisition for Large Language Models via CycleQD

# 摘要

> 训练大型语言模型以掌握特定技能依然充满挑战。传统方法常受困于数据分布不均和目标函数与任务需求不匹配。为此，我们推出了 CycleQD，一种结合循环适应算法、模型合并交叉和 SVD 变异的新方法，利用质量多样性框架。在 CycleQD 中，每个任务的性能指标轮流成为质量评估标准，其他任务则作为行为特征。这种循环机制使得模型能专注于单一任务，无需调整数据比例，简化了目标函数设计。实证数据显示，CycleQD 应用于 LLAMA3-8B-INSTRUCT 模型后，在编码、操作系统和数据库任务中不仅超越了传统微调方法，还达到了与 GPT-3.5-TURBO 相当的性能，尽管后者可能拥有更多参数。尤为重要的是，CycleQD 在提升性能的同时，仍保持了强大的语言能力，这在广泛使用的语言基准测试中得到了验证。我们详细阐述了 CycleQD 的关键设计，展示了其如何提升效果。此外，该方法通用性强，还可应用于图像分割模型，彰显了其在多领域的广泛适用性。

> Training large language models to acquire specific skills remains a challenging endeavor. Conventional training approaches often struggle with data distribution imbalances and inadequacies in objective functions that do not align well with task-specific performance. To address these challenges, we introduce CycleQD, a novel approach that leverages the Quality Diversity framework through a cyclic adaptation of the algorithm, along with a model merging based crossover and an SVD-based mutation. In CycleQD, each task's performance metric is alternated as the quality measure while the others serve as the behavioral characteristics. This cyclic focus on individual tasks allows for concentrated effort on one task at a time, eliminating the need for data ratio tuning and simplifying the design of the objective function. Empirical results from AgentBench indicate that applying CycleQD to LLAMA3-8B-INSTRUCT based models not only enables them to surpass traditional fine-tuning methods in coding, operating systems, and database tasks, but also achieves performance on par with GPT-3.5-TURBO, which potentially contains much more parameters, across these domains. Crucially, this enhanced performance is achieved while retaining robust language capabilities, as evidenced by its performance on widely adopted language benchmark tasks. We highlight the key design choices in CycleQD, detailing how these contribute to its effectiveness. Furthermore, our method is general and can be applied to image segmentation models, highlighting its applicability across different domains.

[Arxiv](https://arxiv.org/abs/2410.14735)