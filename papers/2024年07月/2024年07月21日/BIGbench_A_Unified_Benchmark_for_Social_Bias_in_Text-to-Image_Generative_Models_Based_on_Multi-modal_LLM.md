# BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准

发布时间：2024年07月21日

`LLM应用` `人工智能` `图像生成`

> BIGbench: A Unified Benchmark for Social Bias in Text-to-Image Generative Models Based on Multi-modal LLM

# 摘要

> 随着文本到图像（T2I）生成模型在创造复杂高品质图像方面的能力日益增强，其输出中的社会偏见问题也日益凸显，尤其是在人类图像生成领域。尽管社会学研究已对偏见进行了系统分类，但现有T2I模型研究常混淆不同偏见类型，阻碍了方法进步。为此，我们推出了BIGbench，这是一个专为图像生成偏见设计的统一基准，包含精心构建的数据集。BIGbench独树一帜，将复杂偏见细分为四个评估维度：偏见显现、可见性、获得属性和受保护属性。同时，它采用尖端的多模态大型语言模型（MLLM），实现自动化高精度评估。我们利用BIGbench对近期八个通用T2I模型及三种去偏见技术进行了评估，并辅以人类评估，验证了BIGbench在图像匹配与偏见识别方面的成效。研究还开拓了新的偏见研究领域，如无关受保护属性的副作用及蒸馏技术。我们的数据集与基准面向研究社区开放，确保研究的可重复性。

> Text-to-Image (T2I) generative models are becoming more crucial in terms of their ability to generate complex and high-quality images, which also raises concerns about the social biases in their outputs, especially in human generation. Sociological research has established systematic classifications of bias; however, existing research of T2I models often conflates different types of bias, hindering the progress of these methods. In this paper, we introduce BIGbench, a unified benchmark for Biases of Image Generation with a well-designed dataset. In contrast to existing benchmarks, BIGbench classifies and evaluates complex biases into four dimensions: manifestation of bias, visibility of bias, acquired attributes, and protected attributes. Additionally, BIGbench applies advanced multi-modal large language models (MLLM), achieving fully automated evaluation while maintaining high accuracy. We apply BIGbench to evaluate eight recent general T2I models and three debiased methods. We also conduct human evaluation, whose results demonstrated the effectiveness of BIGbench in aligning images and identifying various biases. Besides, our study also revealed new research directions about biases, including the side-effect of irrelevant protected attributes and distillation. Our dataset and benchmark is openly accessible to the research community to ensure the reproducibility.

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/prompt_portion.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/prompt_construct.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/metric.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/cul_result.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/attractive.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/asian2.png)

![BIGbench：一个针对多模态LLM中文本到图像生成模型社会偏见的统一评估基准](../../../paper_images/2407.15240/debiasing2.png)

[Arxiv](https://arxiv.org/abs/2407.15240)