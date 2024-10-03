# 探索 CLIP 模型鲁棒性的全面评估

发布时间：2024年10月02日

`LLM应用` `计算机视觉` `人工智能`

> Toward a Holistic Evaluation of Robustness in CLIP Models

# 摘要

> CLIP 模型在零-shot 分类中表现出色，尤其是在处理多样分布偏移时。本研究通过引入新视角，对 CLIP 进行了更全面的评估。首先，我们探讨了 CLIP 对视觉因素变化的鲁棒性。其次，我们评估了置信度不确定性和分布外检测这两个关键安全目标。第三，我们考察了 CLIP 在连接图像和文本模态方面的精细程度。第四，我们扩展到 CLIP 的 3D 意识，超越传统 2D 理解。最后，我们研究了现代多模态模型中视觉和语言编码器的交互，及其对分类鲁棒性的影响。我们考虑了六个因素：模型架构、训练分布、训练集大小、微调、对比损失和测试时提示。研究发现，视觉编码器架构对 3D 损坏的鲁棒性至关重要，且 CLIP 在预测时倾向于形状，但微调后偏差减弱。利用 CLIP 视觉编码器的视觉-语言模型在挑战性类别上表现更佳。这些发现为提升 CLIP 的鲁棒性和可靠性提供了重要指导。

> Contrastive Language-Image Pre-training (CLIP) models have shown significant potential, particularly in zero-shot classification across diverse distribution shifts. Building on existing evaluations of overall classification robustness, this work aims to provide a more comprehensive assessment of CLIP by introducing several new perspectives. First, we investigate their robustness to variations in specific visual factors. Second, we assess two critical safety objectives--confidence uncertainty and out-of-distribution detection--beyond mere classification accuracy. Third, we evaluate the finesse with which CLIP models bridge the image and text modalities. Fourth, we extend our examination to 3D awareness in CLIP models, moving beyond traditional 2D image understanding. Finally, we explore the interaction between vision and language encoders within modern large multimodal models (LMMs) that utilize CLIP as the visual backbone, focusing on how this interaction impacts classification robustness. In each aspect, we consider the impact of six factors on CLIP models: model architecture, training distribution, training set size, fine-tuning, contrastive loss, and test-time prompts. Our study uncovers several previously unknown insights into CLIP. For instance, the architecture of the visual encoder in CLIP plays a significant role in their robustness against 3D corruption. CLIP models tend to exhibit a bias towards shape when making predictions. Moreover, this bias tends to diminish after fine-tuning on ImageNet. Vision-language models like LLaVA, leveraging the CLIP vision encoder, could exhibit benefits in classification performance for challenging categories over CLIP alone. Our findings are poised to offer valuable guidance for enhancing the robustness and reliability of CLIP models.

[Arxiv](https://arxiv.org/abs/2410.01534)