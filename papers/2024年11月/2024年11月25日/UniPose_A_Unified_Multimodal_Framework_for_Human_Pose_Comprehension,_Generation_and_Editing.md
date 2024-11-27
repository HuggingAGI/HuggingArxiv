# UniPose：一个用于人体姿态理解、生成与编辑的统一多模态框架

发布时间：2024年11月25日

`LLM应用` `数字媒体` `姿态识别`

> UniPose: A Unified Multimodal Framework for Human Pose Comprehension, Generation and Editing

# 摘要

> 在数字时代，人类姿态至关重要。尽管近期相关工作在理解和生成人类姿态方面成果斐然，但往往仅支持单一模态的控制信号且孤立运作，这限制了其在现实场景中的应用。本文推出了 UniPose，这一框架借助大型语言模型（LLMs）来理解、生成和编辑多种模态的人类姿态，涵盖图像、文本和 3D SMPL 姿态等。具体而言，我们运用姿态标记器将 3D 姿态转化为离散的姿态标记，从而能在统一的词汇表中与 LLM 无缝融合。为进一步提升细粒度的姿态感知能力，我们为 UniPose 配置了多种视觉编码器，其中包含特定于姿态的视觉编码器。得益于统一的学习策略，UniPose 能在不同的姿态相关任务间有效传递知识，适应未知任务，并展现出拓展的能力。此项工作是构建通用的姿态理解、生成和编辑框架的首次尝试。大量实验表明，UniPose 在各类姿态相关任务中表现出色，甚至优于其他方法。

> Human pose plays a crucial role in the digital age. While recent works have achieved impressive progress in understanding and generating human poses, they often support only a single modality of control signals and operate in isolation, limiting their application in real-world scenarios. This paper presents UniPose, a framework employing Large Language Models (LLMs) to comprehend, generate, and edit human poses across various modalities, including images, text, and 3D SMPL poses. Specifically, we apply a pose tokenizer to convert 3D poses into discrete pose tokens, enabling seamless integration into the LLM within a unified vocabulary. To further enhance the fine-grained pose perception capabilities, we facilitate UniPose with a mixture of visual encoders, among them a pose-specific visual encoder. Benefiting from a unified learning strategy, UniPose effectively transfers knowledge across different pose-relevant tasks, adapts to unseen tasks, and exhibits extended capabilities. This work serves as the first attempt at building a general-purpose framework for pose comprehension, generation, and editing. Extensive experiments highlight UniPose's competitive and even superior performance across various pose-relevant tasks.

[Arxiv](https://arxiv.org/abs/2411.16781)