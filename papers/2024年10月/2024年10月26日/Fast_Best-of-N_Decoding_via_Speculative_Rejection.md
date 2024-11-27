# 通过推测性拒绝来达成快速的最佳 N 解码

发布时间：2024年10月26日

`LLM应用` `语言模型` `人工智能`

> Fast Best-of-N Decoding via Speculative Rejection

# 摘要

> 大型语言模型（LLMs）的安全有效部署离不开一个关键步骤——对齐，它能保证模型的响应符合人类偏好。像 DPO、PPO 及其变体这类流行的对齐技术，会在后训练阶段改变预训练模型的权重来实现 LLMs 的对齐。尽管这些后训练方法占据主流，但在部署 LLMs 前会大幅增加复杂性。推理时间对齐方法避开了复杂的后训练步骤，而是让生成的结果倾向于符合人类偏好的响应。最知名的推理时间对齐方法——Best-of-N，与最先进的后训练程序效果相当。可惜的是，Best-of-N 在推理时所需资源远超标准解码策略，在计算上不可行。在本研究中，我们推出了推测性拒绝，这是一种计算可行的推理时间对齐算法。它能像 Best-of-N 那样依据给定的奖励模型生成高分响应，而且计算效率能提高 16 至 32 倍。

> The safe and effective deployment of Large Language Models (LLMs) involves a critical step called alignment, which ensures that the model's responses are in accordance with human preferences. Prevalent alignment techniques, such as DPO, PPO and their variants, align LLMs by changing the pre-trained model weights during a phase called post-training. While predominant, these post-training methods add substantial complexity before LLMs can be deployed. Inference-time alignment methods avoid the complex post-training step and instead bias the generation towards responses that are aligned with human preferences. The best-known inference-time alignment method, called Best-of-N, is as effective as the state-of-the-art post-training procedures. Unfortunately, Best-of-N requires vastly more resources at inference time than standard decoding strategies, which makes it computationally not viable. In this work, we introduce Speculative Rejection, a computationally-viable inference-time alignment algorithm. It generates high-scoring responses according to a given reward model, like Best-of-N does, while being between 16 to 32 times more computationally efficient.

[Arxiv](https://arxiv.org/abs/2410.20290)