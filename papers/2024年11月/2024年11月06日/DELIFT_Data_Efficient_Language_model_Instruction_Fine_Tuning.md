# DELIFT：数据高效语言模型指令微调

发布时间：2024年11月06日

`LLM应用` `语言模型` `数据优化`

> DELIFT: Data Efficient Language model Instruction Fine Tuning

# 摘要

> 对大型语言模型（LLMs）进行微调对于提高其在特定任务上的性能至关重要，但由于冗余或无信息的数据，这通常是资源密集型的。为了解决这种低效率，我们引入了 DELIFT（数据高效语言模型指令微调），这是一种新颖的算法，系统地优化了微调的三个关键阶段的数据选择：（1）指令调整，（2）特定任务微调（例如，推理、问答），以及（3）持续微调（例如，纳入新的数据版本）。与现有的专注于单阶段优化或依赖计算密集型梯度计算的方法不同，DELIFT 在所有阶段都能高效运行。我们方法的核心是一个成对效用指标，它量化了一个数据样本对于改进模型对其他样本的响应有多大益处，有效地测量了相对于模型当前能力的信息价值。通过利用应用于该指标的不同子模函数，DELIFT 选择了在微调的所有阶段都有用的多样化和最优子集。在各种任务和模型规模上的实验表明，DELIFT 可以在不影响性能的情况下将微调数据大小减少多达 70％，大大节省了计算资源，并且在效率和效果上都优于现有方法。

> Fine-tuning large language models (LLMs) is essential for enhancing their performance on specific tasks but is often resource-intensive due to redundant or uninformative data. To address this inefficiency, we introduce DELIFT (Data Efficient Language model Instruction Fine-Tuning), a novel algorithm that systematically optimizes data selection across the three key stages of fine-tuning: (1) instruction tuning, (2) task-specific fine-tuning (e.g., reasoning, question-answering), and (3) continual fine-tuning (e.g., incorporating new data versions). Unlike existing methods that focus on single-stage optimization or rely on computationally intensive gradient calculations, DELIFT operates efficiently across all stages. Central to our approach is a pairwise utility metric that quantifies how beneficial a data sample is for improving the model's responses to other samples, effectively measuring the informational value relative to the model's current capabilities. By leveraging different submodular functions applied to this metric, DELIFT selects diverse and optimal subsets that are useful across all stages of fine-tuning. Experiments across various tasks and model scales demonstrate that DELIFT can reduce the fine-tuning data size by up to 70% without compromising performance, offering significant computational savings and outperforming existing methods in both efficiency and efficacy.

[Arxiv](https://arxiv.org/abs/2411.04425)