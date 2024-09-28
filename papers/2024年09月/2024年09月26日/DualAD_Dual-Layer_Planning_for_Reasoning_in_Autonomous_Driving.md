# DualAD：双层规划助力自动驾驶推理

发布时间：2024年09月26日

`Agent` `自动驾驶` `人工智能`

> DualAD: Dual-Layer Planning for Reasoning in Autonomous Driving

# 摘要

> 我们推出了 DualAD，一种模仿人类驾驶推理的自动驾驶框架。DualAD 分为两层：底层是处理常规任务的规则驱动运动规划器，上层则是将驾驶场景转化为文本的规则驱动编码器。这些文本随后由 LLM 处理，以做出驾驶决策。当检测到潜在危险时，上层会介入底层决策，模拟人类在紧急情况下的反应。实验证明，使用零-shot 预训练模型的 DualAD 远超缺乏推理能力的传统规划器。此外，文本编码器显著提升了模型对场景的理解能力。随着 LLM 的增强，DualAD 的表现也不断提升，显示出其巨大的发展潜力。我们已公开代码和基准测试，供大家参考。

> We present a novel autonomous driving framework, DualAD, designed to imitate human reasoning during driving. DualAD comprises two layers: a rule-based motion planner at the bottom layer that handles routine driving tasks requiring minimal reasoning, and an upper layer featuring a rule-based text encoder that converts driving scenarios from absolute states into text description. This text is then processed by a large language model (LLM) to make driving decisions. The upper layer intervenes in the bottom layer's decisions when potential danger is detected, mimicking human reasoning in critical situations. Closed-loop experiments demonstrate that DualAD, using a zero-shot pre-trained model, significantly outperforms rule-based motion planners that lack reasoning abilities. Our experiments also highlight the effectiveness of the text encoder, which considerably enhances the model's scenario understanding. Additionally, the integrated DualAD model improves with stronger LLMs, indicating the framework's potential for further enhancement. We make code and benchmarks publicly available.

[Arxiv](https://arxiv.org/abs/2409.18053)