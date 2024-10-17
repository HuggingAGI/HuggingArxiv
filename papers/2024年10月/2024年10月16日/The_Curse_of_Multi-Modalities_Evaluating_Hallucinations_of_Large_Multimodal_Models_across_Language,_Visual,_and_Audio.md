# 多模态之咒：探究大型多模态模型在语言、视觉和音频领域的幻觉现象

发布时间：2024年10月16日

`LLM应用` `人工智能` `多媒体`

> The Curse of Multi-Modalities: Evaluating Hallucinations of Large Multimodal Models across Language, Visual, and Audio

# 摘要

> 近期，大型多模态模型 (LMM) 的进步显著提升了多任务性能，并正努力整合视频和音频等更多模态。然而，现有 LMM 仍易受幻觉影响，即输入与输出间的差异，限制了其在现实场景中的应用。本文首次系统探讨了 LMM 中语言、视觉和音频模态的幻觉现象，发现主要原因包括过度依赖单模态先验和虚假模态间相关性。为此，我们推出了“多模态的诅咒”(CMM) 基准，全面评估并深入分析了 LMM 的幻觉问题。研究揭示了模态整合不平衡和训练数据偏见等关键脆弱性，强调了平衡跨模态学习和强化幻觉缓解策略的重要性。基于此，我们提出了提升 LMM 可靠性的潜在研究方向。

> Recent advancements in large multimodal models (LMMs) have significantly enhanced performance across diverse tasks, with ongoing efforts to further integrate additional modalities such as video and audio. However, most existing LMMs remain vulnerable to hallucinations, the discrepancy between the factual multimodal input and the generated textual output, which has limited their applicability in various real-world scenarios. This paper presents the first systematic investigation of hallucinations in LMMs involving the three most common modalities: language, visual, and audio. Our study reveals two key contributors to hallucinations: overreliance on unimodal priors and spurious inter-modality correlations. To address these challenges, we introduce the benchmark The Curse of Multi-Modalities (CMM), which comprehensively evaluates hallucinations in LMMs, providing a detailed analysis of their underlying issues. Our findings highlight key vulnerabilities, including imbalances in modality integration and biases from training data, underscoring the need for balanced cross-modal learning and enhanced hallucination mitigation strategies. Based on our observations and findings, we suggest potential research directions that could enhance the reliability of LMMs.

[Arxiv](https://arxiv.org/abs/2410.12787)