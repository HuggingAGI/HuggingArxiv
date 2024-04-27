# BLINK：虽然多模态的大型语言模型具备视觉识别能力，但它们却无法实现深层次的感知理解。

发布时间：2024年04月24日

`LLM应用` `计算机视觉` `人工智能`

> BLINK: Multimodal Large Language Models Can See but Not Perceive

# 摘要

> 我们推出了 Blink，这是一项针对多模态语言模型（LLMs）的新基准测试，旨在测试其他评测中未涉及的核心视觉感知技能。这些任务，如相对深度估计、视觉匹配、法医侦查和多视角推理，人类都能在瞬间解决。然而，我们发现这些对视觉感知要求极高的任务对当前的多模态 LLMs 构成了显著挑战，因为它们不容易通过自然语言来处理。Blink 将 14 个经典计算机视觉任务转化为 3,807 道多项选择题，每题都配有一张或多张图片和视觉提示。尽管人类平均正确率高达 95.70%，但 Blink 对现有多模态 LLMs 来说却颇具挑战性：即便是表现最佳的 GPT-4V 和 Gemini，准确率也仅为 51.26% 和 45.72%，仅比随机猜测高出 13.17% 和 7.63%，这表明这些感知技能在最新的多模态 LLMs 中尚未“显现”。我们的分析还指出，专业的计算机视觉模型能更好地解决这些问题，这为未来的提升指明了可能的方向。我们相信 Blink 将激励业界共同努力，推动多模态 LLMs 的视觉感知能力向人类水平看齐。

> We introduce Blink, a new benchmark for multimodal language models (LLMs) that focuses on core visual perception abilities not found in other evaluations. Most of the Blink tasks can be solved by humans "within a blink" (e.g., relative depth estimation, visual correspondence, forensics detection, and multi-view reasoning). However, we find these perception-demanding tasks cast significant challenges for current multimodal LLMs because they resist mediation through natural language. Blink reformats 14 classic computer vision tasks into 3,807 multiple-choice questions, paired with single or multiple images and visual prompting. While humans get 95.70% accuracy on average, Blink is surprisingly challenging for existing multimodal LLMs: even the best-performing GPT-4V and Gemini achieve accuracies of 51.26% and 45.72%, only 13.17% and 7.63% higher than random guessing, indicating that such perception abilities have not "emerged" yet in recent multimodal LLMs. Our analysis also highlights that specialist CV models could solve these problems much better, suggesting potential pathways for future improvements. We believe Blink will stimulate the community to help multimodal LLMs catch up with human-level visual perception.

[Arxiv](https://arxiv.org/abs/2404.12390)