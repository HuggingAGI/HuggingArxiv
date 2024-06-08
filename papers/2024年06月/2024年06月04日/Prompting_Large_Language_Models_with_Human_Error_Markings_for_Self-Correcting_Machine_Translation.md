# 借助人类错误标记，引导大型语言模型自我修正，提升机器翻译质量

发布时间：2024年06月04日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在专业领域机器翻译中的应用，特别是在结合人类翻译者的智慧来提升翻译质量的方法。论文提出了一种两步法，首先由人类翻译者识别和标记翻译错误，然后利用从后期编辑翻译记忆库（PE-TM）中提取的类似案例来引导LLM进行修正。这种方法通过结合人类的专业知识和LLM的能力，显著提高了翻译质量。因此，这篇论文属于LLM应用分类，因为它专注于LLM在特定应用场景（即专业领域的机器翻译）中的实际应用和改进。` `语言服务`

> Prompting Large Language Models with Human Error Markings for Self-Correcting Machine Translation

# 摘要

> 大型语言模型（LLMs）虽在通用文本的机器翻译上已达到顶尖水平，但在专业领域，仍需后期编辑（PE）以精炼术语翻译。本文探索了一种高效的两步法：首先，人类翻译者识别并标记翻译错误；随后，从PE-TM中提取类似案例，引导LLM修正。实验证明，这种结合人类智慧的翻译增强方法，显著提升了翻译质量，超越了单纯的自动后期编辑和基础机器翻译。

> While large language models (LLMs) pre-trained on massive amounts of unpaired language data have reached the state-of-the-art in machine translation (MT) of general domain texts, post-editing (PE) is still required to correct errors and to enhance term translation quality in specialized domains. In this paper we present a pilot study of enhancing translation memories (TM) produced by PE (source segments, machine translations, and reference translations, henceforth called PE-TM) for the needs of correct and consistent term translation in technical domains.
  We investigate a light-weight two-step scenario where, at inference time, a human translator marks errors in the first translation step, and in a second step a few similar examples are extracted from the PE-TM to prompt an LLM. Our experiment shows that the additional effort of augmenting translations with human error markings guides the LLM to focus on a correction of the marked errors, yielding consistent improvements over automatic PE (APE) and MT from scratch.

[Arxiv](https://arxiv.org/abs/2406.02267)