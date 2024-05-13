# VLSM-Adapter：以轻巧之姿，高效微调视觉与语言的分割艺术

发布时间：2024年05月09日

`LLM应用

这篇论文介绍了一种名为VLSM-Adapter的新型轻量级适配器，用于微调视觉-语言分割模型（VLSMs），特别是在医学图像处理领域。该适配器能够在不更新预训练模型参数的情况下，通过变换器编码器对模型进行微调，从而显著降低计算需求和成本。这种方法对于资源受限的环境尤其有价值，并且其实验结果表明，VLSM-Adapter在保持高性能的同时，大大减少了可训练参数的数量。由于该工作聚焦于应用层面的模型优化和实际问题解决，因此它属于LLM应用类别。` `医疗影像` `模型微调`

> VLSM-Adapter: Finetuning Vision-Language Segmentation Efficiently with Lightweight Blocks

# 摘要

> 近期，通过将基础视觉-语言模型（VLMs）与大规模开放领域图像和文本对相结合，开发出了能够在推理时通过文本提示指导图像分割的视觉-语言分割模型（VLSMs）。若能构建出适用于医学图像的强大VLSMs，将极大助力医疗专家在需耗时描绘目标结构的临床任务中。然而，由于医学图像标注数据稀缺，VLSMs通常需对预训练于自然图像数据集的模型进行微调，这一过程耗费资源且成本高昂。为此，我们推出了VLSM-Adapter，一种新型轻量级适配器，它能在不更新预训练模型参数的情况下，通过变换器编码器对视觉-语言分割模型进行微调，大幅降低计算需求。实验证明，VLSM-Adapter以仅300万个可训练参数，便超越了现有技术水平，并与端到端微调的效果相媲美。源代码已公开发布于GitHub：https://github.com/naamiinepal/vlsm-adapter。

> Foundation Vision-Language Models (VLMs) trained using large-scale open-domain images and text pairs have recently been adapted to develop Vision-Language Segmentation Models (VLSMs) that allow providing text prompts during inference to guide image segmentation. If robust and powerful VLSMs can be built for medical images, it could aid medical professionals in many clinical tasks where they must spend substantial time delineating the target structure of interest. VLSMs for medical images resort to fine-tuning base VLM or VLSM pretrained on open-domain natural image datasets due to fewer annotated medical image datasets; this fine-tuning is resource-consuming and expensive as it usually requires updating all or a significant fraction of the pretrained parameters. Recently, lightweight blocks called adapters have been proposed in VLMs that keep the pretrained model frozen and only train adapters during fine-tuning, substantially reducing the computing resources required. We introduce a novel adapter, VLSM-Adapter, that can fine-tune pretrained vision-language segmentation models using transformer encoders. Our experiments in widely used CLIP-based segmentation models show that with only 3 million trainable parameters, the VLSM-Adapter outperforms state-of-the-art and is comparable to the upper bound end-to-end fine-tuning. The source code is available at: https://github.com/naamiinepal/vlsm-adapter.

![VLSM-Adapter：以轻巧之姿，高效微调视觉与语言的分割艺术](../../../paper_images/2405.06196/architecture)

![VLSM-Adapter：以轻巧之姿，高效微调视觉与语言的分割艺术](../../../paper_images/2405.06196/adapter_variants)

![VLSM-Adapter：以轻巧之姿，高效微调视觉与语言的分割艺术](../../../paper_images/2405.06196/spider_adapter)

![VLSM-Adapter：以轻巧之姿，高效微调视觉与语言的分割艺术](../../../paper_images/2405.06196/qualitative-analysis)

[Arxiv](https://arxiv.org/abs/2405.06196)