# WaterPark：对语言模型水印的鲁棒性评估

发布时间：2024年11月20日

`LLM应用` `语言模型` `水印技术`

> WaterPark: A Robustness Assessment of Language Model Watermarking

# 摘要

> 为减轻大型语言模型（LLMs）被滥用的情况，比如传播虚假信息、自动网络钓鱼以及学术作弊等，迫切需要拥有识别 LLM 生成文本的能力。水印技术成为颇具前景的解决方案：它在 LLM 的生成过程中植入统计信号，随后验证 LLM 是否生成了给定的文本。各类水印方法（“水印器”）已被提出；然而，因缺乏统一的评估平台，诸多关键问题尚未得到充分探究：其一，各种水印器的长处与局限是什么，尤其是它们的抗攻击能力？其二，各种设计选择如何影响其鲁棒性？其三，如何在对抗环境中最优地操作水印器？
  为填补这一空缺，我们对现有的 LLM 水印器和水印去除攻击加以系统化，描绘出它们的设计空间。接着，我们开发出 WaterPark，这是一个集成了 10 种先进水印器和 12 种代表性攻击的统一平台。更为重要的是，借助 WaterPark，我们对现有的水印器展开了全面评估，揭示出各种设计选择对其抗攻击能力的影响。例如，水印器抵御日益强烈攻击的能力取决于其对上下文的依赖程度。我们进一步探索了在对抗环境中操作水印器的最佳实践。比如，将通用检测器与特定于水印的检测器配合使用，能够提升易受攻击的水印器的安全性。我们认为，我们的研究为当前的 LLM 水印技术带来了启示，而 WaterPark 则作为一个宝贵的测试平台，有助于推动未来的研究。

> To mitigate the misuse of large language models (LLMs), such as disinformation, automated phishing, and academic cheating, there is a pressing need for the capability of identifying LLM-generated texts. Watermarking emerges as one promising solution: it plants statistical signals into LLMs' generative processes and subsequently verifies whether LLMs produce given texts. Various watermarking methods (``watermarkers'') have been proposed; yet, due to the lack of unified evaluation platforms, many critical questions remain under-explored: i) What are the strengths/limitations of various watermarkers, especially their attack robustness? ii) How do various design choices impact their robustness? iii) How to optimally operate watermarkers in adversarial environments?
  To fill this gap, we systematize existing LLM watermarkers and watermark removal attacks, mapping out their design spaces. We then develop WaterPark, a unified platform that integrates 10 state-of-the-art watermarkers and 12 representative attacks. More importantly, leveraging WaterPark, we conduct a comprehensive assessment of existing watermarkers, unveiling the impact of various design choices on their attack robustness. For instance, a watermarker's resilience to increasingly intensive attacks hinges on its context dependency. We further explore the best practices to operate watermarkers in adversarial environments. For instance, using a generic detector alongside a watermark-specific detector improves the security of vulnerable watermarkers. We believe our study sheds light on current LLM watermarking techniques while WaterPark serves as a valuable testbed to facilitate future research.

[Arxiv](https://arxiv.org/abs/2411.13425)