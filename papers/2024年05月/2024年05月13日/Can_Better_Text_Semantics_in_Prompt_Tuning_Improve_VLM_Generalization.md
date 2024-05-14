# 优化提示调整中的文本语义，是否能增强视觉语言模型的泛化能力？这一问题引发了研究者的浓厚兴趣。

发布时间：2024年05月13日

`RAG

解释：这篇论文探讨了在视觉-语言模型中使用大型语言模型生成的类别描述来改进提示调优策略，以弥合图像与类别概念之间的鸿沟。这种方法涉及利用大型语言模型的能力来生成丰富的文本语义，从而提高模型的泛化能力。这与RAG（Retrieval-Augmented Generation）的概念相吻合，因为RAG模型结合了检索和生成的能力，以增强语言模型的性能。因此，这篇论文更倾向于RAG分类，而不是Agent、LLM应用或LLM理论。` `计算机视觉`

> Can Better Text Semantics in Prompt Tuning Improve VLM Generalization?

# 摘要

> 超越传统的视觉-语言模型微调，可学习的提示调优崭露头角，成为一种高效且有潜力的方法。然而，这一技术在实践中遇到了挑战：低样本训练导致过拟合，限制了其适应新类别或数据集的能力；同时，提示调优的效果受限于标签空间，尤其在大类别空间中表现不佳，暗示了图像与类别概念间的潜在鸿沟。本研究探索了更丰富的文本语义是否能弥合这一差距。我们提出了一种新颖的提示调优策略，它利用大型语言模型生成的类别描述，构建了图像与文本特征的细粒度描述视图，并通过对齐学习更泛化的提示。在11个基准数据集上的实验结果表明，我们的方法显著优于现有技术，取得了重大进步。

> Going beyond mere fine-tuning of vision-language models (VLMs), learnable prompt tuning has emerged as a promising, resource-efficient alternative. Despite their potential, effectively learning prompts faces the following challenges: (i) training in a low-shot scenario results in overfitting, limiting adaptability and yielding weaker performance on newer classes or datasets; (ii) prompt-tuning's efficacy heavily relies on the label space, with decreased performance in large class spaces, signaling potential gaps in bridging image and class concepts. In this work, we ask the question if better text semantics can help address these concerns. In particular, we introduce a prompt-tuning method that leverages class descriptions obtained from large language models (LLMs). Our approach constructs part-level description-guided views of both image and text features, which are subsequently aligned to learn more generalizable prompts. Our comprehensive experiments, conducted across 11 benchmark datasets, outperform established methods, demonstrating substantial improvements.

[Arxiv](https://arxiv.org/abs/2405.07921)