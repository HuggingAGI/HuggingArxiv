# 借助情感与语义分析，精准评估图像标题的真实性与品质。

发布时间：2024年09月14日

`LLM应用` `计算机视觉`

> Evaluating authenticity and quality of image captions via sentiment and semantic analyses

# 摘要

> 深度学习的发展离不开大量标注数据的支持，尤其是在自然语言处理和计算机视觉领域。在图像到文本或图像到图像的任务中，模型可能会无意中从人类生成的图像描述中学习到情感。此外，描述的多样性和丰富性也会影响学习效果。虽然大规模数据集的标注通常依赖于众包或数据工作者，但评估这些训练数据的质量至关重要。本研究提出了一种专注于情感和语义丰富性的评估方法，并将其应用于包含约150K张图像的COCO-MS数据集。我们使用预训练模型从描述中提取情感分数和语义嵌入的变异性，并通过多元线性回归分析了这些指标与对象类别之间的关系。结果显示，大多数描述为中性，但约6%的描述表现出受特定对象类别影响的强烈情感。图像内描述的语义变异性较低且与对象类别无关。模型生成的描述中仅有不到1.5%表现出强烈情感，且这些情感不受对象类别影响，与人类生成的描述情感也不相关。这项研究展示了一种基于图像内容评估众包或工作者来源描述质量的方法。

> The growth of deep learning (DL) relies heavily on huge amounts of labelled data for tasks such as natural language processing and computer vision. Specifically, in image-to-text or image-to-image pipelines, opinion (sentiment) may be inadvertently learned by a model from human-generated image captions. Additionally, learning may be affected by the variety and diversity of the provided captions. While labelling large datasets has largely relied on crowd-sourcing or data-worker pools, evaluating the quality of such training data is crucial.
  This study proposes an evaluation method focused on sentiment and semantic richness. That method was applied to the COCO-MS dataset, comprising approximately 150K images with segmented objects and corresponding crowd-sourced captions. We employed pre-trained models (Twitter-RoBERTa-base and BERT-base) to extract sentiment scores and variability of semantic embeddings from captions. The relation of the sentiment score and semantic variability with object categories was examined using multiple linear regression. Results indicate that while most captions were neutral, about 6% of the captions exhibited strong sentiment influenced by specific object categories. Semantic variability of within-image captions remained low and uncorrelated with object categories. Model-generated captions showed less than 1.5% of strong sentiment which was not influenced by object categories and did not correlate with the sentiment of the respective human-generated captions. This research demonstrates an approach to assess the quality of crowd- or worker-sourced captions informed by image content.

[Arxiv](https://arxiv.org/abs/2409.09560)