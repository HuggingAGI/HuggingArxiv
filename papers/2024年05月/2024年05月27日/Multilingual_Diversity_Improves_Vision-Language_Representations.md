# 多语言的丰富性增强了视觉与语言的表达能力

发布时间：2024年05月27日

`多模态学习

这篇论文主要探讨了如何通过引入更多非英语的多模态数据来提升模型的性能，特别是在视觉任务中。研究者通过翻译和重新筛选网络爬取的多语言图文对，增加了训练集中多语言数据的比例，并在多个测试基准上展示了性能的提升。这一研究强调了多元文化和多语言数据在提升模型全面能力方面的重要性。因此，这篇论文更符合多模态学习的分类，因为它关注的是如何利用多语言数据来改进模型的多模态学习能力，而不是直接涉及Agent、RAG、LLM应用或LLM理论。` `多模态学习` `数据集筛选`

> Multilingual Diversity Improves Vision-Language Representations

# 摘要

> 网络爬取的大量图文数据集为多模态学习的发展奠定了基石。这些数据集原本是为了让模型在标准视觉测试中表现出色，但许多测试已证实偏向英语（如ImageNet）。因此，现有的数据筛选方法偏爱英语图文对，忽视了许多非英语的有价值样本。我们的研究对此提出了质疑。多语言数据因其能够揭示文化特色概念且以独特视角展现常见事物而显得尤为珍贵。我们系统地研究了在英语视觉任务中引入更多非英语样本的益处。通过将网络爬取的多语言图文对翻译成英语并重新筛选，我们提升了训练集中多语言数据的比例。在此基础上预训练的模型在ImageNet、ImageNet分布变化、图文检索以及DataComp基准的38项任务中均超越了仅使用英语或英语主导的数据集。在地理分布广泛的GeoDE任务上，我们也观察到所有地区的性能提升，尤其是非洲地区。此外，我们通过定量分析证实，英语与非英语数据在图像和翻译文本空间中存在显著差异。我们期望这些发现能够鼓励未来的研究更加重视多元文化和多语言数据的融合，不仅在处理非英语或地理多样性任务时，更在于全面提升模型的能力。

> Massive web-crawled image-text datasets lay the foundation for recent progress in multimodal learning. These datasets are designed with the goal of training a model to do well on standard computer vision benchmarks, many of which, however, have been shown to be English-centric (e.g., ImageNet). Consequently, existing data curation techniques gravitate towards using predominantly English image-text pairs and discard many potentially useful non-English samples. Our work questions this practice. Multilingual data is inherently enriching not only because it provides a gateway to learn about culturally salient concepts, but also because it depicts common concepts differently from monolingual data. We thus conduct a systematic study to explore the performance benefits of using more samples of non-English origins with respect to English vision tasks. By translating all multilingual image-text pairs from a raw web crawl to English and re-filtering them, we increase the prevalence of (translated) multilingual data in the resulting training set. Pre-training on this dataset outperforms using English-only or English-dominated datasets on ImageNet, ImageNet distribution shifts, image-English-text retrieval and on average across 38 tasks from the DataComp benchmark. On a geographically diverse task like GeoDE, we also observe improvements across all regions, with the biggest gain coming from Africa. In addition, we quantitatively show that English and non-English data are significantly different in both image and (translated) text space. We hope that our findings motivate future work to be more intentional about including multicultural and multilingual data, not just when non-English or geographically diverse tasks are involved, but to enhance model capabilities at large.

[Arxiv](https://arxiv.org/abs/2405.16915)