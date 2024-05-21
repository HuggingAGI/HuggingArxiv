# 借助级联视觉语言模型提升细粒度图像分类精度

发布时间：2024年05月18日

`RAG

理由：这篇论文讨论了在零/少样本场景下细粒度图像分类的挑战，并提出了CascadeVLM框架，该框架通过挖掘大型视觉-语言模型（LVLMs）的深层知识来解决这一问题。这种方法涉及到视觉-语言模型的应用和改进，特别是在细粒度图像分类方面的应用，因此属于RAG（Retrieval-Augmented Generation）分类，即通过检索增强生成模型来提高性能。这与Agent或LLM理论的分类不符，因为Agent通常涉及自主决策和行动，而LLM理论更多关注语言模型的理论基础和算法。同时，虽然它涉及LLM的应用，但更侧重于通过检索增强的方法来改进模型，因此RAG分类更为合适。` `图像分类` `机器学习`

> Enhancing Fine-Grained Image Classifications via Cascaded Vision Language Models

# 摘要

> 在零/少样本场景下的细粒度图像分类对视觉-语言模型（如CLIP）构成挑战，因其预训练中缺乏细粒度分类的监督信号，难以区分语义相似的类别。CascadeVLM框架通过挖掘大型视觉-语言模型（LVLMs）的深层知识，突破了这一局限。实验显示，CascadeVLM在多个数据集上超越了现有模型，尤其在斯坦福汽车数据集上达到85.6%的零样本准确率。分析表明，LVLMs对CLIP难以判断的图像预测更为准确，显著提升了整体性能。我们的框架揭示了VLMs与LVLMs整合的新途径，为细粒度图像分类提供了高效解决方案。

> Fine-grained image classification, particularly in zero/few-shot scenarios, presents a significant challenge for vision-language models (VLMs), such as CLIP. These models often struggle with the nuanced task of distinguishing between semantically similar classes due to limitations in their pre-trained recipe, which lacks supervision signals for fine-grained categorization. This paper introduces CascadeVLM, an innovative framework that overcomes the constraints of previous CLIP-based methods by effectively leveraging the granular knowledge encapsulated within large vision-language models (LVLMs). Experiments across various fine-grained image datasets demonstrate that CascadeVLM significantly outperforms existing models, specifically on the Stanford Cars dataset, achieving an impressive 85.6% zero-shot accuracy. Performance gain analysis validates that LVLMs produce more accurate predictions for challenging images that CLIPs are uncertain about, bringing the overall accuracy boost. Our framework sheds light on a holistic integration of VLMs and LVLMs for effective and efficient fine-grained image classification.

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/flowerbase.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/cascadeVLM.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/perf_analysis.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/entropy_threshold.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/reasoning.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/casestudy.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/clipvitb32-trending.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/clipvitb16-trending.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/clipvitl14-trending.png)

![借助级联视觉语言模型提升细粒度图像分类精度](../../../paper_images/2405.11301/error_analysis.png)

[Arxiv](https://arxiv.org/abs/2405.11301)