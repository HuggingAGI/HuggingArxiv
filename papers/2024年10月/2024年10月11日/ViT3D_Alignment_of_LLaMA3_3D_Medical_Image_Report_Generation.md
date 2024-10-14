# ViT3D 与 LLaMA3 的 3D 医学图像报告生成对齐

发布时间：2024年10月11日

`LLM应用` `人工智能`

> ViT3D Alignment of LLaMA3: 3D Medical Image Report Generation

# 摘要

> 自动医疗报告生成 (MRG) 旨在从医学图像生成详细文本报告，已成为关键任务。MRG 系统通过减少报告撰写时间和精力，提升放射工作流程和诊断效率。我们提出一种新方法，利用多模态大型语言模型，采用 3D Vision Transformer (ViT3D) 处理 3D 扫描，并使用 Asclepius-Llama3-8B 生成文本报告。实验表明，我们的模型在 MRG 和视觉问答 (VQA) 任务中表现优异，通过小数据集调整模型，展示了 ViT3D 与 LLaMA3 的有效性。

> Automatic medical report generation (MRG), which aims to produce detailed text reports from medical images, has emerged as a critical task in this domain. MRG systems can enhance radiological workflows by reducing the time and effort required for report writing, thereby improving diagnostic efficiency. In this work, we present a novel approach for automatic MRG utilizing a multimodal large language model. Specifically, we employed the 3D Vision Transformer (ViT3D) image encoder introduced from M3D-CLIP to process 3D scans and use the Asclepius-Llama3-8B as the language model to generate the text reports by auto-regressive decoding. The experiment shows our model achieved an average Green score of 0.3 on the MRG task validation set and an average accuracy of 0.61 on the visual question answering (VQA) task validation set, outperforming the baseline model. Our approach demonstrates the effectiveness of the ViT3D alignment of LLaMA3 for automatic MRG and VQA tasks by tuning the model on a small dataset.

[Arxiv](https://arxiv.org/abs/2410.08588)