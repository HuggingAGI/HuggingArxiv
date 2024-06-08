# 借助人类错误标记，引导大型语言模型自我修正机器翻译

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在专业领域机器翻译中的应用，特别是在结合人工错误标记和后编辑翻译记忆（PE-TM）的情况下，如何提高翻译质量和术语准确性。这种方法涉及人工和机器智能的结合，旨在优化LLM在特定领域的性能。因此，它属于LLM应用类别，因为它关注的是LLM在实际翻译任务中的应用和改进。` `语言服务`

> Prompting Large Language Models with Human Error Markings for Self-Correcting Machine Translation

# 摘要

> 大型语言模型（LLMs）虽在通用文本的机器翻译（MT）中表现卓越，但在专业领域，仍需后编辑（PE）来修正错误并提升术语翻译质量。本研究探索了一种轻量级的两步法：首先，人类翻译者在翻译初稿中标记错误；随后，从后编辑翻译记忆（PE-TM）中提取类似案例，以引导LLM进行修正。实验结果显示，这种结合人工错误标记的方法，使LLM更精准地修正错误，显著优于自动后编辑（APE）及全新翻译。

> While large language models (LLMs) pre-trained on massive amounts of unpaired language data have reached the state-of-the-art in machine translation (MT) of general domain texts, post-editing (PE) is still required to correct errors and to enhance term translation quality in specialized domains. In this paper we present a pilot study of enhancing translation memories (TM) produced by PE (source segments, machine translations, and reference translations, henceforth called PE-TM) for the needs of correct and consistent term translation in technical domains.
  We investigate a light-weight two-step scenario where, at inference time, a human translator marks errors in the first translation step, and in a second step a few similar examples are extracted from the PE-TM to prompt an LLM. Our experiment shows that the additional effort of augmenting translations with human error markings guides the LLM to focus on a correction of the marked errors, yielding consistent improvements over automatic PE (APE) and MT from scratch.

[Arxiv](https://arxiv.org/abs/2406.02267)