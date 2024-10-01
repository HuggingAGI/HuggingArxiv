# OpenKD：为零-shot 和少-shot 关键点检测开启提示多样性

发布时间：2024年09月29日

`LLM应用` `计算机视觉` `人工智能`

> OpenKD: Opening Prompt Diversity for Zero- and Few-shot Keypoint Detection

# 摘要

> 利用基础模型（如CLIP）构建多功能关键点检测器正逐渐成为研究热点。现有模型多通过文本（如“猫的鼻子”）或视觉提示（如带有关键点标注的图像）来检测目标图像中的关键点，从而实现零-shot或few-shot检测。然而，多模态提示的研究尚不充分，提示的语义和语言多样性仍有待挖掘。例如，如何处理新颖关键点的未见文本提示，或如“你能检测猫的鼻子和耳朵吗？”这类多样化提示。为此，我们从模态、语义（已见与未见）和语言三个方面探索提示多样性，以实现更通用的零-shot和few-shot关键点检测（Z-FSKD）。我们提出了OpenKD模型，利用多模态原型集支持视觉和文本提示。此外，为提升未见文本的关键点检测能力，我们引入了从视觉和文本域插值的辅助关键点和文本，显著增强了模型的空间推理和零-shot新颖关键点检测能力。实验表明，OpenKD在Z-FSKD上表现卓越，并开创了处理未见和多样化文本的新方法。源代码和数据已公开，详见https://github.com/AlanLuSun/OpenKD。

> Exploiting the foundation models (e.g., CLIP) to build a versatile keypoint detector has gained increasing attention. Most existing models accept either the text prompt (e.g., ``the nose of a cat''), or the visual prompt (e.g., support image with keypoint annotations), to detect the corresponding keypoints in query image, thereby, exhibiting either zero-shot or few-shot detection ability. However, the research on taking multimodal prompt is still underexplored, and the prompt diversity in semantics and language is far from opened. For example, how to handle unseen text prompts for novel keypoint detection and the diverse text prompts like ``Can you detect the nose and ears of a cat?'' In this work, we open the prompt diversity from three aspects: modality, semantics (seen v.s. unseen), and language, to enable a more generalized zero- and few-shot keypoint detection (Z-FSKD). We propose a novel OpenKD model which leverages multimodal prototype set to support both visual and textual prompting. Further, to infer the keypoint location of unseen texts, we add the auxiliary keypoints and texts interpolated from visual and textual domains into training, which improves the spatial reasoning of our model and significantly enhances zero-shot novel keypoint detection. We also found large language model (LLM) is a good parser, which achieves over 96% accuracy to parse keypoints from texts. With LLM, OpenKD can handle diverse text prompts. Experimental results show that our method achieves state-of-the-art performance on Z-FSKD and initiates new ways to deal with unseen text and diverse texts. The source code and data are available at https://github.com/AlanLuSun/OpenKD.

[Arxiv](https://arxiv.org/abs/2409.19899)