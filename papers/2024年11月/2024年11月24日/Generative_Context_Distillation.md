# 生成式的上下文蒸馏

发布时间：2024年11月24日

`Agent` `语言模型` `代理应用`

> Generative Context Distillation

# 摘要

> 在近期基于大型语言模型的应用中，所使用的提示往往固定且冗长，从而产生了大量的计算开销。为应对此挑战，我们提出了生成式上下文蒸馏（GCD），这是一种采用联合训练方式的轻量级提示内化方法。该方法不仅能复刻有提示输入的模型的行为，还能生成提示内容以及模型行为应相应改变的缘由。我们证实，此方法在各类基于代理的应用场景中，能有效地内化复杂提示。为在不与专用环境互动的情况下进行有效训练，我们引入了一种数据合成技术，通过调换代理和环境的角色来自动收集对话数据集。这种方法在仅有预定义提示而无相应训练数据集的情形下尤为有用。通过内化复杂提示，生成式上下文蒸馏能够实现高性能且高效的推理，无需明确的提示。

> Prompts used in recent large language model based applications are often fixed and lengthy, leading to significant computational overhead. To address this challenge, we propose Generative Context Distillation (GCD), a lightweight prompt internalization method that employs a joint training approach. This method not only replicates the behavior of models with prompt inputs but also generates the content of the prompt along with reasons for why the model's behavior should change accordingly. We demonstrate that our approach effectively internalizes complex prompts across various agent-based application scenarios. For effective training without interactions with the dedicated environments, we introduce a data synthesis technique that autonomously collects conversational datasets by swapping the roles of the agent and environment. This method is especially useful in scenarios where only a predefined prompt is available without a corresponding training dataset. By internalizing complex prompts, Generative Context Distillation enables high-performance and efficient inference without the need for explicit prompts.

[Arxiv](https://arxiv.org/abs/2411.15927)