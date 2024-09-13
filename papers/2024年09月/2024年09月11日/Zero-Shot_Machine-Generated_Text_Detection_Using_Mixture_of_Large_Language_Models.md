# 利用大型语言模型混合技术，实现零-shot 机器生成文本的精准检测

发布时间：2024年09月11日

`LLM应用` `网络安全` `人工智能`

> Zero-Shot Machine-Generated Text Detection Using Mixture of Large Language Models

# 摘要

> 随着大规模训练的 LLM 及其强大文本生成能力的普及，生成式 AI 技术带来的威胁日益严重，降低了有害、虚假内容的制作成本。为此，人们提出了多种自动区分人工与人类文本的方案，通常将其视为分类问题。大多数方法依赖于精心挑选的检测器 LLM，认为低困惑度分数能可靠识别机器生成内容。然而，单一检测器可能存在性能脆弱性，因此我们采用了多检测器策略，并提出了一种新的、理论支撑的方法来整合它们的优势。实验结果显示，我们的方法显著提升了检测的鲁棒性。

> The dissemination of Large Language Models (LLMs), trained at scale, and endowed with powerful text-generating abilities has vastly increased the threats posed by generative AI technologies by reducing the cost of producing harmful, toxic, faked or forged content. In response, various proposals have been made to automatically discriminate artificially generated from human-written texts, typically framing the problem as a classification problem. Most approaches evaluate an input document by a well-chosen detector LLM, assuming that low-perplexity scores reliably signal machine-made content. As using one single detector can induce brittleness of performance, we instead consider several and derive a new, theoretically grounded approach to combine their respective strengths. Our experiments, using a variety of generator LLMs, suggest that our method effectively increases the robustness of detection.

[Arxiv](https://arxiv.org/abs/2409.07615)