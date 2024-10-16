# PAVLM：借助视觉-语言模型，推动基于点云的可操作性理解

发布时间：2024年10月15日

`Agent` `机器人` `计算机视觉`

> PAVLM: Advancing Point Cloud based Affordance Understanding Via Vision-Language Model

# 摘要

> Affordance 理解对机器人与物理世界互动至关重要。尽管视觉语言模型在机器人操作方面表现出色，但在细微物理特性理解上仍显不足。我们提出的 PAVLM 框架，通过融合预训练语言模型的多模态知识，显著提升了点云的 3D Affordance 理解。实验证明，PAVLM 在处理 3D 对象的新颖任务时表现尤为突出。更多详情，请访问：pavlm-source.github.io。

> Affordance understanding, the task of identifying actionable regions on 3D objects, plays a vital role in allowing robotic systems to engage with and operate within the physical world. Although Visual Language Models (VLMs) have excelled in high-level reasoning and long-horizon planning for robotic manipulation, they still fall short in grasping the nuanced physical properties required for effective human-robot interaction. In this paper, we introduce PAVLM (Point cloud Affordance Vision-Language Model), an innovative framework that utilizes the extensive multimodal knowledge embedded in pre-trained language models to enhance 3D affordance understanding of point cloud. PAVLM integrates a geometric-guided propagation module with hidden embeddings from large language models (LLMs) to enrich visual semantics. On the language side, we prompt Llama-3.1 models to generate refined context-aware text, augmenting the instructional input with deeper semantic cues. Experimental results on the 3D-AffordanceNet benchmark demonstrate that PAVLM outperforms baseline methods for both full and partial point clouds, particularly excelling in its generalization to novel open-world affordance tasks of 3D objects. For more information, visit our project site: pavlm-source.github.io.

[Arxiv](https://arxiv.org/abs/2410.11564)