# PEVA-Net：一种用于零样本或少样本多视角3D形状识别的增强提示视图聚合网络。

发布时间：2024年04月29日

`分类：LLM应用` `计算机视觉` `机器学习`

> PEVA-Net: Prompt-Enhanced View Aggregation Network for Zero/Few-Shot Multi-View 3D Shape Recognition

# 摘要

> 大型视觉-语言模型显著提升了二维视觉识别在零样本/少样本场景下的性能。本文着眼于运用大型视觉-语言模型CLIP，针对基于多视图表示的零样本/少样本三维形状识别进行研究。核心挑战在于生成能够代表三维形状的多视图图像的区分性描述符，无论是在完全没有显式训练（零样本三维形状识别）还是只有少量数据训练（少样本三维形状识别）的情况下。我们发现这两个任务不仅相关，而且可以一并处理。具体而言，利用对零样本推断有效的描述符来指导少样本训练中的聚合描述符的调整，可以有效提升少样本学习的效果。因此，我们提出了增强型视图聚合网络（PEVA-Net），以同时应对零样本/少样本三维形状识别的挑战。在零样本场景下，我们提出利用候选类别构建的提示来增强多视图相关视觉特征的聚合。这样聚合得到的特征能够有效地用于零样本三维形状识别。而在少样本场景下，我们首先使用变换器编码器将视图相关视觉特征整合成全局描述符，并通过自我蒸馏策略，结合零样本描述符作为引导信号，通过特征蒸馏损失来调整编码器，从而显著提升少样本学习的效果。

> Large vision-language models have impressively promote the performance of 2D visual recognition under zero/few-shot scenarios. In this paper, we focus on exploiting the large vision-language model, i.e., CLIP, to address zero/few-shot 3D shape recognition based on multi-view representations. The key challenge for both tasks is to generate a discriminative descriptor of the 3D shape represented by multiple view images under the scenarios of either without explicit training (zero-shot 3D shape recognition) or training with a limited number of data (few-shot 3D shape recognition). We analyze that both tasks are relevant and can be considered simultaneously. Specifically, leveraging the descriptor which is effective for zero-shot inference to guide the tuning of the aggregated descriptor under the few-shot training can significantly improve the few-shot learning efficacy. Hence, we propose Prompt-Enhanced View Aggregation Network (PEVA-Net) to simultaneously address zero/few-shot 3D shape recognition. Under the zero-shot scenario, we propose to leverage the prompts built up from candidate categories to enhance the aggregation process of multiple view-associated visual features. The resulting aggregated feature serves for effective zero-shot recognition of the 3D shapes. Under the few-shot scenario, we first exploit a transformer encoder to aggregate the view-associated visual features into a global descriptor. To tune the encoder, together with the main classification loss, we propose a self-distillation scheme via a feature distillation loss by treating the zero-shot descriptor as the guidance signal for the few-shot descriptor. This scheme can significantly enhance the few-shot learning efficacy.

[Arxiv](https://arxiv.org/abs/2404.19168)