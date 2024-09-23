# FIHA：借助 Davidson 场景图，自主评估视觉-语言模型中的幻觉现象

发布时间：2024年09月20日

`LLM应用` `计算机视觉`

> FIHA: Autonomous Hallucination Evaluation in Vision-Language Models with Davidson Scene Graphs

# 摘要

> 随着大型视觉-语言模型 (LVLMs) 的迅猛发展，幻觉问题日益突出，使得高效全面的评估变得至关重要。现有方法多依赖昂贵的注释，且评估不够全面。为此，我们推出了 FIHA，一种无需 LLM 和注释即可评估 LVLMs 幻觉的自主系统，并能建模幻觉间的依赖关系。FIHA 能以极低成本生成图像数据集的问答对，全面评估幻觉。基于此，我们创建了 FIHA-v1 基准，涵盖 MSCOCO 和 Foggy 的多样化图像问题。通过 Davidson Scene Graph (DSG) 优化问答结构，提升评估可靠性。我们用 FIHA-v1 评估了代表性模型，揭示其局限与挑战，并公开了代码与数据。

> The rapid development of Large Vision-Language Models (LVLMs) often comes with widespread hallucination issues, making cost-effective and comprehensive assessments increasingly vital. Current approaches mainly rely on costly annotations and are not comprehensive -- in terms of evaluating all aspects such as relations, attributes, and dependencies between aspects. Therefore, we introduce the FIHA (autonomous Fine-graIned Hallucination evAluation evaluation in LVLMs), which could access hallucination LVLMs in the LLM-free and annotation-free way and model the dependency between different types of hallucinations. FIHA can generate Q&A pairs on any image dataset at minimal cost, enabling hallucination assessment from both image and caption. Based on this approach, we introduce a benchmark called FIHA-v1, which consists of diverse questions on various images from MSCOCO and Foggy. Furthermore, we use the Davidson Scene Graph (DSG) to organize the structure among Q&A pairs, in which we can increase the reliability of the evaluation. We evaluate representative models using FIHA-v1, highlighting their limitations and challenges. We released our code and data.

[Arxiv](https://arxiv.org/abs/2409.13612)