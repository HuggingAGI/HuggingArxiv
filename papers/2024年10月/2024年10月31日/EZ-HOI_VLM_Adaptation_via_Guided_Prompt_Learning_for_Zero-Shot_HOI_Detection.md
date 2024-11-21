# EZ-HOI：借助引导提示学习实现零样本 HOI 检测的 VLM 适配

发布时间：2024年10月31日

`LLM应用` `计算机视觉` `人-物交互检测`

> EZ-HOI: VLM Adaptation via Guided Prompt Learning for Zero-Shot HOI Detection

# 摘要

> 在零样本环境下检测人-物交互（HOI），模型得应对未曾见过的类别，这颇具挑战。现有的那些依赖将视觉编码器与大型视觉语言模型（VLMs）对齐来利用 VLMs 丰富知识的方法，需要庞大且计算开销高的模型，还面临训练难题。用提示学习来调整 VLMs 提供了不同于直接对齐的选择。但在特定任务数据集上进行微调，常导致对可见类的过拟合以及在不可见类上表现不佳，毕竟没有不可见类的标签。为应对这些挑战，我们推出了一个新颖的基于提示学习的高效零样本 HOI 检测（EZ-HOI）框架。首先，我们为可学习提示引入大型语言模型（LLM）和 VLM 引导，融合详细的 HOI 描述与视觉语义，让 VLMs 适配 HOI 任务。然而，由于训练数据集只含可见类标签，在这类数据集上微调 VLMs 往往会为可见类优化可学习提示，而非不可见类。所以，我们借助相关可见类的信息为不可见类设计提示学习，并利用 LLM 突显不可见类与相关可见类的差异。在基准数据集上的定量评估显示，我们的 EZ-HOI 在各类零样本设定中都达到了领先水平，与现有方法相比，可训练参数仅为 10.35％至 33.95％。代码可在 https://github.com/ChelsieLei/EZ-HOI 获取。

> Detecting Human-Object Interactions (HOI) in zero-shot settings, where models must handle unseen classes, poses significant challenges. Existing methods that rely on aligning visual encoders with large Vision-Language Models (VLMs) to tap into the extensive knowledge of VLMs, require large, computationally expensive models and encounter training difficulties. Adapting VLMs with prompt learning offers an alternative to direct alignment. However, fine-tuning on task-specific datasets often leads to overfitting to seen classes and suboptimal performance on unseen classes, due to the absence of unseen class labels. To address these challenges, we introduce a novel prompt learning-based framework for Efficient Zero-Shot HOI detection (EZ-HOI). First, we introduce Large Language Model (LLM) and VLM guidance for learnable prompts, integrating detailed HOI descriptions and visual semantics to adapt VLMs to HOI tasks. However, because training datasets contain seen-class labels alone, fine-tuning VLMs on such datasets tends to optimize learnable prompts for seen classes instead of unseen ones. Therefore, we design prompt learning for unseen classes using information from related seen classes, with LLMs utilized to highlight the differences between unseen and related seen classes. Quantitative evaluations on benchmark datasets demonstrate that our EZ-HOI achieves state-of-the-art performance across various zero-shot settings with only 10.35% to 33.95% of the trainable parameters compared to existing methods. Code is available at https://github.com/ChelsieLei/EZ-HOI.

[Arxiv](https://arxiv.org/abs/2410.23904)