# 分解聚合法：构建一个逐步透明的评估体系

发布时间：2024年05月24日

`LLM理论

这篇论文摘要讨论了大型语言模型（LLMs）在文本生成评估中的应用，并提出了一种新的评估策略——“分解与聚合”。这种方法旨在提高LLMs评估能力的透明度和准确性，通过将评估过程细化为多个阶段来实现。这与LLM的理论研究相关，因为它探索了如何改进和理解LLMs的评估机制，而不是直接应用LLMs或探讨其安全性。因此，这篇论文更符合LLM理论分类。` `文本评估`

> Decompose and Aggregate: A Step-by-Step Interpretable Evaluation Framework

# 摘要

> 随着大型语言模型研究的飞速发展，我们有了新的工具来评估文本生成。这些模型既高效又经济，但它们的评估准确性却成了研究的热点。以往的研究中，LLMs作为评判者时，通常只被允许一次提示以做出最终评价，并比较其结果与人类评价的一致性。这种方法缺乏对LLMs评估能力的深入理解。为此，我们提出了“分解与聚合”策略，借鉴教学实践，将评估过程细化为多个阶段。实验结果显示，这种方法不仅增强了LLMs评估能力的透明度，还在多个元评估基准上将性能提升了高达39.6%。

> The acceleration of Large Language Models (LLMs) research has opened up new possibilities for evaluating generated texts. They serve as scalable and economical evaluators, but the question of how reliable these evaluators are has emerged as a crucial research question. Prior research efforts in the meta-evaluation of LLMs as judges limit the prompting of an LLM to a single use to obtain a final evaluation decision. They then compute the agreement between LLMs' outputs and human labels. This lacks interpretability in understanding the evaluation capability of LLMs. In light of this challenge, we propose Decompose and Aggregate, which breaks down the evaluation process into different stages based on pedagogical practices. Our experiments illustrate that it not only provides a more interpretable window for how well LLMs evaluate, but also leads to improvements up to 39.6% for different LLMs on a variety of meta-evaluation benchmarks.

![分解聚合法：构建一个逐步透明的评估体系](../../../paper_images/2405.15329/crown-jewel-llmeval2.png)

![分解聚合法：构建一个逐步透明的评估体系](../../../paper_images/2405.15329/framework-llmeval2.png)

[Arxiv](https://arxiv.org/abs/2405.15329)