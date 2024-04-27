# BLINK：多模态的大型语言模型具备视觉能力，但尚未达到深层感知的水平。

发布时间：2024年04月24日

`分类：LLM应用` `计算机视觉` `人工智能`

> BLINK: Multimodal Large Language Models Can See but Not Perceive

# 摘要

> 我们推出了 Blink，这是一项针对多模态语言模型（LLMs）的新基准测试，它专注于其他测试中未涵盖的核心视觉感知技能。这些任务对人类来说易如反掌，例如相对深度的估计、视觉匹配、法医侦查和多视角推理。然而，这些对视觉感知能力要求极高的任务对现有的多模态 LLMs 构成了显著挑战，因为它们不易通过自然语言进行中介。Blink 将 14 项经典的计算机视觉任务转化为 3,807 道多项选择题，每题配有一张或多张图片和视觉提示。尽管人类平均正确率高达 95.70%，但对于现有的多模态 LLMs 来说，Blink 却异常艰难：即便是表现最佳的 GPT-4V 和 Gemini，其准确率也仅为 51.26% 和 45.72%，仅比随机猜测高出 13.17% 和 7.63%，这表明这些模型尚未真正“掌握”这些视觉感知能力。我们的分析还指出，专业的计算机视觉（CV）模型能更有效地解决这些问题，为未来的技术进步提供了可能的路径。我们认为，Blink 将激励社区推动多模态 LLMs 在视觉感知方面达到人类的水平。

> We introduce Blink, a new benchmark for multimodal language models (LLMs) that focuses on core visual perception abilities not found in other evaluations. Most of the Blink tasks can be solved by humans "within a blink" (e.g., relative depth estimation, visual correspondence, forensics detection, and multi-view reasoning). However, we find these perception-demanding tasks cast significant challenges for current multimodal LLMs because they resist mediation through natural language. Blink reformats 14 classic computer vision tasks into 3,807 multiple-choice questions, paired with single or multiple images and visual prompting. While humans get 95.70% accuracy on average, Blink is surprisingly challenging for existing multimodal LLMs: even the best-performing GPT-4V and Gemini achieve accuracies of 51.26% and 45.72%, only 13.17% and 7.63% higher than random guessing, indicating that such perception abilities have not "emerged" yet in recent multimodal LLMs. Our analysis also highlights that specialist CV models could solve these problems much better, suggesting potential pathways for future improvements. We believe Blink will stimulate the community to help multimodal LLMs catch up with human-level visual perception.

[Arxiv](https://arxiv.org/abs/2404.12390)