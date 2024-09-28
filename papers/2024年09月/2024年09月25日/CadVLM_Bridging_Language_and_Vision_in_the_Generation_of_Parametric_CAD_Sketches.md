# CadVLM：在参数化 CAD 草图生成中融合语言与视觉

发布时间：2024年09月25日

`LLM应用` `机械设计` `计算机辅助设计`

> CadVLM: Bridging Language and Vision in the Generation of Parametric CAD Sketches

# 摘要

> 参数化 CAD 是现代机械设计的核心，但在精确草图建模和实用评估指标方面面临挑战。我们借助在 NLP 和 CV 领域表现出色的预训练模型，开发了专用于 CAD 的生成模型。这些模型能深入理解复杂几何和设计逻辑，是 CAD 技术的重大突破。本文介绍的 CadVLM 是一种端到端的 CAD 视觉语言模型，通过调整预训练模型，有效整合草图原语和图像，显著提升了 CAD 草图生成任务的性能。这是首次将多模态 LLM 成功应用于参数化 CAD 生成，为计算机辅助机械设计领域开辟了新路径。

> Parametric Computer-Aided Design (CAD) is central to contemporary mechanical design. However, it encounters challenges in achieving precise parametric sketch modeling and lacks practical evaluation metrics suitable for mechanical design. We harness the capabilities of pre-trained foundation models, renowned for their successes in natural language processing and computer vision, to develop generative models specifically for CAD. These models are adept at understanding complex geometries and design reasoning, a crucial advancement in CAD technology. In this paper, we propose CadVLM, an end-to-end vision language model for CAD generation. Our approach involves adapting pre-trained foundation models to manipulate engineering sketches effectively, integrating both sketch primitive sequences and sketch images. Extensive experiments demonstrate superior performance on multiple CAD sketch generation tasks such as CAD autocompletion, CAD autoconstraint, and image conditional generation. To our knowledge, this is the first instance of a multimodal Large Language Model (LLM) being successfully applied to parametric CAD generation, representing a pioneering step in the field of computer-aided mechanical design.

[Arxiv](https://arxiv.org/abs/2409.17457)