# R2GenCSR：利用大型语言模型，为X射线医学报告生成精选上下文样本

发布时间：2024年08月19日

`LLM应用` `人工智能`

> R2GenCSR: Retrieving Context Samples for Large Language Model based X-ray Medical Report Generation

# 摘要

> 借鉴大型语言模型的成功经验，现有X射线医学报告生成方法尝试借助大型模型提升性能。这些方法通常采用Transformer提取X射线图像的视觉特征，再将其输入LLM生成文本。然而，如何提取更有效的信息以优化LLM的最终结果，以及视觉Transformer带来的高计算复杂度，都是亟需解决的问题。为此，我们提出了一种新颖的上下文引导高效X射线医学报告生成框架。该框架采用Mamba作为视觉骨干，其线性复杂度下的性能可与强大的Transformer相媲美。在训练阶段，我们通过上下文检索，利用正负相关样本来强化特征表示和判别学习。最终，结合视觉令牌、上下文信息和提示语句，LLM能够生成高质量的医学报告。在IU-Xray、MIMIC-CXR和CheXpert Plus三个数据集上的广泛实验，充分证明了我们模型的有效性。相关源代码将发布于\url{https://github.com/Event-AHU/Medical_Image_Analysis}。

> Inspired by the tremendous success of Large Language Models (LLMs), existing X-ray medical report generation methods attempt to leverage large models to achieve better performance. They usually adopt a Transformer to extract the visual features of a given X-ray image, and then, feed them into the LLM for text generation. How to extract more effective information for the LLMs to help them improve final results is an urgent problem that needs to be solved. Additionally, the use of visual Transformer models also brings high computational complexity. To address these issues, this paper proposes a novel context-guided efficient X-ray medical report generation framework. Specifically, we introduce the Mamba as the vision backbone with linear complexity, and the performance obtained is comparable to that of the strong Transformer model. More importantly, we perform context retrieval from the training set for samples within each mini-batch during the training phase, utilizing both positively and negatively related samples to enhance feature representation and discriminative learning. Subsequently, we feed the vision tokens, context information, and prompt statements to invoke the LLM for generating high-quality medical reports. Extensive experiments on three X-ray report generation datasets (i.e., IU-Xray, MIMIC-CXR, CheXpert Plus) fully validated the effectiveness of our proposed model. The source code of this work will be released on \url{https://github.com/Event-AHU/Medical_Image_Analysis}.

[Arxiv](https://arxiv.org/abs/2408.09743)