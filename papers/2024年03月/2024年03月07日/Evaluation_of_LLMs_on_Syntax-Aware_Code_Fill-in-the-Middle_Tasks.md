# [我们对LLMs在处理具有语法敏感性的代码中间填充任务时的表现进行评估，以深入探究其理解和生成代码结构的能力。](https://arxiv.org/abs/2403.04814)

发布时间：2024年03月07日

`LLM应用`

> Evaluation of LLMs on Syntax-Aware Code Fill-in-the-Middle Tasks

> 我们创新推出了Syntax-Aware Fill-In-the-Middle (SAFIM)基准测试，专门用于检验大型语言模型（LLMs）在代码“填空”任务中的表现。此基准聚焦于对代码块、条件表达式等程序结构的语法敏感性补全，涵盖了自2022年4月以来不同编程语言的17,720个新鲜示例，确保数据尽可能纯净。SAFIM配备了一系列精心设计的提示方案与独特的语法感知后处理技术，为公平公正地对比LLMs提供了稳健的试验场。通过对15款LLMs的详尽评估，我们发现FIM预训练不仅能显著增强模型在FIM任务上的实力，还有助于提升LLMs执行从左至右（L2R）推理的能力。这一系列成果颠覆了固有认知，揭示了预训练方法及数据质量可能比模型规模更具影响力。因此，SAFIM作为一项基石性的资源，为探索代码LLMs高效预训练策略的研究铺平了道路。相关评估工具包和数据集已开放在GitHub（https://github.com/gonglinyuan/safim）下载，同时排行榜信息可在https://safimbenchmark.com查阅。

> We introduce Syntax-Aware Fill-In-the-Middle (SAFIM), a new benchmark for evaluating Large Language Models (LLMs) on the code Fill-in-the-Middle (FIM) task. This benchmark focuses on syntax-aware completions of program structures such as code blocks and conditional expressions, and includes 17,720 examples from multiple programming languages, sourced from recent code submissions after April 2022 to minimize data contamination. SAFIM provides a robust framework with various prompt designs and novel syntax-aware post-processing techniques, facilitating accurate and fair comparisons across LLMs. Our comprehensive evaluation of 15 LLMs shows that FIM pretraining not only enhances FIM proficiency but also improves Left-to-Right (L2R) inference using LLMs. Our findings challenge conventional beliefs and suggest that pretraining methods and data quality have more impact than model size. SAFIM thus serves as a foundational platform for future research in effective pretraining strategies for code LLMs. The evaluation toolkit and dataset are available at https://github.com/gonglinyuan/safim, and the leaderboard is available at https://safimbenchmark.com.

![我们对LLMs在处理具有语法敏感性的代码中间填充任务时的表现进行评估，以深入探究其理解和生成代码结构的能力。](../../../paper_images/2403.04814/x1.png)

![我们对LLMs在处理具有语法敏感性的代码中间填充任务时的表现进行评估，以深入探究其理解和生成代码结构的能力。](../../../paper_images/2403.04814/x2.png)

![我们对LLMs在处理具有语法敏感性的代码中间填充任务时的表现进行评估，以深入探究其理解和生成代码结构的能力。](../../../paper_images/2403.04814/x3.png)