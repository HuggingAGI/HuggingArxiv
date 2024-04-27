# 多模态上下文内学习的成功之道是什么？

发布时间：2024年04月25日

`分类：LLM应用` `人工智能` `多模态学习`

> What Makes Multimodal In-Context Learning Work?

# 摘要

> 大型语言模型在多样化任务上展现了非凡的成效，它们能够通过少量示例的上下文学习（ICL）迅速掌握新技能。本研究构建了一个深入的框架，旨在探索大型多模态模型中的多模态ICL（M-ICL）。我们评估了顶尖的开源多模态模型（如IDEFICS、OpenFlamingo）以及一系列多模态任务。研究发现包括：（1）M-ICL主要依赖于文本驱动机制，图像模态的影响微乎其微。（2）采用高级ICL策略（例如RICES）时，M-ICL的性能并不超越基于上下文示例多数投票的简单策略。此外，我们还发现了M-ICL的几个潜在偏见和限制，这些在实际应用前需要被充分考虑。相关代码已在 https://gitlab.com/folbaeni/multimodal-icl 上公开。

> Large Language Models have demonstrated remarkable performance across various tasks, exhibiting the capacity to swiftly acquire new skills, such as through In-Context Learning (ICL) with minimal demonstration examples. In this work, we present a comprehensive framework for investigating Multimodal ICL (M-ICL) in the context of Large Multimodal Models. We consider the best open-source multimodal models (e.g., IDEFICS, OpenFlamingo) and a wide range of multimodal tasks. Our study unveils several noteworthy findings: (1) M-ICL primarily relies on text-driven mechanisms, showing little to no influence from the image modality. (2) When used with advanced-ICL strategy (like RICES), M-ICL is not better than a simple strategy based on majority voting over context examples. Moreover, we identify several biases and limitations of M-ICL that warrant consideration prior to deployment. Code available at https://gitlab.com/folbaeni/multimodal-icl

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/image.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/remove_image_radar.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/remove_modality_normalized_full.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/remove_question_radar.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/ngrams.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_diff_bar.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_no_modality_radar_image.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_vqa_bar.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_oracle_radar.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/coco_similarity_rouge.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/similarity_vqa_final.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/coco_vqa_repetition_avanced.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/remove_modality_full.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_key_full.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_reverse_full.png)

![多模态上下文内学习的成功之道是什么？](../../../paper_images/2404.15736/rices_no_image_full.png)

[Arxiv](https://arxiv.org/abs/2404.15736)