# LLaVA 需更多知识：结合知识图谱的检索增强自然语言生成，助力胸腔病理解析

发布时间：2024年10月07日

`LLM应用` `图像处理`

> LLaVA Needs More Knowledge: Retrieval Augmented Natural Language Generation with Knowledge Graph for Explaining Thoracic Pathologies

# 摘要

> 为医学图像模型预测生成自然语言解释，尤其是胸腔病理图像，仍是一项关键且具挑战性的任务。现有方法常因通用模型缺乏特定医学知识和检索增强技术带来的隐私问题而受限。为此，我们提出了一种结合知识图谱 (KG) 数据存储的视觉-语言框架，通过引入额外领域特定医学知识，提升模型生成准确且信息丰富解释的能力。该框架采用基于 KG 的检索机制，既提高了解释精度，又通过避免直接数据检索保护了隐私。KG 数据存储设计为即插即用模块，可无缝集成多种模型架构。我们评估了三种框架：KG-LLaVA 集成预训练 LLaVA 模型与 KG-RAG；Med-XPT 结合 MedCLIP、变压器投影仪和 GPT-2；Bio-LLaVA 通过结合 Bio-ViT-L 视觉模型适应 LLaVA。这些框架在 MIMIC-NLE 数据集上验证，取得最先进成果，凸显了 KG 增强在生成高质量胸腔病理解释中的有效性。

> Generating Natural Language Explanations (NLEs) for model predictions on medical images, particularly those depicting thoracic pathologies, remains a critical and challenging task. Existing methodologies often struggle due to general models' insufficient domain-specific medical knowledge and privacy concerns associated with retrieval-based augmentation techniques. To address these issues, we propose a novel Vision-Language framework augmented with a Knowledge Graph (KG)-based datastore, which enhances the model's understanding by incorporating additional domain-specific medical knowledge essential for generating accurate and informative NLEs. Our framework employs a KG-based retrieval mechanism that not only improves the precision of the generated explanations but also preserves data privacy by avoiding direct data retrieval. The KG datastore is designed as a plug-and-play module, allowing for seamless integration with various model architectures. We introduce and evaluate three distinct frameworks within this paradigm: KG-LLaVA, which integrates the pre-trained LLaVA model with KG-RAG; Med-XPT, a custom framework combining MedCLIP, a transformer-based projector, and GPT-2; and Bio-LLaVA, which adapts LLaVA by incorporating the Bio-ViT-L vision model. These frameworks are validated on the MIMIC-NLE dataset, where they achieve state-of-the-art results, underscoring the effectiveness of KG augmentation in generating high-quality NLEs for thoracic pathologies.

[Arxiv](https://arxiv.org/abs/2410.04749)