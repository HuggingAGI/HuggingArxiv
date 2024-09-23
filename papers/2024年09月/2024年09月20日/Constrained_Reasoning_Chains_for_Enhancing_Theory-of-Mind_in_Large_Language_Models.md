# 通过约束推理链提升大型语言模型的心智理论能力

发布时间：2024年09月20日

`LLM理论` `人工智能`

> Constrained Reasoning Chains for Enhancing Theory-of-Mind in Large Language Models

# 摘要

> 大型语言模型 (LLM) 的 Theory-of-Mind (ToM) 能力有限，现有方法多采用零-shot 提示，但在复杂推理和非叙事上下文中表现不佳。我们提出 Constrained Chain-of-ToM (CCoToM)，利用领域知识和因果关系，指导 LLM 构建推理链，并自适应调整提示以提高一致性。CCoToM 不仅适用于叙事，还能处理对话等非叙事上下文。实验证明，CCoToM 在各 LLM 和数据集上均大幅超越现有方法。我们还深入分析了 CCoToM，并公开了代码。

> Theory-of-Mind (ToM) ability possessed by Large Language Models (LLMs) has been shown to be limited. Most existing methods for improving ToM in LLMs adopt zero-shot prompting, and they face challenges including poor performance in complex ToM reasoning tasks and an inability to handle non-narrative contexts. We propose a zero-shot prompting method named Constrained Chain-of-ToM (CCoToM) that leverages domain knowledge and the causal relations between ToM dimensions to address these limitations. Specifically, CCoToM guides LLMs to construct explicit reasoning chains by first prompting LLMs to infer related ToM dimensions (e.g., belief). Afterward, CCoToM prompts LLMs to infer the queried ToM dimension based on the generated related ToM dimensions and corresponding causal relations. Additionally, CCoToM adaptively imposes constraints on prompts to introduce inductive biases and improve consistency between ToM dimensions. Besides narratives, CCoToM can also handle non-narrative contexts like conversations. Extensive experiments show that CCoToM consistently outperforms previous state-of-the-art methods by large margins across all LLMs and datasets used. We also conduct in-depth analyses to gain deeper insights into CCoToM. We have made our code publicly available.

[Arxiv](https://arxiv.org/abs/2409.13490)