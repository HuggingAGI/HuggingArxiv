# GradBias：揭秘文本到图像生成模型中词汇如何影响偏差

发布时间：2024年08月29日

`LLM应用` `人工智能` `图像处理`

> GradBias: Unveiling Word Influence on Bias in Text-to-Image Generative Models

# 摘要

> 随着文本到图像生成模型性能的提升和普及，确保其公平性和安全性变得尤为重要，以防止偏见的传播。本文提出了一种开放集合框架，无需预定义偏见即可识别、量化和解释偏见。该框架首先利用大型语言模型从标题中提出偏见，然后生成图像，最后通过视觉问答进行偏见评估。我们展示了两种框架变体：OpenBias 和 GradBias。OpenBias 能有效检测各种偏见，并与现有方法高度一致；GradBias 则揭示了中性词对偏见的显著影响，并超越了多个基线模型。详细代码可在 GitHub 上获取。

> Recent progress in Text-to-Image (T2I) generative models has enabled high-quality image generation. As performance and accessibility increase, these models are gaining significant attraction and popularity: ensuring their fairness and safety is a priority to prevent the dissemination and perpetuation of biases. However, existing studies in bias detection focus on closed sets of predefined biases (e.g., gender, ethnicity). In this paper, we propose a general framework to identify, quantify, and explain biases in an open set setting, i.e. without requiring a predefined set. This pipeline leverages a Large Language Model (LLM) to propose biases starting from a set of captions. Next, these captions are used by the target generative model for generating a set of images. Finally, Vision Question Answering (VQA) is leveraged for bias evaluation. We show two variations of this framework: OpenBias and GradBias. OpenBias detects and quantifies biases, while GradBias determines the contribution of individual prompt words on biases. OpenBias effectively detects both well-known and novel biases related to people, objects, and animals and highly aligns with existing closed-set bias detection methods and human judgment. GradBias shows that neutral words can significantly influence biases and it outperforms several baselines, including state-of-the-art foundation models. Code available here: https://github.com/Moreno98/GradBias.

[Arxiv](https://arxiv.org/abs/2408.16700)