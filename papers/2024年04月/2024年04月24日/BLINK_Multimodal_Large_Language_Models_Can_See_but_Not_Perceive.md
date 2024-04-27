# BLINK：多模态大型语言模型具备视觉识别能力，但尚未达到深度感知的水平。

发布时间：2024年04月24日

`分类：LLM应用

这篇论文的摘要描述了一个针对多模态语言模型（LLM）的新基准测试，名为 Blink。它专注于测试 LLM 在核心视觉感知技能方面的表现，这些技能在其他评估中并不常见。论文中提到了人类在这些任务上的表现，以及现有多模态 LLM 的挑战。此外，论文还指出了专业计算机视觉模型在解决这些问题上的潜力。因此，这篇论文主要关注多模态 LLM 在实际应用中的性能和挑战，属于 LLM 应用类别。` `计算机视觉` `人工智能`

> BLINK: Multimodal Large Language Models Can See but Not Perceive

# 摘要

> 我们推出了 Blink，这是针对多模态语言模型（LLM）的一项新基准测试，它着眼于核心视觉感知技能，这些技能在其他评估中并不常见。人类可以在一瞬间解决大多数 Blink 任务，如相对深度估计、视觉匹配、法医侦测和多视角推理。然而，这些对感知能力要求极高的任务对当前的多模态 LLM 来说是一个重大挑战，因为它们不容易通过自然语言进行中介。Blink 将 14 个经典计算机视觉任务转化为 3,807 道多项选择题，每题都配有一张或多张图片以及视觉提示。尽管人类平均正确率高达 95.70%，但 Blink 对现有多模态 LLM 来说却异常困难：即便是表现最佳的 GPT-4V 和 Gemini，其准确率也仅为 51.26% 和 45.72%，仅比随机猜测高出 13.17% 和 7.63%，这表明这些感知技能在最新的多模态 LLM 中尚未“显现”。我们的分析还指出，专业的计算机视觉模型能更好地解决这些问题，这为未来的提升指明了可能的方向。我们相信 Blink 将激励社区推动多模态 LLM 达到与人类相媲美的视觉感知水平。

> We introduce Blink, a new benchmark for multimodal language models (LLMs) that focuses on core visual perception abilities not found in other evaluations. Most of the Blink tasks can be solved by humans "within a blink" (e.g., relative depth estimation, visual correspondence, forensics detection, and multi-view reasoning). However, we find these perception-demanding tasks cast significant challenges for current multimodal LLMs because they resist mediation through natural language. Blink reformats 14 classic computer vision tasks into 3,807 multiple-choice questions, paired with single or multiple images and visual prompting. While humans get 95.70% accuracy on average, Blink is surprisingly challenging for existing multimodal LLMs: even the best-performing GPT-4V and Gemini achieve accuracies of 51.26% and 45.72%, only 13.17% and 7.63% higher than random guessing, indicating that such perception abilities have not "emerged" yet in recent multimodal LLMs. Our analysis also highlights that specialist CV models could solve these problems much better, suggesting potential pathways for future improvements. We believe Blink will stimulate the community to help multimodal LLMs catch up with human-level visual perception.

[Arxiv](https://arxiv.org/abs/2404.12390)