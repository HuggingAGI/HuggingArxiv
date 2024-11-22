# 从“愚蠢”的问题中学习能够对大型语言模型有所改进，不过改进程度甚微。

发布时间：2024年11月21日

`LLM应用` `语言模型`

> Learning from "Silly" Questions Improves Large Language Models, But Only Slightly

# 摘要

> 构建高质量的有监督微调（SFT）数据集对大型语言模型（LLMs）的训练意义重大。近期研究发现，使用来自特定来源——用户为深入理解某些主题而提出“傻问题”的中文网站若志吧的数据，能够带来更出色的微调效果。本文旨在探究一些潜在因素：其成功的缘由以及对性能的大规模评估。首先，我们借助 GPT-4 从教育、心理学和认知科学的视角剖析若志吧问题的成功案例，推导出一组解释性规则。接着，我们将这些规则应用于 MMLU 训练集来构建微调数据集。令人意外的是，我们的成果显示，规则在某些任务中能显著提升模型性能，在另一些任务中却可能导致性能降低。比如，依照“反直觉思维”规则生成的 SFT 数据在“全球事实”任务上能实现约 5％的提升，而“模糊概念边界”规则在“计量经济学”任务上致使性能下降 6.14％。此外，对于特定任务，不同规则对模型性能的影响往往具有一致性。这表明所提取的规则之间差异不大，且规则的有效性在不同任务中相对一致。我们的研究凸显了在构建 SFT 数据集时，考虑任务多样性和规则适用性对于实现更全面的性能提升的重要性。

> Constructing high-quality Supervised Fine-Tuning (SFT) datasets is critical for the training of large language models (LLMs). Recent studies have shown that using data from a specific source, Ruozhiba, a Chinese website where users ask "silly" questions to better understand certain topics, can lead to better fine-tuning performance. This paper aims to explore some hidden factors: the potential interpretations of its success and a large-scale evaluation of the performance. First, we leverage GPT-4 to analyze the successful cases of Ruozhiba questions from the perspective of education, psychology, and cognitive science, deriving a set of explanatory rules. Then, we construct fine-tuning datasets by applying these rules to the MMLU training set. Surprisingly, our results indicate that rules can significantly improve model performance in certain tasks, while potentially diminishing performance on others. For example, SFT data generated following the "Counterintuitive Thinking" rule can achieve approximately a 5% improvement on the "Global Facts" task, whereas the "Blurring the Conceptual Boundaries" rule leads to a performance drop of 6.14% on the "Econometrics" task. In addition, for specific tasks, different rules tend to have a consistent impact on model performance. This suggests that the differences between the extracted rules are not as significant, and the effectiveness of the rules is relatively consistent across tasks. Our research highlights the importance of considering task diversity and rule applicability when constructing SFT datasets to achieve more comprehensive performance improvements.

[Arxiv](https://arxiv.org/abs/2411.14121)