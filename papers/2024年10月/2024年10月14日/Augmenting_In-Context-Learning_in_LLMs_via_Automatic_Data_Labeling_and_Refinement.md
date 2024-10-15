# 借助自动数据标注与优化，提升 LLM 中的 In-Context-Learning 效果

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Augmenting In-Context-Learning in LLMs via Automatic Data Labeling and Refinement

# 摘要

> 大型语言模型 (LLM) 通过 Chain of Thought (CoT) 或 In-Context Learning (ICL) 可以显著提升性能，但这些方法需要繁琐的手动演示。为此，我们提出了自动数据标注和细化 (ADLR)，从少量手工示例出发，自动生成和优化包含中间步骤的演示。实验表明，ADLR 在代码表格问答和数学推理任务中，性能提升高达 5.5%。相关代码将在补充材料中公开。

> It has been shown that Large Language Models' (LLMs) performance can be improved for many tasks using Chain of Thought (CoT) or In-Context Learning (ICL), which involve demonstrating the steps needed to solve a task using a few examples. However, while datasets with input-output pairs are relatively easy to produce, providing demonstrations which include intermediate steps requires cumbersome manual work. These steps may be executable programs, as in agentic flows, or step-by-step reasoning as in CoT. In this work, we propose Automatic Data Labeling and Refinement (ADLR), a method to automatically generate and filter demonstrations which include the above intermediate steps, starting from a small seed of manually crafted examples. We demonstrate the advantage of ADLR in code-based table QA and mathematical reasoning, achieving up to a 5.5% gain. The code implementing our method is provided in the Supplementary material and will be made available.

[Arxiv](https://arxiv.org/abs/2410.10348)