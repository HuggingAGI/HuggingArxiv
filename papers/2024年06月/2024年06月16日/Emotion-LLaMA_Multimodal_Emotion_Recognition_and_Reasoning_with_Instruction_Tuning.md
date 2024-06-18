# 情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理

发布时间：2024年06月16日

`LLM应用

理由：这篇论文主要介绍了Emotion-LLaMA模型，这是一个多模态大型语言模型，专门设计用于情感识别和推理。它通过整合音频、视觉和文本信息，并在情感识别任务中展示了优越的性能。这种模型的发展和应用直接关联到大型语言模型的实际应用领域，特别是在情感感知和分析方面。因此，它属于LLM应用分类。` `人机交互`

> Emotion-LLaMA: Multimodal Emotion Recognition and Reasoning with Instruction Tuning

# 摘要

> 在人机交互、教育和咨询等领域，精准的情感感知至关重要。然而，传统单一模态方法难以捕捉现实世界中复杂多变的情感表达。现有的多模态大型语言模型（MLLMs）在整合音频和识别细微面部表情方面亦显不足。为此，我们推出了MERR数据集，包含28,618个粗粒度和4,487个细粒度标注样本，覆盖广泛情感类别，助力模型在多样场景中学习并应用于现实世界。同时，我们提出了Emotion-LLaMA模型，它通过专为情感设计的编码器，无缝融合音频、视觉和文本信息。通过特征对齐和指令调整的LLaMA模型，Emotion-LLaMA在情感识别和推理上大放异彩。评估结果显示，Emotion-LLaMA在多个指标上超越其他MLLMs，在EMER测试中Clue Overlap和Label Overlap得分领先，MER2023挑战赛中F1分数高达0.9036，DFEW数据集的零-shot评估中UAR和WAR均创下新高。

> Accurate emotion perception is crucial for various applications, including human-computer interaction, education, and counseling. However, traditional single-modality approaches often fail to capture the complexity of real-world emotional expressions, which are inherently multimodal. Moreover, existing Multimodal Large Language Models (MLLMs) face challenges in integrating audio and recognizing subtle facial micro-expressions. To address this, we introduce the MERR dataset, containing 28,618 coarse-grained and 4,487 fine-grained annotated samples across diverse emotional categories. This dataset enables models to learn from varied scenarios and generalize to real-world applications. Furthermore, we propose Emotion-LLaMA, a model that seamlessly integrates audio, visual, and textual inputs through emotion-specific encoders. By aligning features into a shared space and employing a modified LLaMA model with instruction tuning, Emotion-LLaMA significantly enhances both emotional recognition and reasoning capabilities. Extensive evaluations show Emotion-LLaMA outperforms other MLLMs, achieving top scores in Clue Overlap (7.83) and Label Overlap (6.25) on EMER, an F1 score of 0.9036 on MER2023 challenge, and the highest UAR (45.59) and WAR (59.37) in zero-shot evaluations on DFEW dataset.

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x1.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x2.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x3.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x4.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x5.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x6.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x7.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x8.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x9.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x10.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x11.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x14.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x15.png)

![情感之光：Emotion-LLaMA 借助指令调整，实现多模态情感识别与深度推理](../../../paper_images/2406.11161/x16.png)

[Arxiv](https://arxiv.org/abs/2406.11161)