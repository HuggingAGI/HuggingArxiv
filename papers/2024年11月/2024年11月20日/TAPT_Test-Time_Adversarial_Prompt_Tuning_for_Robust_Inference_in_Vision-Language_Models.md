# TAPT：视觉语言模型中用于实现稳健推理的测试时对抗提示调整

发布时间：2024年11月20日

`LLM应用` `计算机视觉` `模型安全`

> TAPT: Test-Time Adversarial Prompt Tuning for Robust Inference in Vision-Language Models

# 摘要

> 像 CLIP 这样的大型预训练视觉语言模型（VLMs）在各类下游任务中展现出绝佳的零样本泛化能力。然而，近期研究发现，CLIP 的推理性能会因微小的对抗性扰动而严重下降，特别是其视觉模态，这带来了重大的安全隐患。为降低这种脆弱性，本文提出了一种新颖的防御方法——测试时对抗提示调整（TAPT），以增强 CLIP 抵御视觉对抗攻击的推理鲁棒性。TAPT 属于测试时的防御手段，通过学习防御性的双模态（文本和视觉）提示来巩固 CLIP 的推理流程。具体来说，这是一种无监督方法，它为每个测试样本优化防御提示，方法是最小化多视图熵并对齐对抗清洁分布。我们在 11 个基准数据集（包含 ImageNet 及其他 10 个零样本数据集）上评估了 TAPT 的效果，结果显示，其将原始 CLIP 针对 AutoAttack（AA）的零样本对抗鲁棒性至少提升了 48.9%，同时在干净样本上基本维持了性能。此外，TAPT 在各种骨干网络中的表现均优于现有的对抗提示调整方法，平均鲁棒性提升至少 36.6%。

> Large pre-trained Vision-Language Models (VLMs) such as CLIP have demonstrated excellent zero-shot generalizability across various downstream tasks. However, recent studies have shown that the inference performance of CLIP can be greatly degraded by small adversarial perturbations, especially its visual modality, posing significant safety threats. To mitigate this vulnerability, in this paper, we propose a novel defense method called Test-Time Adversarial Prompt Tuning (TAPT) to enhance the inference robustness of CLIP against visual adversarial attacks. TAPT is a test-time defense method that learns defensive bimodal (textual and visual) prompts to robustify the inference process of CLIP. Specifically, it is an unsupervised method that optimizes the defensive prompts for each test sample by minimizing a multi-view entropy and aligning adversarial-clean distributions. We evaluate the effectiveness of TAPT on 11 benchmark datasets, including ImageNet and 10 other zero-shot datasets, demonstrating that it enhances the zero-shot adversarial robustness of the original CLIP by at least 48.9% against AutoAttack (AA), while largely maintaining performance on clean examples. Moreover, TAPT outperforms existing adversarial prompt tuning methods across various backbones, achieving an average robustness improvement of at least 36.6%.

[Arxiv](https://arxiv.org/abs/2411.13136)