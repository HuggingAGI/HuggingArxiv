# PosterLLaVa：利用大型语言模型打造统一的多模态布局生成器

发布时间：2024年06月04日

`LLM应用

这篇论文主要探讨了如何利用多模态大型语言模型（MLLM）来处理图形设计中的布局生成问题。通过结合结构化文本和视觉指令调整，该研究提出了一种新的框架，能够在特定的视觉和文本约束下生成布局。这种方法不仅在公共多模态布局生成基准上达到了最先进水平，而且还推出了两个新数据集来进一步验证其在实际应用中的效果。因此，这篇论文属于LLM应用类别，因为它展示了大型语言模型在特定应用领域（即图形设计）的实际应用和效果。` `图形设计` `自动化设计`

> PosterLLaVa: Constructing a Unified Multi-modal Layout Generator with LLM

# 摘要

> 布局生成是自动化图形设计的核心，它要求以美观且符合约束的方式安排多模态设计元素的位置和大小。传统方法要么在大规模应用中效率低下，要么无法灵活应对多变的设计需求。我们的研究提出了一种统一的框架，利用多模态大型语言模型（MLLM）来处理各种设计任务。我们的数据驱动方法通过结构化文本（JSON格式）和视觉指令调整，在特定视觉和文本约束下，包括用户定义的自然语言规范，生成布局。实验结果在公共多模态布局生成基准上达到了最先进水平，展示了我们方法的效力。鉴于现有数据集在反映真实世界图形设计复杂性方面的不足，我们推出了两个新数据集，针对更具挑战性的任务（用户约束生成和复杂海报设计），进一步证实了我们的模型在实际应用中的价值。这种方法以其高度的可访问性和适应性，极大地推动了大规模图形设计任务的自动化。代码和数据集将在https://github.com/posterllava/PosterLLaVA公开发布。

> Layout generation is the keystone in achieving automated graphic design, requiring arranging the position and size of various multi-modal design elements in a visually pleasing and constraint-following manner. Previous approaches are either inefficient for large-scale applications or lack flexibility for varying design requirements. Our research introduces a unified framework for automated graphic layout generation, leveraging the multi-modal large language model (MLLM) to accommodate diverse design tasks. In contrast, our data-driven method employs structured text (JSON format) and visual instruction tuning to generate layouts under specific visual and textual constraints, including user-defined natural language specifications. We conducted extensive experiments and achieved state-of-the-art (SOTA) performance on public multi-modal layout generation benchmarks, demonstrating the effectiveness of our method. Moreover, recognizing existing datasets' limitations in capturing the complexity of real-world graphic designs, we propose two new datasets for much more challenging tasks (user-constrained generation and complicated poster), further validating our model's utility in real-life settings. Marking by its superior accessibility and adaptability, this approach further automates large-scale graphic design tasks. The code and datasets will be publicly available on https://github.com/posterllava/PosterLLaVA.

![PosterLLaVa：利用大型语言模型打造统一的多模态布局生成器](../../../paper_images/2406.02884/x1.png)

![PosterLLaVa：利用大型语言模型打造统一的多模态布局生成器](../../../paper_images/2406.02884/x2.png)

![PosterLLaVa：利用大型语言模型打造统一的多模态布局生成器](../../../paper_images/2406.02884/x3.png)

![PosterLLaVa：利用大型语言模型打造统一的多模态布局生成器](../../../paper_images/2406.02884/x4.png)

[Arxiv](https://arxiv.org/abs/2406.02884)