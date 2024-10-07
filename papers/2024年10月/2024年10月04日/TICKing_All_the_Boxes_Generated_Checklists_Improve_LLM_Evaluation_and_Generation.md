# 生成的检查表全面提升 LLM 的评估与生成能力

发布时间：2024年10月04日

`LLM应用` `人工智能`

> TICKing All the Boxes: Generated Checklists Improve LLM Evaluation and Generation

# 摘要

> 随着大型语言模型（LLM）的普及，对其指令遵循能力的灵活且可解释的评估变得至关重要。尽管偏好判断已成为评估标准，但将复杂的多方面偏好简化为单一排名仍存在挑战。此外，由于人工注释成本高昂，LLM 越来越多地被用于评估，尽管这牺牲了可靠性和可解释性。为此，我们提出了 TICK（Targeted Instruct-evaluation with ChecKlists），一种全自动、可解释的评估协议，利用 LLM 生成的特定指令检查表进行评估。我们发现，LLM 能生成高质量的检查表，将指令分解为一系列 YES/NO 问题，显著提高了 LLM 判断与人类偏好的一致性（46.4% 提升至 52.2%）。此外，STICK（Self-TICK）通过自我改进和最佳选择，在多个基准上提升了生成质量，例如在 LiveBench 推理任务上提升了 7.8%，在 WildBench 数据集上提升了 6.3%。这表明，结构化的多方面自我改进是提升 LLM 能力的有力途径。最后，通过向人类评估者提供 LLM 生成的检查表，我们显著提高了注释者间的一致性（从 0.194 提升至 0.256）。

> Given the widespread adoption and usage of Large Language Models (LLMs), it is crucial to have flexible and interpretable evaluations of their instruction-following ability. Preference judgments between model outputs have become the de facto evaluation standard, despite distilling complex, multi-faceted preferences into a single ranking. Furthermore, as human annotation is slow and costly, LLMs are increasingly used to make these judgments, at the expense of reliability and interpretability. In this work, we propose TICK (Targeted Instruct-evaluation with ChecKlists), a fully automated, interpretable evaluation protocol that structures evaluations with LLM-generated, instruction-specific checklists. We first show that, given an instruction, LLMs can reliably produce high-quality, tailored evaluation checklists that decompose the instruction into a series of YES/NO questions. Each question asks whether a candidate response meets a specific requirement of the instruction. We demonstrate that using TICK leads to a significant increase (46.4% $\to$ 52.2%) in the frequency of exact agreements between LLM judgements and human preferences, as compared to having an LLM directly score an output. We then show that STICK (Self-TICK) can be used to improve generation quality across multiple benchmarks via self-refinement and Best-of-N selection. STICK self-refinement on LiveBench reasoning tasks leads to an absolute gain of $+$7.8%, whilst Best-of-N selection with STICK attains $+$6.3% absolute improvement on the real-world instruction dataset, WildBench. In light of this, structured, multi-faceted self-improvement is shown to be a promising way to further advance LLM capabilities. Finally, by providing LLM-generated checklists to human evaluators tasked with directly scoring LLM responses to WildBench instructions, we notably increase inter-annotator agreement (0.194 $\to$ 0.256).

[Arxiv](https://arxiv.org/abs/2410.03608)