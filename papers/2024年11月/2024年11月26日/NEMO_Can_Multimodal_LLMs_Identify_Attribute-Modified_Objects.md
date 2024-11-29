# NEMO：多模态 LLMs 能否识别属性修改后的对象？

发布时间：2024年11月26日

`LLM应用` `视觉理解` `对象识别`

> NEMO: Can Multimodal LLMs Identify Attribute-Modified Objects?

# 摘要

> 多模态大型语言模型（MLLMs）在视觉理解领域成果斐然，但其识别经特定属性修饰的对象的能力仍有待探究。为此，我们对 MLLMs 在对象识别方面的推理能力展开探索，涵盖从常识到超常识的各种场景。我们推出了一个全新的基准——NEMO，它包含 900 张原始水果及其对应属性修改后的图像，还有 2700 个问题，包括开放型、多项选择型和无解型。我们用这个基准评估了 26 个近期的开源及商业模型。结果显示，在 NEMO 中识别对象存在显著的性能差距，不同模型的答案偏好也大相径庭。虽然更强大的视觉编码器能提升性能，但 MLLMs 仍不及独立的视觉编码器。有趣的是，扩大模型规模并非总能带来更优结果，深入分析发现，在微调时，更大的 LLM 可能会削弱视觉编码器。这些发现揭示了当前 MLLMs 的关键局限，也为开发更通用、更具弹性的多模态模型指明了潜在方向。

> Multimodal Large Language Models (MLLMs) have made notable advances in visual understanding, yet their abilities to recognize objects modified by specific attributes remain an open question. To address this, we explore MLLMs' reasoning capabilities in object recognition, ranging from commonsense to beyond-commonsense scenarios. We introduce a novel benchmark, NEMO, which comprises 900 images of origiNal fruits and their corresponding attributE-MOdified ones; along with a set of 2,700 questions including open-, multiple-choice-, unsolvable types. We assess 26 recent open-sourced and commercial models using our benchmark. The findings highlight pronounced performance gaps in recognizing objects in NEMO and reveal distinct answer preferences across different models. Although stronger vision encoders improve performance, MLLMs still lag behind standalone vision encoders. Interestingly, scaling up the model size does not consistently yield better outcomes, as deeper analysis reveals that larger LLMs can weaken vision encoders during fine-tuning. These insights shed light on critical limitations in current MLLMs and suggest potential pathways toward developing more versatile and resilient multimodal models.

[Arxiv](https://arxiv.org/abs/2411.17794)