# 本研究通过三段论揭示大型语言模型中的推理偏差，并基于 NeuBAROCO 数据集提供深入见解。

发布时间：2024年08月08日

`LLM理论` `认知科学` `人工智能`

> Exploring Reasoning Biases in Large Language Models Through Syllogism: Insights from the NeuBAROCO Dataset

# 摘要

> 本文深入探讨了大型语言模型在自然语言逻辑推理中的表现，特别关注其是否存在类似人类的推理偏差。我们专注于三段论推理，这是一种在认知科学中广泛研究的人类自然推理形式。为此，我们创建了包含英语和日语三段论问题的NeuBAROCO数据集，旨在通过心理实验评估人类的推理能力。实验结果显示，领先的大型语言模型不仅展现出与人类相似的推理偏差，还存在其他错误倾向。尤其是在前提与假设关系复杂、非简单蕴含或矛盾的推理问题中，模型的表现有待大幅提升。此外，我们采用了一种创新的思维链提示方法，通过将三段论转化为抽象逻辑表达式并解释推理过程，深入分析了模型的推理能力。分析结果指出，LLMs的主要局限在于推理过程本身，而非对三段论的理解。

> This paper explores the question of how accurately current large language models can perform logical reasoning in natural language, with an emphasis on whether these models exhibit reasoning biases similar to humans. Specifically, our study focuses on syllogistic reasoning, a form of deductive reasoning extensively studied in cognitive science as a natural form of human reasoning. We present a syllogism dataset called NeuBAROCO, which consists of syllogistic reasoning problems in English and Japanese. This dataset was originally designed for psychological experiments to assess human reasoning capabilities using various forms of syllogisms. Our experiments with leading large language models indicate that these models exhibit reasoning biases similar to humans, along with other error tendencies. Notably, there is significant room for improvement in reasoning problems where the relationship between premises and hypotheses is neither entailment nor contradiction. We also present experimental results and in-depth analysis using a new Chain-of-Thought prompting method, which asks LLMs to translate syllogisms into abstract logical expressions and then explain their reasoning process. Our analysis using this method suggests that the primary limitations of LLMs lie in the reasoning process itself rather than the interpretation of syllogisms.

[Arxiv](https://arxiv.org/abs/2408.04403)