# EyeDiff：文本到图像的扩散模型提升了罕见眼病的诊断能力

发布时间：2024年11月15日

`LLM应用`

> EyeDiff: text-to-image diffusion model improves rare eye disease diagnosis

# 摘要

> 威胁视力的视网膜疾病愈发常见，给全球医疗保健体系造成了重大负担。深度学习（DL）为自动疾病筛查带来了颇具希望的解决办法，可却需要海量数据。在不同模式下收集和标注大量眼科图像面临诸多现实挑战，在罕见病方面尤甚。在此，我们推出 EyeDiff，这是一款能依据自然语言提示生成多模态眼科图像的文本到图像模型，并对其在常见及罕见疾病诊断中的适用性予以评估。EyeDiff 借助先进的潜在扩散模型在八个大规模数据集上开展训练，涵盖 14 种眼科图像模态和 80 多种眼部疾病，还适配了十个多国的外部数据集。所生成的图像精准捕捉了关键的病变特征，经客观指标和人类专家评估，与文本提示高度契合。而且，整合生成的图像大幅提升了检测少数类别和罕见眼病的精准度，在处理数据不均衡方面胜过传统的过采样方法。EyeDiff 有力化解了罕见病中常见的数据不均衡和不足的问题，也克服了收集大规模标注图像的难题，为推动眼科领域专家级疾病诊断模型的发展提供了创新性的解决方案。

> The rising prevalence of vision-threatening retinal diseases poses a significant burden on the global healthcare systems. Deep learning (DL) offers a promising solution for automatic disease screening but demands substantial data. Collecting and labeling large volumes of ophthalmic images across various modalities encounters several real-world challenges, especially for rare diseases. Here, we introduce EyeDiff, a text-to-image model designed to generate multimodal ophthalmic images from natural language prompts and evaluate its applicability in diagnosing common and rare diseases. EyeDiff is trained on eight large-scale datasets using the advanced latent diffusion model, covering 14 ophthalmic image modalities and over 80 ocular diseases, and is adapted to ten multi-country external datasets. The generated images accurately capture essential lesional characteristics, achieving high alignment with text prompts as evaluated by objective metrics and human experts. Furthermore, integrating generated images significantly enhances the accuracy of detecting minority classes and rare eye diseases, surpassing traditional oversampling methods in addressing data imbalance. EyeDiff effectively tackles the issue of data imbalance and insufficiency typically encountered in rare diseases and addresses the challenges of collecting large-scale annotated images, offering a transformative solution to enhance the development of expert-level diseases diagnosis models in ophthalmic field.

[Arxiv](https://arxiv.org/abs/2411.10004)