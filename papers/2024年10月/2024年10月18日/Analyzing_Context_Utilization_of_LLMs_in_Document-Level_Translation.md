# 探究 LLM 在文档翻译中的上下文运用

发布时间：2024年10月18日

`LLM应用`

> Analyzing Context Utilization of LLMs in Document-Level Translation

# 摘要

> 大型语言模型 (LLM) 在机器翻译领域日益强大。我们专注于文档级翻译，探讨在没有外部句子上下文的情况下无法翻译的词汇。通过分析模型对上下文变化的适应性，我们评估了 LLM 利用上下文的能力。结果显示，尽管 LLM 在文档翻译上有所进步，但代词翻译的改进并不显著。因此，我们强调对 LLM 进行上下文感知的微调，特别是针对上下文的关键部分，以提升其在文档翻译中的可靠性。

> Large language models (LLM) are increasingly strong contenders in machine translation. We study document-level translation, where some words cannot be translated without context from outside the sentence. We investigate the ability of prominent LLMs to utilize context by analyzing models' robustness to perturbed and randomized document context. We find that LLMs' improved document-translation performance is not always reflected in pronoun translation performance. We highlight the need for context-aware finetuning of LLMs with a focus on relevant parts of the context to improve their reliability for document-level translation.

[Arxiv](https://arxiv.org/abs/2410.14391)