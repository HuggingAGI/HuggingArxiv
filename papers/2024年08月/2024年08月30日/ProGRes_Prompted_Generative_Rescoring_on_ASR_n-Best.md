# ProGRes：针对 ASR n-Best 列表的提示生成重评分技术

发布时间：2024年08月30日

`LLM应用` `语音识别` `人工智能`

> ProGRes: Prompted Generative Rescoring on ASR n-Best

# 摘要

> 大型语言模型 (LLM) 通过有效重评分束搜索过程中的 n-最佳假设，显著提升了语音识别器的性能。然而，如何充分利用生成指令调整的 LLM 进行假设重评分仍是一个挑战。本文提出了一种创新方法，利用指令调整的 LLM 动态扩展 n-最佳语音识别假设，通过适当提示的 LLM 生成新假设。我们引入了一种结合置信度分数、LLM 序列评分和基于提示的假设生成的新零-shot 方法。通过比较 Llama-3-Instruct、GPT-3.5 Turbo 和 GPT-4 Turbo 作为基于提示的生成器与 Llama-3 作为序列评分 LLM，我们使用不同语音识别器进行了评估，并实现了单词错误率 (WER) 的显著相对改进，提升幅度达 5% 至 25%。

> Large Language Models (LLMs) have shown their ability to improve the performance of speech recognizers by effectively rescoring the n-best hypotheses generated during the beam search process. However, the best way to exploit recent generative instruction-tuned LLMs for hypothesis rescoring is still unclear. This paper proposes a novel method that uses instruction-tuned LLMs to dynamically expand the n-best speech recognition hypotheses with new hypotheses generated through appropriately-prompted LLMs. Specifically, we introduce a new zero-shot method for ASR n-best rescoring, which combines confidence scores, LLM sequence scoring, and prompt-based hypothesis generation. We compare Llama-3-Instruct, GPT-3.5 Turbo, and GPT-4 Turbo as prompt-based generators with Llama-3 as sequence scorer LLM. We evaluated our approach using different speech recognizers and observed significant relative improvement in the word error rate (WER) ranging from 5% to 25%.

[Arxiv](https://arxiv.org/abs/2409.00217)