# 一张 X 光片，胜过 15 个特征：稀疏自动编码器助力放射报告生成，更可解释。

发布时间：2024年10月04日

`LLM应用` `人工智能`

> An X-Ray Is Worth 15 Features: Sparse Autoencoders for Interpretable Radiology Report Generation

# 摘要

> 放射服务需求激增，推动了自动化放射报告生成的发展。然而，现有视觉-语言模型存在幻觉、缺乏可解释性且需昂贵微调。为此，我们推出 SAE-Rad，利用稀疏自编码器将视觉变换器的潜在表示分解为人类可理解的特征。结合最先进的 SAE 技术，SAE-Rad 在保持稀疏性的同时实现精确重构。通过现成语言模型，我们无需微调大型模型，即可将真实报告提炼成放射描述并编译成完整报告。SAE-Rad 首次将机械可解释性技术应用于多模态推理任务，在 MIMIC-CXR 数据集上，其性能媲美最先进模型，且训练资源大幅减少。定性分析表明，SAE-Rad 不仅学习了有意义的视觉概念，还生成了与专家解释高度一致的报告。这为医疗多模态推理提供了更具可解释性的新选择。

> Radiological services are experiencing unprecedented demand, leading to increased interest in automating radiology report generation. Existing Vision-Language Models (VLMs) suffer from hallucinations, lack interpretability, and require expensive fine-tuning. We introduce SAE-Rad, which uses sparse autoencoders (SAEs) to decompose latent representations from a pre-trained vision transformer into human-interpretable features. Our hybrid architecture combines state-of-the-art SAE advancements, achieving accurate latent reconstructions while maintaining sparsity. Using an off-the-shelf language model, we distil ground-truth reports into radiological descriptions for each SAE feature, which we then compile into a full report for each image, eliminating the need for fine-tuning large models for this task. To the best of our knowledge, SAE-Rad represents the first instance of using mechanistic interpretability techniques explicitly for a downstream multi-modal reasoning task. On the MIMIC-CXR dataset, SAE-Rad achieves competitive radiology-specific metrics compared to state-of-the-art models while using significantly fewer computational resources for training. Qualitative analysis reveals that SAE-Rad learns meaningful visual concepts and generates reports aligning closely with expert interpretations. Our results suggest that SAEs can enhance multimodal reasoning in healthcare, providing a more interpretable alternative to existing VLMs.

[Arxiv](https://arxiv.org/abs/2410.03334)