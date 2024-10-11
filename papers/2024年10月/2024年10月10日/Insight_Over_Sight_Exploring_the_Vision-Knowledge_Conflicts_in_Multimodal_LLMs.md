# 洞察力与视觉的较量？探究多模态 LLM 中的视觉与知识冲突

发布时间：2024年10月10日

`LLM应用` `人工智能` `计算机视觉`

> Insight Over Sight? Exploring the Vision-Knowledge Conflicts in Multimodal LLMs

# 摘要

> 本文深入研究了多模态大型语言模型 (MLLM) 中视觉信息与常识知识之间的冲突问题。为此，我们设计了一套自动化流程，并结合人在回路的质量控制，创建了一个模拟和评估这些冲突的基准。该基准包含 374 张原始图像和 1,122 个高质量问答对，覆盖两种冲突类型和三种难度级别，全面评估 MLLM 的冲突解决能力。我们发现，现有模型对文本查询的依赖过重。基于此，我们提出了“Focus-on-Vision” (FoV) 策略，显著提升模型对视觉数据的优先处理能力。这一研究不仅深化了对 MLLM 中视觉-知识冲突的理解，还提供了有效的缓解策略。所有数据和代码均已公开。

> This paper explores the problem of commonsense-level vision-knowledge conflict in Multimodal Large Language Models (MLLMs), where visual information contradicts model's internal commonsense knowledge (see Figure 1). To study this issue, we introduce an automated pipeline, augmented with human-in-the-loop quality control, to establish a benchmark aimed at simulating and assessing the conflicts in MLLMs. Utilizing this pipeline, we have crafted a diagnostic benchmark comprising 374 original images and 1,122 high-quality question-answer (QA) pairs. This benchmark covers two types of conflict target and three question difficulty levels, providing a thorough assessment tool. Through this benchmark, we evaluate the conflict-resolution capabilities of nine representative MLLMs across various model families and find a noticeable over-reliance on textual queries. Drawing on these findings, we propose a novel prompting strategy, "Focus-on-Vision" (FoV), which markedly enhances MLLMs' ability to favor visual data over conflicting textual knowledge. Our detailed analysis and the newly proposed strategy significantly advance the understanding and mitigating of vision-knowledge conflicts in MLLMs. The data and code are made publicly available.

[Arxiv](https://arxiv.org/abs/2410.08145)