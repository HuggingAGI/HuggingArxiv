# FINEMATCH：面向细节的图像与文本错配检测及校正系统

发布时间：2024年04月22日

`LLM应用` `视觉识别`

> FINEMATCH: Aspect-based Fine-grained Image and Text Mismatch Detection and Correction

# 摘要

> 最新的大规模预训练进展催生了视觉-语言模型（VLMs），这些模型在理解和创造多模态内容上展现了非凡的才能。尽管VLMs在复杂推理上表现出色，但现有模型在捕捉图像和文本的组合信息方面仍面临挑战。为此，我们引入了FineMatch，一个新颖的基于方面的细粒度文本与图像匹配基准，专注于检测和修正文本与图像的不匹配问题。该基准旨在提升VLMs在细粒度匹配方面的组合能力。在这项任务中，模型需识别标题中的不匹配方面短语，确定其类别，并为可能存在0至3处不匹配的图像-文本对提出修正建议。我们设计了新的评估指标ITM-IoU来衡量模型在此任务上的表现，实验显示其与人工评估高度相关。我们还对主流VLMs进行了全面的实验分析，包括全监督和上下文学习场景。研究发现，通过FineMatch训练的模型在识别细微的文本与图像不匹配上更为精准。然而，即便是在多模态上下文学习方面表现出色的模型（如GPT-4V、Gemini Pro Vision），在细粒度组合图像与文本匹配分析上也存在不足。利用FineMatch，我们构建了一个系统，用于检测和修正文本到图像生成中的幻觉问题。

> Recent progress in large-scale pre-training has led to the development of advanced vision-language models (VLMs) with remarkable proficiency in comprehending and generating multimodal content. Despite the impressive ability to perform complex reasoning for VLMs, current models often struggle to effectively and precisely capture the compositional information on both the image and text sides. To address this, we propose FineMatch, a new aspect-based fine-grained text and image matching benchmark, focusing on text and image mismatch detection and correction. This benchmark introduces a novel task for boosting and evaluating the VLMs' compositionality for aspect-based fine-grained text and image matching. In this task, models are required to identify mismatched aspect phrases within a caption, determine the aspect's class, and propose corrections for an image-text pair that may contain between 0 and 3 mismatches. To evaluate the models' performance on this new task, we propose a new evaluation metric named ITM-IoU for which our experiments show a high correlation to human evaluation. In addition, we also provide a comprehensive experimental analysis of existing mainstream VLMs, including fully supervised learning and in-context learning settings. We have found that models trained on FineMatch demonstrate enhanced proficiency in detecting fine-grained text and image mismatches. Moreover, models (e.g., GPT-4V, Gemini Pro Vision) with strong abilities to perform multimodal in-context learning are not as skilled at fine-grained compositional image and text matching analysis. With FineMatch, we are able to build a system for text-to-image generation hallucination detection and correction.

[Arxiv](https://arxiv.org/abs/2404.14715)