# 逆向思考：用逆向强化学习重构 LLM 训练目标

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Insights from the Inverse: Reconstructing LLM Training Goals Through Inverse RL

# 摘要

> 通过 RLHF 训练的 LLM 表现出色，但其奖励函数和决策过程仍不透明。本文提出一种新方法，利用 IRL 揭示 LLM 的隐含奖励函数。我们在不同规模的毒性对齐 LLM 上实验，提取的奖励模型在预测人类偏好上准确率高达 80.40%。分析显示，奖励函数的非可识别性、模型大小与可解释性的关系，以及 RLHF 过程中的潜在问题。我们还证明，IRL 衍生的奖励模型可用于微调新 LLM，提升毒性基准上的表现。这项研究为理解和优化 LLM 对齐提供了新视角，对负责任的系统开发和部署具有深远影响。

> Large language models (LLMs) trained with Reinforcement Learning from Human Feedback (RLHF) have demonstrated remarkable capabilities, but their underlying reward functions and decision-making processes remain opaque. This paper introduces a novel approach to interpreting LLMs by applying inverse reinforcement learning (IRL) to recover their implicit reward functions. We conduct experiments on toxicity-aligned LLMs of varying sizes, extracting reward models that achieve up to 80.40% accuracy in predicting human preferences. Our analysis reveals key insights into the non-identifiability of reward functions, the relationship between model size and interpretability, and potential pitfalls in the RLHF process. We demonstrate that IRL-derived reward models can be used to fine-tune new LLMs, resulting in comparable or improved performance on toxicity benchmarks. This work provides a new lens for understanding and improving LLM alignment, with implications for the responsible development and deployment of these powerful systems.

[Arxiv](https://arxiv.org/abs/2410.12491)