# 语言模型和循环一致性用于自我反思的机器翻译

发布时间：2024年11月04日

`LLM应用` `机器翻译` `语言模型`

> Language Models and Cycle Consistency for Self-Reflective Machine Translation

# 摘要

> 这篇论文介绍了一个利用大型语言模型（LLM）进行机器翻译（MT）的新框架。我们从一个推测开始：一个理想的翻译应该包含完整和准确的信息，以便足够强大的 LLM 能够恢复原始句子。我们从源语言 A 生成多个到目标语言 B 的翻译候选，然后将这些候选翻译回原始语言 A。通过使用诸如标记级精度和准确性等指标评估原始句子和回译句子之间的循环一致性，我们在不知道语言 B 的真实情况的情况下，隐式地估计语言 B 中的翻译质量。这也有助于仅使用单语语料库评估 LLM 的翻译能力。对于每个源句子，我们将与原始句子具有最佳循环一致性的翻译候选确定为最终答案。我们的实验表明，更大的 LLM，或者在推理期间具有更多前向传递的相同 LLM，表现出增加的循环一致性，这与 LLM 模型大小缩放定律和测试时间计算缩放定律一致。这项工作提供了以下方法：1）隐式评估目标语言中句子的翻译质量，2）评估 LLM 进行任意语言到任意语言翻译的能力，3）如何为特定的 LLM 生成更好的翻译。

> This paper introduces a novel framework that leverages large language models (LLMs) for machine translation (MT). We start with one conjecture: an ideal translation should contain complete and accurate information for a strong enough LLM to recover the original sentence. We generate multiple translation candidates from a source language A to a target language B, and subsequently translate these candidates back to the original language A. By evaluating the cycle consistency between the original and back-translated sentences using metrics such as token-level precision and accuracy, we implicitly estimate the translation quality in language B, without knowing its ground-truth. This also helps to evaluate the LLM translation capability, only with monolingual corpora. For each source sentence, we identify the translation candidate with optimal cycle consistency with the original sentence as the final answer. Our experiments demonstrate that larger LLMs, or the same LLM with more forward passes during inference, exhibit increased cycle consistency, aligning with the LLM model size scaling law and test-time computation scaling law. This work provide methods for, 1) to implicitly evaluate translation quality of a sentence in the target language, 2), to evaluate capability of LLM for any-to-any-language translation, and 3), how to generate a better translation for a specific LLM.

[Arxiv](https://arxiv.org/abs/2411.02791)