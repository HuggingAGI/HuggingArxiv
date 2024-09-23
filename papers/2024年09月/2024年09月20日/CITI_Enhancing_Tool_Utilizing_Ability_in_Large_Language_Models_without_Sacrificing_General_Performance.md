# CITI：提升大型语言模型的工具使用能力，同时不降低其通用性能

发布时间：2024年09月20日

`LLM应用` `人工智能` `软件工程`

> CITI: Enhancing Tool Utilizing Ability in Large Language Models without Sacrificing General Performance

# 摘要

> 工具学习让大型语言模型 (LLM) 通过调用工具与外部环境互动，提升了其准确性和能力范围。然而，以往的研究多聚焦于提高工具利用的准确性和泛化能力，却忽视了这种调整对模型整体性能的负面影响。这偏离了整合工具以增强模型的初衷。为此，我们深入分析了模型组件的隐藏表示变化和梯度重要性，提出了一种基于组件重要性的工具利用能力注入方法 (CITI)。CITI 根据组件的重要性分数，采用不同的训练策略，有效缓解了微调带来的能力冲突。对重要组件，CITI 应用了 Mixture-Of-LoRA (MOLoRA)；对次要组件，则进行微调并保持其他参数不变。实验证明，CITI 在提升工具利用能力的同时，并未显著影响模型的整体性能，表现出色。

> Tool learning enables the Large Language Models (LLMs) to interact with the external environment by invoking tools, enriching the accuracy and capability scope of LLMs. However, previous works predominantly focus on improving model's tool-utilizing accuracy and the ability to generalize to new, unseen tools, excessively forcing LLMs to adjust specific tool-invoking pattern without considering the harm to model's general performance. This deviates from the actual applications and original intention of integrating tools to enhance model. To tackle this problem, we dissect the capability trade-offs by examining the hidden representation changes and the gradient-based importance score of model's components. Based on the analysis result, we propose a Component Importance-based Tool-utilizing ability Injection method (CITI). According to the gradient-based importance score of different components, it alleviates the capability conflicts caused by fine-tuning process by applying distinct training strategies to different components. CITI applies Mixture-Of-LoRA (MOLoRA) for important components. Meanwhile, it fine-tunes the parameters of few components deemed less important in the backbone of the LLM, while keeping other parameters frozen. CITI can effectively enhance the model's tool-utilizing capability without excessively compromising its general performance. Experimental results demonstrate that our approach achieves outstanding performance across a range of evaluation metrics.

[Arxiv](https://arxiv.org/abs/2409.13202)