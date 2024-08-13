# 探索边界：大型语言模型任务可行性的光谱研究

发布时间：2024年08月11日

`LLM应用` `人工智能` `数据科学`

> Defining Boundaries: A Spectrum of Task Feasibility for Large Language Models

# 摘要

> 尽管大型语言模型在多任务处理中表现卓越，但面对超出其知识范畴的查询时，常给出错误或虚构的答案。本文旨在解决 LLM 识别并拒绝处理超出其能力范围任务的问题。我们首先对不可行任务进行了系统的定义和分类，涵盖了多种幻觉现象。接着，我们创建了一个包含多种不可行与可行任务的数据集，用于评估多个 LLM 的任务处理能力。同时，我们探讨了通过微调提升 LLM 拒绝处理不可行任务能力的可能性。实验结果证实了我们方法的有效性，为优化 LLM 在实际应用中的操作界限指明了方向。

> Large language models (LLMs) have shown remarkable performance in various tasks but often fail to handle queries that exceed their knowledge and capabilities, leading to incorrect or fabricated responses. This paper addresses the need for LLMs to recognize and refuse infeasible tasks due to the required skills surpassing their capabilities. We first systematically conceptualize infeasible tasks for LLMs, providing formal definitions and categorizations that cover a spectrum of related hallucinations. We develop and benchmark a new dataset comprising diverse infeasible and feasible tasks to test multiple LLMs' abilities on task feasibility. Furthermore, we explore the potential of training enhancements to increase LLMs' refusal capabilities with fine-tuning. Experiments validate the effectiveness of our methods, offering promising directions for refining the operational boundaries of LLMs in real applications.

[Arxiv](https://arxiv.org/abs/2408.05873)