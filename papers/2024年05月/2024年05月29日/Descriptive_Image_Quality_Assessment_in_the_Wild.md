# 自然环境下的图像质量描述性评估

发布时间：2024年05月29日

`LLM应用

理由：这篇论文主要讨论了基于视觉语言模型（VLMs）的图像质量评估（IQA）方法，特别是在构建了一个多功能IQA任务框架“野外描绘图像质量评估（DepictQA-Wild）”以及相关的数据集DQ-495K。这些工作都是针对具体的应用场景，即图像质量评估，并且利用了语言模型来提高评估的准确性和适应性。因此，这篇论文更符合LLM应用分类，因为它展示了如何将语言模型技术应用于特定的实际问题中。` `图像质量评估` `视觉语言模型`

> Descriptive Image Quality Assessment in the Wild

# 摘要

> 随着视觉语言模型（VLMs）技术的飞速进步，基于VLM的图像质量评估（IQA）正致力于通过语言精准描述图像质量，以契合人类表达并深入捕捉IQA任务的复杂性。尽管如此，现有方法仍未能满足实际应用的需求。一方面，过往研究往往局限于特定子任务或场景，难以适应现实世界应用的多样性；另一方面，受限于数据集的广度、规模及质量，其性能表现不尽人意。为此，我们推出了“野外描绘图像质量评估（DepictQA-Wild）”，该方法构建了一个多功能IQA任务框架，囊括了评估与比较、简述与详述、全参考与无参考等多种场景。我们采用了一种基于真实数据的数据集构建策略，大幅提升了数据质量，并在简短-详细联合框架下将数据集扩充至495K，命名为DQ-495K。此外，我们在训练中保持图像分辨率不变，有效应对分辨率相关的质量问题，并引入置信度评分机制，助力筛选低质量回应。实验结果表明，DepictQA-Wild在失真识别、即时评分及推理任务上均显著超越传统评分方法、先前的VLM-based IQA模型以及专有的GPT-4V。在评估网络下载图像和模型处理图像排名等实际应用场景中，我们的方法展现出明显优势。相关数据集和代码将在https://depictqa.github.io/depictqa-wild/公开发布。

> With the rapid advancement of Vision Language Models (VLMs), VLM-based Image Quality Assessment (IQA) seeks to describe image quality linguistically to align with human expression and capture the multifaceted nature of IQA tasks. However, current methods are still far from practical usage. First, prior works focus narrowly on specific sub-tasks or settings, which do not align with diverse real-world applications. Second, their performance is sub-optimal due to limitations in dataset coverage, scale, and quality. To overcome these challenges, we introduce Depicted image Quality Assessment in the Wild (DepictQA-Wild). Our method includes a multi-functional IQA task paradigm that encompasses both assessment and comparison tasks, brief and detailed responses, full-reference and non-reference scenarios. We introduce a ground-truth-informed dataset construction approach to enhance data quality, and scale up the dataset to 495K under the brief-detail joint framework. Consequently, we construct a comprehensive, large-scale, and high-quality dataset, named DQ-495K. We also retain image resolution during training to better handle resolution-related quality issues, and estimate a confidence score that is helpful to filter out low-quality responses. Experimental results demonstrate that DepictQA-Wild significantly outperforms traditional score-based methods, prior VLM-based IQA models, and proprietary GPT-4V in distortion identification, instant rating, and reasoning tasks. Our advantages are further confirmed by real-world applications including assessing the web-downloaded images and ranking model-processed images. Datasets and codes will be released in https://depictqa.github.io/depictqa-wild/.

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x1.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x2.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x3.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x4.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x5.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x6.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/org.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x7.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x8.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/word_cloud.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x9.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/example.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x10.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x11.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x12.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x13.png)

![自然环境下的图像质量描述性评估](../../../paper_images/2405.18842/x14.png)

[Arxiv](https://arxiv.org/abs/2405.18842)