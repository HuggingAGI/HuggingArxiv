# MC-Bench：MLLM 时代下的多上下文视觉定位基准

发布时间：2024年10月16日

`LLM应用` `人工智能` `计算机视觉`

> MC-Bench: A Benchmark for Multi-Context Visual Grounding in the Era of MLLMs

# 摘要

> 尽管多模态大型语言模型 (MLLMs) 在视觉-语言理解方面表现出色，并展现出成为通用助手的潜力，但它们在处理多张图像中的实例级视觉-语言问题时仍需深入探索。为此，我们提出了一项新的视觉定位任务——多上下文视觉定位，旨在根据开放式文本提示在多张图像中定位目标实例。为支持这一研究，我们构建了 MC-Bench 数据集，包含 2K 个高质量手工标注样本，涵盖 20 种实际技能。我们评估了 20 多个最先进的 MLLMs 和基础模型，发现现有 MLLMs 在所有指标上与人类存在显著差距。此外，专门针对单张图像训练的 MLLMs 在多图像场景中表现不佳，而结合先进 MLLM 和检测器的简单基线则显著优于传统端到端模型。我们希望通过 MC-Bench 和这些发现，激发社区进一步挖掘 MLLMs 在多图像上下文中的潜力。项目页面：https://xuyunqiu.github.io/MC-Bench/。

> While multimodal large language models (MLLMs) have demonstrated extraordinary vision-language understanding capabilities and shown potential to serve as general-purpose assistants, their abilities to solve instance-level visual-language problems beyond a single image warrant further exploration. In order to assess these unproven abilities of MLLMs, this paper proposes a new visual grounding task called multi-context visual grounding, which aims to localize instances of interest across multiple images based on open-ended text prompts. To facilitate this research, we meticulously construct a new dataset MC-Bench for benchmarking the visual grounding capabilities of MLLMs. MC-Bench features 2K high-quality and manually annotated samples, consisting of instance-level labeled image pairs and corresponding text prompts that indicate the target instances in the images. In total, there are three distinct styles of text prompts, covering 20 practical skills. We benchmark over 20 state-of-the-art MLLMs and foundation models with potential multi-context visual grounding capabilities. Our evaluation reveals a non-trivial performance gap between existing MLLMs and humans across all metrics. We also observe that existing MLLMs typically outperform foundation models without LLMs only on image-level metrics, and the specialist MLLMs trained on single images often struggle to generalize to multi-image scenarios. Moreover, a simple stepwise baseline integrating advanced MLLM and a detector can significantly surpass prior end-to-end MLLMs. We hope our MC-Bench and empirical findings can encourage the research community to further explore and enhance the untapped potentials of MLLMs in instance-level tasks, particularly in multi-image contexts. Project page: https://xuyunqiu.github.io/MC-Bench/.

[Arxiv](https://arxiv.org/abs/2410.12332)