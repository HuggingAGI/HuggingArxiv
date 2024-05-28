# 多语言多样性增强视觉-语言表征

发布时间：2024年05月27日

`RAG

理由：这篇论文主要关注的是多模态学习中的数据集构建和性能提升，特别是通过整合多语言数据来丰富数据集并提高模型在特定任务上的表现。这与RAG（Retrieval-Augmented Generation）模型中利用多源数据增强生成模型的能力相吻合。虽然论文中提到了多语言数据的使用，但这更多是关于数据处理和模型训练的实践，而不是直接关于Agent的行为、LLM的应用或理论研究。因此，将其归类为RAG是合适的。` `多模态学习` `数据集增强`

> Multilingual Diversity Improves Vision-Language Representations

# 摘要

> 网络爬取的大量图像-文本数据集推动了多模态学习的进步，但这些数据集往往偏重英语，忽视了非英语资源的价值。我们的研究表明，多语言数据不仅能丰富文化知识，还能以独特视角展现常见概念。通过将网络爬取的多语言数据翻译并整合到英语数据集中，我们发现这种混合数据集在ImageNet等基准测试中表现更佳，尤其在地理多样性任务如GeoDE中，非洲地区的提升最为显著。此外，数据分析显示，英语与非英语数据在图像和文本层面存在显著差异。我们期望这些发现能鼓励未来研究更积极地融合多元文化和多语言数据，以全面提升模型性能。

> Massive web-crawled image-text datasets lay the foundation for recent progress in multimodal learning. These datasets are designed with the goal of training a model to do well on standard computer vision benchmarks, many of which, however, have been shown to be English-centric (e.g., ImageNet). Consequently, existing data curation techniques gravitate towards using predominantly English image-text pairs and discard many potentially useful non-English samples. Our work questions this practice. Multilingual data is inherently enriching not only because it provides a gateway to learn about culturally salient concepts, but also because it depicts common concepts differently from monolingual data. We thus conduct a systematic study to explore the performance benefits of using more samples of non-English origins with respect to English vision tasks. By translating all multilingual image-text pairs from a raw web crawl to English and re-filtering them, we increase the prevalence of (translated) multilingual data in the resulting training set. Pre-training on this dataset outperforms using English-only or English-dominated datasets on ImageNet, ImageNet distribution shifts, image-English-text retrieval and on average across 38 tasks from the DataComp benchmark. On a geographically diverse task like GeoDE, we also observe improvements across all regions, with the biggest gain coming from Africa. In addition, we quantitatively show that English and non-English data are significantly different in both image and (translated) text space. We hope that our findings motivate future work to be more intentional about including multicultural and multilingual data, not just when non-English or geographically diverse tasks are involved, but to enhance model capabilities at large.

[Arxiv](https://arxiv.org/abs/2405.16915)