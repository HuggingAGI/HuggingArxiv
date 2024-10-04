# LLM 隐藏的知识比它们展示的更多：探讨 LLM 幻觉的内在机制

发布时间：2024年10月03日

`LLM理论` `人工智能`

> LLMs Know More Than They Show: On the Intrinsic Representation of LLM Hallucinations

# 摘要

> 大型语言模型（LLM）常出现事实错误、偏见和推理失败等“幻觉”问题。最新研究发现，LLM 内部状态蕴含着输出真实性的信息，可用于错误检测。我们发现，LLM 内部表示比预期更富含真实性信息。首先，真实性信息集中于特定标记，利用此特性可大幅提升错误检测效果。然而，这类检测器跨数据集泛化能力不足，表明真实性编码并非普适，而是多维度的。此外，内部表示还能预测模型可能的错误类型，助力定制化缓解策略。最后，我们揭示了 LLM 内部编码与实际输出间的矛盾：模型可能“知道”正确答案，却总是给出错误答案。这些发现从模型内部视角深化了对 LLM 错误的理解，为未来提升错误分析与缓解提供了方向。

> Large language models (LLMs) often produce errors, including factual inaccuracies, biases, and reasoning failures, collectively referred to as "hallucinations". Recent studies have demonstrated that LLMs' internal states encode information regarding the truthfulness of their outputs, and that this information can be utilized to detect errors. In this work, we show that the internal representations of LLMs encode much more information about truthfulness than previously recognized. We first discover that the truthfulness information is concentrated in specific tokens, and leveraging this property significantly enhances error detection performance. Yet, we show that such error detectors fail to generalize across datasets, implying that -- contrary to prior claims -- truthfulness encoding is not universal but rather multifaceted. Next, we show that internal representations can also be used for predicting the types of errors the model is likely to make, facilitating the development of tailored mitigation strategies. Lastly, we reveal a discrepancy between LLMs' internal encoding and external behavior: they may encode the correct answer, yet consistently generate an incorrect one. Taken together, these insights deepen our understanding of LLM errors from the model's internal perspective, which can guide future research on enhancing error analysis and mitigation.

[Arxiv](https://arxiv.org/abs/2410.02707)