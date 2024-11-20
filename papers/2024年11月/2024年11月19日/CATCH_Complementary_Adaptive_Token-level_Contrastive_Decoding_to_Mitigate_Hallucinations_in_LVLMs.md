# CATCH：通过互补自适应令牌级对比解码来减轻 LVLMs 中的幻觉

发布时间：2024年11月19日

`LLM应用` `视觉处理`

> CATCH: Complementary Adaptive Token-level Contrastive Decoding to Mitigate Hallucinations in LVLMs

# 摘要

> 大型视觉语言模型（LVLM）系统展现出了令人瞩目的视觉语言推理能力，然而却深陷普遍且严重的幻觉问题，给医疗保健和自主系统等关键领域带来了巨大风险。尽管此前为缓解幻觉问题付出了努力，但仍存在一个顽疾：视觉语言未对齐造成的视觉缺陷，成为视觉处理能力的瓶颈。为攻克这一难题，我们基于信息瓶颈理论研发了用于减轻 LVLM 幻觉的互补自适应令牌级对比解码（CATCH）。CATCH 引入了用于视觉信息分离的互补视觉解耦（CVD）、用于幻觉检测的非视觉筛选（NVS）以及用于减轻幻觉的自适应令牌级对比解码（ATCD）。CATCH 解决了导致在开放式场景中精细粒度特征感知减弱和累积幻觉的视觉缺陷相关问题。它适用于各类视觉问答任务，无需特定数据或先验知识，且无需额外训练就能在新任务中表现出强大的泛化能力，为 LVLM 在各种挑战性应用中的发展开辟了新的前景。

> Large Vision-Language Model (LVLM) systems have demonstrated impressive vision-language reasoning capabilities but suffer from pervasive and severe hallucination issues, posing significant risks in critical domains such as healthcare and autonomous systems. Despite previous efforts to mitigate hallucinations, a persistent issue remains: visual defect from vision-language misalignment, creating a bottleneck in visual processing capacity. To address this challenge, we develop Complementary Adaptive Token-level Contrastive Decoding to Mitigate Hallucinations in LVLMs (CATCH), based on the Information Bottleneck theory. CATCH introduces Complementary Visual Decoupling (CVD) for visual information separation, Non-Visual Screening (NVS) for hallucination detection, and Adaptive Token-level Contrastive Decoding (ATCD) for hallucination mitigation. CATCH addresses issues related to visual defects that cause diminished fine-grained feature perception and cumulative hallucinations in open-ended scenarios. It is applicable to various visual question-answering tasks without requiring any specific data or prior knowledge, and generalizes robustly to new tasks without additional training, opening new possibilities for advancing LVLM in various challenging applications.

[Arxiv](https://arxiv.org/abs/2411.12713)