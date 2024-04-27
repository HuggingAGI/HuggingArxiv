# 多模态上下文内学习为何有效？

发布时间：2024年04月25日

`LLM应用` `多模态学习` `人工智能`

> What Makes Multimodal In-Context Learning Work?

# 摘要

> 大型语言模型在多样化任务上展现了非凡的能力，能够通过极少量的示例迅速掌握新技能，这主要得益于上下文学习（ICL）。本研究构建了一个深入的框架，旨在探讨大型多模态模型中的多模态ICL（M-ICL）。我们评估了顶尖的开源多模态模型（如IDEFICS、OpenFlamingo）在一系列多模态任务上的表现。研究发现，M-ICL主要依赖文本驱动机制，图像模态的影响微乎其微。此外，采用高级ICL策略（例如RICES）时，M-ICL的性能并不超越简单的多数投票策略。我们还指出了M-ICL存在的一些偏见和限制，这些在实际应用前需要被充分考虑。相关代码已在 https://gitlab.com/folbaeni/multimodal-icl 上公开。

> Large Language Models have demonstrated remarkable performance across various tasks, exhibiting the capacity to swiftly acquire new skills, such as through In-Context Learning (ICL) with minimal demonstration examples. In this work, we present a comprehensive framework for investigating Multimodal ICL (M-ICL) in the context of Large Multimodal Models. We consider the best open-source multimodal models (e.g., IDEFICS, OpenFlamingo) and a wide range of multimodal tasks. Our study unveils several noteworthy findings: (1) M-ICL primarily relies on text-driven mechanisms, showing little to no influence from the image modality. (2) When used with advanced-ICL strategy (like RICES), M-ICL is not better than a simple strategy based on majority voting over context examples. Moreover, we identify several biases and limitations of M-ICL that warrant consideration prior to deployment. Code available at https://gitlab.com/folbaeni/multimodal-icl

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/image.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/remove_image_radar.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/remove_modality_normalized_full.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/remove_question_radar.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/ngrams.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_diff_bar.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_no_modality_radar_image.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_vqa_bar.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_oracle_radar.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/coco_similarity_rouge.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/similarity_vqa_final.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/coco_vqa_repetition_avanced.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/remove_modality_full.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_key_full.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_reverse_full.png)

![多模态上下文内学习为何有效？](../../../paper_images/2404.15736/rices_no_image_full.png)

[Arxiv](https://arxiv.org/abs/2404.15736)