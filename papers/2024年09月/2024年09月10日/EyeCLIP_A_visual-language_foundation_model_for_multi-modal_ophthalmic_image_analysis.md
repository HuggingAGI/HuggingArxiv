# EyeCLIP：一款专为多模态眼科图像分析打造的视觉-语言基础模型

发布时间：2024年09月10日

`LLM应用`

> EyeCLIP: A visual-language foundation model for multi-modal ophthalmic image analysis

# 摘要

> 早期发现青光眼、黄斑变性等眼病对预防视力丧失至关重要。虽然AI基础模型潜力巨大，但现有眼科模型多聚焦单一模态，而诊断眼病需多模态信息。我们提出EyeCLIP，利用277万张多模态眼科图像和部分文本数据，结合自监督重建、多模态对比学习等策略，学习多模态共享表示。在14个基准数据集上，EyeCLIP在疾病分类、视觉问答等任务中表现卓越，尤其在长尾场景中展现少样本甚至零样本能力，超越以往方法。

> Early detection of eye diseases like glaucoma, macular degeneration, and diabetic retinopathy is crucial for preventing vision loss. While artificial intelligence (AI) foundation models hold significant promise for addressing these challenges, existing ophthalmic foundation models primarily focus on a single modality, whereas diagnosing eye diseases requires multiple modalities. A critical yet often overlooked aspect is harnessing the multi-view information across various modalities for the same patient. Additionally, due to the long-tail nature of ophthalmic diseases, standard fully supervised or unsupervised learning approaches often struggle. Therefore, it is essential to integrate clinical text to capture a broader spectrum of diseases. We propose EyeCLIP, a visual-language foundation model developed using over 2.77 million multi-modal ophthalmology images with partial text data. To fully leverage the large multi-modal unlabeled and labeled data, we introduced a pretraining strategy that combines self-supervised reconstructions, multi-modal image contrastive learning, and image-text contrastive learning to learn a shared representation of multiple modalities. Through evaluation using 14 benchmark datasets, EyeCLIP can be transferred to a wide range of downstream tasks involving ocular and systemic diseases, achieving state-of-the-art performance in disease classification, visual question answering, and cross-modal retrieval. EyeCLIP represents a significant advancement over previous methods, especially showcasing few-shot, even zero-shot capabilities in real-world long-tail scenarios.

[Arxiv](https://arxiv.org/abs/2409.06644)