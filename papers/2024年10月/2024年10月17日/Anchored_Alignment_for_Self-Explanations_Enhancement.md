# 锚定对齐：自我解释的增强之道

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Anchored Alignment for Self-Explanations Enhancement

# 摘要

> 我们提出了一种对齐方法，帮助大型语言模型 (LLM) 在没有标注理由的情况下更好地表达推理。该方法包含三个核心部分：解释质量评估、自我指导数据集生成和模型对齐。此外，我们创新性地引入了“锚定偏好对对齐”技术，通过将模型输出分类为始终正确、始终错误和可变三组，优化偏好对选择。这种分类策略显著提升了直接偏好优化 (DPO) 的效果。实验证明，这种方法在保持准确性的同时，大幅提升了解释质量，优于其他微调策略。

> In this work, we introduce a methodology for alignment designed to enhance the ability of large language models (LLMs) to articulate their reasoning (self-explanation) even in the absence of annotated rationale explanations. Our alignment methodology comprises three key components: explanation quality assessment, self-instruction dataset generation, and model alignment. Additionally, we present a novel technique called Alignment with Anchor Preference Pairs, which improves the selection of preference pairs by categorizing model outputs into three groups: consistently correct, consistently incorrect, and variable. By applying tailored strategies to each category, we enhance the effectiveness of Direct Preference Optimization (DPO). Our experimental results demonstrate that this approach significantly improves explanation quality while maintaining accuracy compared to other fine-tuning strategies.

[Arxiv](https://arxiv.org/abs/2410.13216)