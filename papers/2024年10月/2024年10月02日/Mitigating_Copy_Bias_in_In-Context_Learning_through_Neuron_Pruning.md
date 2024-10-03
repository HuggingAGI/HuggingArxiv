# 通过神经元修剪技术，我们能够有效减轻上下文学习中的复制偏差问题。

发布时间：2024年10月02日

`LLM理论` `人工智能` `机器学习`

> Mitigating Copy Bias in In-Context Learning through Neuron Pruning

# 摘要

> LLM 在少样本 ICL 方面表现出色，但有时会陷入“复制偏差”，即简单复制示例答案而非学习本质模式。为此，我们提出了一种新颖简便的方法来缓解这一问题。首先，通过合成任务和 Integrated Gradients 方法，我们识别并修剪了那些过度依赖复制的神经元。实验证明，这一操作显著提升了各类 ICL 任务的性能。此外，我们的方法兼容多种 LLM 架构，无需额外调整。分析中，我们聚焦于 ICL 的任务识别能力，发现修剪操作优化了任务向量的质量，揭示了这些神经元原本对任务识别的阻碍作用。

> Large language models (LLMs) have demonstrated impressive few-shot in-context learning (ICL) abilities. Still, we show that they are sometimes prone to a `copying bias', where they copy answers from provided examples instead of learning the underlying patterns. In this work, we propose a novel and simple method to mitigate such copying bias. First, we create a synthetic task and use the Integrated Gradients method to identify neurons that prioritize copying over generalization. We demonstrate that pruning these neurons consistently improves performance across a diverse set of ICL tasks. We also show that our method is applicable across various LLM architectures, including Transformers and State-Space Models, without requiring modifications. In our analysis, we adopt a task-recognition perspective on ICL and examine task vectors (Hendel et al., 2023) induced by the model. We find that pruning enhances the quality of these vectors, suggesting that the pruned neurons previously hindered effective task recognition.

[Arxiv](https://arxiv.org/abs/2410.01288)