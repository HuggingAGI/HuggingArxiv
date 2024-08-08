# 借助 LLM 提升自动驾驶中的开放词汇 3D 场景理解能力

发布时间：2024年08月06日

`LLM应用` `自动驾驶` `人工智能`

> Leveraging LLMs for Enhanced Open-Vocabulary 3D Scene Understanding in Autonomous Driving

# 摘要

> 本文提出了一种创新方法，通过融合语言嵌入的3D高斯与大型语言模型（LLMs），提升自动驾驶中的开放词汇3D场景理解。我们利用LLMs生成与场景相关的标准短语，用于分割和解释。该方法通过比较LLMs生成的短语与3D高斯中的语言特征，显著增强了对新环境的零-shot理解和目标检测。实验显示，在WayveScenes101数据集上，我们的方法在开放词汇对象检测和分割方面表现卓越。这项研究推动了自动驾驶系统向更智能、上下文感知方向的发展，有效整合了3D场景与高级语义理解。

> This paper introduces a novel method for open-vocabulary 3D scene understanding in autonomous driving by combining Language Embedded 3D Gaussians with Large Language Models (LLMs) for enhanced inference. We propose utilizing LLMs to generate contextually relevant canonical phrases for segmentation and scene interpretation. Our method leverages the contextual and semantic capabilities of LLMs to produce a set of canonical phrases, which are then compared with the language features embedded in the 3D Gaussians. This LLM-guided approach significantly improves zero-shot scene understanding and detection of objects of interest, even in the most challenging or unfamiliar environments. Experimental results on the WayveScenes101 dataset demonstrate that our approach surpasses state-of-the-art methods in terms of accuracy and flexibility for open-vocabulary object detection and segmentation. This work represents a significant advancement towards more intelligent, context-aware autonomous driving systems, effectively bridging 3D scene representation with high-level semantic understanding.

[Arxiv](https://arxiv.org/abs/2408.03516)