# FADE：借助大型视觉-语言模型，实现少样本/零样本的异常检测引擎

发布时间：2024年08月31日

`LLM应用` `制造业` `质量控制`

> FADE: Few-shot/zero-shot Anomaly Detection Engine using Large Vision-Language Model

# 摘要

> 在制造业中，自动图像异常检测对质量检查至关重要。传统方法需要大量正常样本训练模型，但在实际应用中，零-/少-shot异常检测更为常见，这带来了挑战。近期，大型视觉-语言模型虽在多种任务中表现出色，但并非专为异常检测设计。为此，我们提出FADE引擎，利用CLIP模型并进行调整，以适应工业异常检测。我们通过改进CLIP的多尺度图像块嵌入和自动生成相关文本提示，提升了语言引导的异常分割效果。同时，结合查询和参考图像的视觉信息，进一步优化了零-shot和少-shot异常检测性能。在MVTec-AD和VisA数据集上，FADE在异常分割任务中表现卓越，零-shot和1-normal-shot的像素AUROC分别达到89.6%（91.5%）和95.4%（97.5%）。代码已公开，详见https://github.com/BMVC-FADE/BMVC-FADE。

> Automatic image anomaly detection is important for quality inspection in the manufacturing industry. The usual unsupervised anomaly detection approach is to train a model for each object class using a dataset of normal samples. However, a more realistic problem is zero-/few-shot anomaly detection where zero or only a few normal samples are available. This makes the training of object-specific models challenging. Recently, large foundation vision-language models have shown strong zero-shot performance in various downstream tasks. While these models have learned complex relationships between vision and language, they are not specifically designed for the tasks of anomaly detection. In this paper, we propose the Few-shot/zero-shot Anomaly Detection Engine (FADE) which leverages the vision-language CLIP model and adjusts it for the purpose of industrial anomaly detection. Specifically, we improve language-guided anomaly segmentation 1) by adapting CLIP to extract multi-scale image patch embeddings that are better aligned with language and 2) by automatically generating an ensemble of text prompts related to industrial anomaly detection. 3) We use additional vision-based guidance from the query and reference images to further improve both zero-shot and few-shot anomaly detection. On the MVTec-AD (and VisA) dataset, FADE outperforms other state-of-the-art methods in anomaly segmentation with pixel-AUROC of 89.6% (91.5%) in zero-shot and 95.4% (97.5%) in 1-normal-shot. Code is available at https://github.com/BMVC-FADE/BMVC-FADE.

[Arxiv](https://arxiv.org/abs/2409.00556)