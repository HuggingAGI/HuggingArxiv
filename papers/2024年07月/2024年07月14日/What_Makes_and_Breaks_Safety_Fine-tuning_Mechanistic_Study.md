# 安全微调的成与败：机制探究

发布时间：2024年07月14日

`LLM理论` `人工智能` `网络安全`

> What Makes and Breaks Safety Fine-tuning? Mechanistic Study

# 摘要

> 安全微调有助于确保大型语言模型 (LLM) 符合人类对其安全部署的期望。为深入探究安全微调背后的关键因素，我们构建了一个合成数据生成框架，通过模拟模型执行任务与其具体应用概念间的互动，精准捕捉不安全输入的特征。我们深入分析了三种主流安全微调技术——监督微调、偏好优化及遗忘策略，并发现这些方法通过微调 MLP 权重，巧妙地将潜在风险输入转化为安全模式，实现输入安全性的智能聚类。面对对抗性输入时，模型能将其激活状态调整至接近安全样本，从而确保其处理过程的安全性。我们在真实模型 Llama-2 7B 和 Llama-3 8B 上验证了这些发现，展现了安全微调的实际应用价值。

> Safety fine-tuning helps align Large Language Models (LLMs) with human preferences for their safe deployment. To better understand the underlying factors that make models safe via safety fine-tuning, we design a synthetic data generation framework that captures salient aspects of an unsafe input by modeling the interaction between the task the model is asked to perform (e.g., ``design'') versus the specific concepts the task is asked to be performed upon (e.g., a ``cycle'' vs. a ``bomb''). Using this, we investigate three well-known safety fine-tuning methods -- supervised safety fine-tuning, direct preference optimization, and unlearning -- and provide significant evidence demonstrating that these methods minimally transform MLP weights to specifically align unsafe inputs into its weights' null space. This yields a clustering of inputs based on whether the model deems them safe or not. Correspondingly, when an adversarial input (e.g., a jailbreak) is provided, its activations are closer to safer samples, leading to the model processing such an input as if it were safe. We validate our findings, wherever possible, on real-world models -- specifically, Llama-2 7B and Llama-3 8B.

[Arxiv](https://arxiv.org/abs/2407.10264)