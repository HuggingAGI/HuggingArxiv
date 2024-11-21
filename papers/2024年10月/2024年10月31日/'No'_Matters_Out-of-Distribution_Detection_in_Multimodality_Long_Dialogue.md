# “‘不’很关键”：多模态长对话中的分布外检测

发布时间：2024年10月31日

`Agent` `对话系统` `多模态`

> 'No' Matters: Out-of-Distribution Detection in Multimodality Long Dialogue

# 摘要

> 在多模态情境下的分布外（OOD）检测对于识别不同模态组合输入中的偏差极为重要，尤其在开放域对话系统或现实生活对话交互等应用中。本文旨在通过高效检测 OOD 对话和图像来提升涉及多轮长对话的用户体验。我们引入了名为对话图像对齐和增强框架（DIAEF）的全新评分框架，它将视觉语言模型与新提出的分数相融合，用于检测两个关键场景中的 OOD：一是对话与图像输入对的不匹配，二是具有先前未见过标签的输入对。从各种基准得出的实验结果表明，对于先前未见过的标签，将图像和多轮对话的 OOD 检测相结合比单独使用任何一种模态更有效。在存在不匹配对的情况下，我们提出的分数能有效识别这些不匹配，并在长对话中展现出强大的稳健性。此方法增强了具有领域感知和自适应能力的会话代理，并为未来研究奠定了基础。

> Out-of-distribution (OOD) detection in multimodal contexts is essential for identifying deviations in combined inputs from different modalities, particularly in applications like open-domain dialogue systems or real-life dialogue interactions. This paper aims to improve the user experience that involves multi-round long dialogues by efficiently detecting OOD dialogues and images. We introduce a novel scoring framework named Dialogue Image Aligning and Enhancing Framework (DIAEF) that integrates the visual language models with the novel proposed scores that detect OOD in two key scenarios (1) mismatches between the dialogue and image input pair and (2) input pairs with previously unseen labels. Our experimental results, derived from various benchmarks, demonstrate that integrating image and multi-round dialogue OOD detection is more effective with previously unseen labels than using either modality independently. In the presence of mismatched pairs, our proposed score effectively identifies these mismatches and demonstrates strong robustness in long dialogues. This approach enhances domain-aware, adaptive conversational agents and establishes baselines for future studies.

[Arxiv](https://arxiv.org/abs/2410.23883)