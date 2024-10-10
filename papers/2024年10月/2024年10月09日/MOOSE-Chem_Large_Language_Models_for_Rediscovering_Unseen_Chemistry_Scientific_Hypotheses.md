# MOOSE-Chem：利用大型语言模型，探索并重新发现那些尚未被揭示的化学科学假设。

发布时间：2024年10月09日

`LLM应用` `科学研究`

> MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses

# 摘要

> 科学发现推动了人类社会的繁荣，而大型语言模型（LLMs）的最新进展显示，它们可能加速这一进程。然而，LLMs在化学领域能否发现新颖且有效的假设仍是个谜。我们探讨的核心问题是：在仅提供化学研究背景的情况下，LLMs能否自动生成新颖且有效的化学假设，且不受研究领域的限制？通过与化学专家的深入讨论，我们假设大多数化学假设源于研究背景和几个灵感。基于此，我们将核心问题细化为三个基本问题：（1）LLMs能否从背景问题中提取灵感；（2）结合背景和灵感，LLMs能否生成假设；（3）LLMs能否识别并优先考虑优质假设。为验证这些问题，我们构建了一个包含51篇顶级期刊化学论文的基准，每篇论文由化学博士生分为背景、灵感和假设三部分。我们的目标是仅利用背景和随机选择的化学文献语料库，通过截至2023年训练的LLMs重新发现假设。此外，我们设计了一个基于LLM的多代理框架，分三个阶段解决上述问题。实验结果显示，该方法能高度相似地重新发现许多真实假设，涵盖了主要创新点。

> Scientific discovery contributes largely to human society's prosperity, and recent progress shows that LLMs could potentially catalyze this process. However, it is still unclear whether LLMs can discover novel and valid hypotheses in chemistry. In this work, we investigate this central research question: Can LLMs automatically discover novel and valid chemistry research hypotheses given only a chemistry research background (consisting of a research question and/or a background survey), without limitation on the domain of the research question? After extensive discussions with chemistry experts, we propose an assumption that a majority of chemistry hypotheses can be resulted from a research background and several inspirations. With this key insight, we break the central question into three smaller fundamental questions. In brief, they are: (1) given a background question, whether LLMs can retrieve good inspirations; (2) with background and inspirations, whether LLMs can lead to hypothesis; and (3) whether LLMs can identify good hypotheses to rank them higher. To investigate these questions, we construct a benchmark consisting of 51 chemistry papers published in Nature, Science, or a similar level in 2024 (all papers are only available online since 2024). Every paper is divided by chemistry PhD students into three components: background, inspirations, and hypothesis. The goal is to rediscover the hypothesis, given only the background and a large randomly selected chemistry literature corpus consisting the ground truth inspiration papers, with LLMs trained with data up to 2023. We also develop an LLM-based multi-agent framework that leverages the assumption, consisting of three stages reflecting the three smaller questions. The proposed method can rediscover many hypotheses with very high similarity with the ground truth ones, covering the main innovations.

[Arxiv](https://arxiv.org/abs/2410.07076)