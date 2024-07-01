# AnomaLLMy —— 通过低置信单令牌预测，在黑盒 LLM 中识别异常令牌

发布时间：2024年06月28日

`LLM应用` `人工智能` `软件开发`

> AnomaLLMy -- Detecting anomalous tokens in black-box LLMs through low-confidence single-token predictions

# 摘要

> 本文引入了 AnomaLLMy 技术，该技术能自动检测仅通过 API 访问的 LLM 中的异常标记。通过低置信度的单标记预测，AnomaLLMy 有效识别模型行为中的异常，从而提升模型质量和可靠性。在 GPT-4 的 cl100k_base 数据集上，该技术成功检测出 413 个主要和 65 个次要异常，且成本仅为 24.39 美元。这些发现有望进一步增强 LLM 的鲁棒性和准确性，尤其是在标记器的开发与评估领域。

> This paper introduces AnomaLLMy, a novel technique for the automatic detection of anomalous tokens in black-box Large Language Models (LLMs) with API-only access. Utilizing low-confidence single-token predictions as a cost-effective indicator, AnomaLLMy identifies irregularities in model behavior, addressing the issue of anomalous tokens degrading the quality and reliability of models. Validated on the cl100k_base dataset, the token set of GPT-4, AnomaLLMy detected 413 major and 65 minor anomalies, demonstrating the method's efficiency with just \$24.39 spent in API credits. The insights from this research are expected to be beneficial for enhancing the robustness of and accuracy of LLMs, particularly in the development and assessment of tokenizers.

[Arxiv](https://arxiv.org/abs/2406.19840)