# ZALM3：借助多轮多模态医疗对话中的上下文信息，实现视觉与语言对齐的零-shot 增强。

发布时间：2024年09月26日

`LLM应用` `人工智能`

> ZALM3: Zero-Shot Enhancement of Vision-Language Alignment via In-Context Information in Multi-Turn Multimodal Medical Dialogue

# 摘要

> 近年来，LLM 的蓬勃发展推动了 VLM 在医疗领域的应用。在我们的在线医疗咨询中，医生通过多轮对话分析患者的文本和图像，形成多轮多模态医疗对话。然而，患者用手机拍摄的图像质量较差，影响了视觉-语言对齐。为此，我们提出了 ZALM3，一种零-shot 策略，通过 LLM 提取关键词和视觉定位模型提取感兴趣区域，优化图像质量，提升视觉-语言对齐。实验结果表明，ZALM3 在多个临床部门中显著提升了诊断效果。

> The rocketing prosperity of large language models (LLMs) in recent years has boosted the prevalence of vision-language models (VLMs) in the medical sector. In our online medical consultation scenario, a doctor responds to the texts and images provided by a patient in multiple rounds to diagnose her/his health condition, forming a multi-turn multimodal medical dialogue format. Unlike high-quality images captured by professional equipment in traditional medical visual question answering (Med-VQA), the images in our case are taken by patients' mobile phones. These images have poor quality control, with issues such as excessive background elements and the lesion area being significantly off-center, leading to degradation of vision-language alignment in the model training phase. In this paper, we propose ZALM3, a Zero-shot strategy to improve vision-language ALignment in Multi-turn Multimodal Medical dialogue. Since we observe that the preceding text conversations before an image can infer the regions of interest (RoIs) in the image, ZALM3 employs an LLM to summarize the keywords from the preceding context and a visual grounding model to extract the RoIs. The updated images eliminate unnecessary background noise and provide more effective vision-language alignment. To better evaluate our proposed method, we design a new subjective assessment metric for multi-turn unimodal/multimodal medical dialogue to provide a fine-grained performance comparison. Our experiments across three different clinical departments remarkably demonstrate the efficacy of ZALM3 with statistical significance.

[Arxiv](https://arxiv.org/abs/2409.17610)