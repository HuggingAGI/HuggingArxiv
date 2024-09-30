# Align$^2$LLaVA：通过级联人类与大型语言模型的偏好对齐，实现多模态指令的优化。

发布时间：2024年09月27日

`LLM应用` `人工智能` `机器学习`

> Align$^2$LLaVA: Cascaded Human and Large Language Model Preference Alignment for Multi-modal Instruction Curation

# 摘要

> 多模态大型语言模型（如 LLaVA 系列）的进步，依赖于大量机器生成的指令数据调优。然而，这种自动收集流程却无意中导致了数据质量的显著波动。本文提出了一种创新的指令精选算法，结合了人类与 LLM 的偏好对齐，将庞大的机器生成多模态指令库压缩为高质量的紧凑形式：(i) 通过收集多模态指令数据集，并设定全面的主客观标准，我们训练了一个奖励模型，以捕捉人类对指令对齐的细微理解。(ii) 利用 MLLM 内部的 LLM，我们进一步优化了视觉指令的写作风格，使其与内部 LLM 对齐。实验证明，即使将合成多模态指令压缩至原规模的 10%，模型性能仍能保持甚至提升。特别地，将训练样本从 158k 锐减至 14k，我们的模型在多项 MLLM 基准测试中依然表现优异。项目详情请访问 https://github.com/DCDmllm/Align2LLaVA。

> Recent advances in Multi-modal Large Language Models (MLLMs), such as LLaVA-series models, are driven by massive machine-generated instruction-following data tuning. Such automatic instruction collection pipelines, however, inadvertently introduce significant variability in data quality. This paper introduces a novel instruction curation algorithm, derived from two unique perspectives, human and LLM preference alignment, to compress this vast corpus of machine-generated multimodal instructions to a compact and high-quality form: (i) For human preference alignment, we have collected a machine-generated multimodal instruction dataset and established a comprehensive set of both subjective and objective criteria to guide the data quality assessment critically from human experts. By doing so, a reward model was trained on the annotated dataset to internalize the nuanced human understanding of instruction alignment. (ii) For LLM preference alignment, given the instruction selected by the reward model, we propose leveraging the inner LLM used in MLLM to align the writing style of visual instructions with that of the inner LLM itself, resulting in LLM-aligned instruction improvement. Extensive experiments demonstrate that we can maintain or even improve model performance by compressing synthetic multimodal instructions by up to 90%. Impressively, by aggressively reducing the total training sample size from 158k to 14k (9$\times$ smaller), our model consistently outperforms its full-size dataset counterpart across various MLLM benchmarks. Our project is available at https://github.com/DCDmllm/Align2LLaVA.

[Arxiv](https://arxiv.org/abs/2409.18541)