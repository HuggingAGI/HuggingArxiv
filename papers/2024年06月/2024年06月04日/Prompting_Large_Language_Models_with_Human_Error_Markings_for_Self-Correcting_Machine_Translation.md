# 借助人类错误标记，引导大型语言模型自我修正机器翻译

发布时间：2024年06月04日

`LLM应用

论文摘要：大型语言模型（LLMs）虽在通用文本的机器翻译（MT）中表现卓越，但在专业领域，仍需后编辑（PE）来修正错误并提升术语翻译质量。本文介绍了一项针对通过后编辑（PE）增强的翻译记忆库（TM）（包括源片段、机器翻译及参考翻译，统称PE-TM）的初步研究，旨在确保技术领域术语翻译的准确性与一致性。我们提出了一种轻量级的两步法：首先，利用LLMs生成初步翻译，然后通过PE-TM进行后编辑，以优化术语使用和翻译质量。我们的实验结果表明，这种方法能显著提高专业术语的翻译准确性和一致性，同时保持翻译流程的高效性。本研究不仅为专业领域的机器翻译提供了新的视角，也为LLMs在特定领域的应用提供了实践指导。` `技术领域`

> Prompting Large Language Models with Human Error Markings for Self-Correcting Machine Translation

# 摘要

> 大型语言模型（LLMs）虽在通用文本的机器翻译（MT）中表现卓越，但在专业领域，仍需后编辑（PE）来修正错误并提升术语翻译质量。本文介绍了一项针对通过后编辑（PE）增强的翻译记忆库（TM）（包括源片段、机器翻译及参考翻译，统称PE-TM）的初步研究，旨在确保技术领域术语翻译的准确性与一致性。我们提出了一种轻量级的两步法：

> While large language models (LLMs) pre-trained on massive amounts of unpaired language data have reached the state-of-the-art in machine translation (MT) of general domain texts, post-editing (PE) is still required to correct errors and to enhance term translation quality in specialized domains. In this paper we present a pilot study of enhancing translation memories (TM) produced by PE (source segments, machine translations, and reference translations, henceforth called PE-TM) for the needs of correct and consistent term translation in technical domains.
  We investigate a light-weight two-step scenario where, at inference time, a human translator marks errors in the first translation step, and in a second step a few similar examples are extracted from the PE-TM to prompt an LLM. Our experiment shows that the additional effort of augmenting translations with human error markings guides the LLM to focus on a correction of the marked errors, yielding consistent improvements over automatic PE (APE) and MT from scratch.

[Arxiv](https://arxiv.org/abs/2406.02267)