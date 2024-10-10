# MedImageInsight：一款专为通用医学影像设计的开源嵌入模型

发布时间：2024年10月09日

`LLM应用` `人工智能`

> MedImageInsight: An Open-Source Embedding Model for General Domain Medical Imaging

# 摘要

> 我们推出了 MedImageInsight，一款开源的医学影像嵌入模型。该模型在多样化的医学图像数据集上训练，涵盖 X 光、CT、MRI 等多种成像技术。评估结果显示，MedImageInsight 在分类、图像搜索和微调任务中表现卓越，达到或超越人类专家水平。例如，在 CT 3D 图像检索和胸部 X 光、皮肤病学、OCT 成像的疾病分类中，它均达到 SOTA。此外，在骨龄估计和多数领域的 AUC 上，MedImageInsight 表现出色。与 GPT-4o 相比，尽管在词汇指标上稍逊一筹，但在临床应用中更具优势。MedImageInsight 还能生成 ROC 曲线，调整敏感性和特异性，并通过图像搜索提供决策支持。在胸部 X 光的图像搜索评估中，它以显著优势胜过其他公开模型，并在 AI 公平性方面表现突出。我们期待 MedImageInsight 的发布能推动医学影像 AI 领域的共同进步。

> In this work, we present MedImageInsight, an open-source medical imaging embedding model. MedImageInsight is trained on medical images with associated text and labels across a diverse collection of domains, including X-Ray, CT, MRI, dermoscopy, OCT, fundus photography, ultrasound, histopathology, and mammography. Rigorous evaluations demonstrate MedImageInsight's ability to achieve state-of-the-art (SOTA) or human expert level performance across classification, image-image search, and fine-tuning tasks. Specifically, on public datasets, MedImageInsight achieves SOTA in CT 3D medical image retrieval, as well as SOTA in disease classification and search for chest X-ray, dermatology, and OCT imaging. Furthermore, MedImageInsight achieves human expert performance in bone age estimation (on both public and partner data), as well as AUC above 0.9 in most other domains. When paired with a text decoder, MedImageInsight achieves near SOTA level single image report findings generation with less than 10\% the parameters of other models. Compared to fine-tuning GPT-4o with only MIMIC-CXR data for the same task, MedImageInsight outperforms in clinical metrics, but underperforms on lexical metrics where GPT-4o sets a new SOTA. Importantly for regulatory purposes, MedImageInsight can generate ROC curves, adjust sensitivity and specificity based on clinical need, and provide evidence-based decision support through image-image search (which can also enable retrieval augmented generation). In an independent clinical evaluation of image-image search in chest X-ray, MedImageInsight outperformed every other publicly available foundation model evaluated by large margins (over 6 points AUC), and significantly outperformed other models in terms of AI fairness (across age and gender). We hope releasing MedImageInsight will help enhance collective progress in medical imaging AI research and development.

[Arxiv](https://arxiv.org/abs/2410.06542)