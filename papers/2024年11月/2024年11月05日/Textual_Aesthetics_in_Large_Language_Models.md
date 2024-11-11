# 大型语言模型中的文本美学

发布时间：2024年11月05日

`LLM应用` `图像生成` `文本美学`

> Textual Aesthetics in Large Language Models

# 摘要

> 图像美学是图像生成领域的一个关键指标。然而，文本美学尚未得到充分探索。随着大型语言模型（LLM）的广泛应用，以前的工作主要集中在内容的正确性和响应的有用性上。尽管如此，为LLM提供具有文本美学的响应也是一个重要因素，它可以提供更清晰的布局，并确保内容具有更大的一致性和连贯性。在这项工作中，我们引入了一个用于美学修饰的管道，并帮助构建了一个名为TexAes的文本美学数据集。我们提出了一种基于直接偏好优化的文本美学驱动的微调方法，称为TAPO，它利用文本美学而不影响内容的正确性。此外，我们分别基于文本和图像分析开发了两种用于文本美学的评估方法。我们的实验表明，使用文本美学数据并采用TAPO微调方法不仅提高了美学分数，而且在诸如AlpacalEval和Anera-hard等一般评估数据集上提高了性能。

> Image aesthetics is a crucial metric in the field of image generation. However, textual aesthetics has not been sufficiently explored. With the widespread application of large language models (LLMs), previous work has primarily focused on the correctness of content and the helpfulness of responses. Nonetheless, providing responses with textual aesthetics is also an important factor for LLMs, which can offer a cleaner layout and ensure greater consistency and coherence in content. In this work, we introduce a pipeline for aesthetics polishing and help construct a textual aesthetics dataset named TexAes. We propose a textual aesthetics-powered fine-tuning method based on direct preference optimization, termed TAPO, which leverages textual aesthetics without compromising content correctness. Additionally, we develop two evaluation methods for textual aesthetics based on text and image analysis, respectively. Our experiments demonstrate that using textual aesthetics data and employing the TAPO fine-tuning method not only improves aesthetic scores but also enhances performance on general evaluation datasets such as AlpacalEval and Anera-hard.

[Arxiv](https://arxiv.org/abs/2411.02930)