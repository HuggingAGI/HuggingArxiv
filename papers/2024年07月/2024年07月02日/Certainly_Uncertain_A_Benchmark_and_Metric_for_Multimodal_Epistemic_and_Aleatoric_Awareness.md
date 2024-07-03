# 探索不确定性：多模态认知与偶然性意识的评估基准与度量

发布时间：2024年07月02日

`LLM理论` `人工智能` `计算机视觉`

> Certainly Uncertain: A Benchmark and Metric for Multimodal Epistemic and Aleatoric Awareness

# 摘要

> AI系统的真实可靠性建立在对知识与推理中必然存在的不确定性的认识上。本文精心构建了视觉-语言AI系统的不确定性分类，细分为信息不足的认知不确定性和本质难测的偶然不确定性，并深入探索其细分领域。据此，我们打造了CertainlyUncertain数据集，内含178K对比式VQA样本，通过图像修复与语言模型提示，巧妙地将可答问题转化为不可答。同时，我们创新性地提出了置信度加权准确率这一新指标，有效结合了准确性与校准误差，旨在弥补传统指标的缺陷。

> The ability to acknowledge the inevitable uncertainty in their knowledge and reasoning is a prerequisite for AI systems to be truly truthful and reliable. In this paper, we present a taxonomy of uncertainty specific to vision-language AI systems, distinguishing between epistemic uncertainty (arising from a lack of information) and aleatoric uncertainty (due to inherent unpredictability), and further explore finer categories within. Based on this taxonomy, we synthesize a benchmark dataset, CertainlyUncertain, featuring 178K visual question answering (VQA) samples as contrastive pairs. This is achieved by 1) inpainting images to make previously answerable questions into unanswerable ones; and 2) using image captions to prompt large language models for both answerable and unanswerable questions. Additionally, we introduce a new metric confidence-weighted accuracy, that is well correlated with both accuracy and calibration error, to address the shortcomings of existing metrics.

[Arxiv](https://arxiv.org/abs/2407.01942)