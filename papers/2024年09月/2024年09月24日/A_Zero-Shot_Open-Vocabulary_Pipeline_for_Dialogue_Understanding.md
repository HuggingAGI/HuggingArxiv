# 零-shot 开放词汇对话理解管道

发布时间：2024年09月24日

`LLM应用` `对话系统` `任务型对话`

> A Zero-Shot Open-Vocabulary Pipeline for Dialogue Understanding

# 摘要

> 对话状态跟踪 (DST) 在面向任务的对话中至关重要，但现有方法多依赖预定义本体和黄金标签，难以适应新槽值。基于大型语言模型 (LLM) 的系统虽有零-shot 潜力，却面临计算资源消耗大或性能不足的问题。为此，我们提出了一种零-shot、开放词汇的系统，通过单一管道整合领域分类和 DST，将 DST 重构为问答任务，并采用自我精炼提示。该系统不依赖固定槽值，能动态适应。实验表明，在 Multi-WOZ 2.1 数据集上，我们的方法比现有 SOTA 高出 20% 的联合目标准确性 (JGA)，且 LLM API 请求减少 90%。

> Dialogue State Tracking (DST) is crucial for understanding user needs and executing appropriate system actions in task-oriented dialogues. Majority of existing DST methods are designed to work within predefined ontologies and assume the availability of gold domain labels, struggling with adapting to new slots values. While Large Language Models (LLMs)-based systems show promising zero-shot DST performance, they either require extensive computational resources or they underperform existing fully-trained systems, limiting their practicality. To address these limitations, we propose a zero-shot, open-vocabulary system that integrates domain classification and DST in a single pipeline. Our approach includes reformulating DST as a question-answering task for less capable models and employing self-refining prompts for more adaptable ones. Our system does not rely on fixed slot values defined in the ontology allowing the system to adapt dynamically. We compare our approach with existing SOTA, and show that it provides up to 20% better Joint Goal Accuracy (JGA) over previous methods on datasets like Multi-WOZ 2.1, with up to 90% fewer requests to the LLM API.

[Arxiv](https://arxiv.org/abs/2409.15861)