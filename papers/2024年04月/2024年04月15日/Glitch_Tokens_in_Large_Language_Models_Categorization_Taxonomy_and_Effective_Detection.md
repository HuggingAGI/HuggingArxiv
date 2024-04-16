# 大型语言模型里，错误标记的分类及其检测策略。

发布时间：2024年04月15日

`LLM应用` `语言模型` `分词工具`

> Glitch Tokens in Large Language Models: Categorization Taxonomy and Effective Detection

# 摘要

> 随着大型语言模型（LLMs）在众多领域的应用日益广泛，深入探究它们潜在的异常行为及其后果变得尤为重要。本研究首次系统性地研究了“故障标记”这一现象，这些异常的标记由现有的分词工具生成，可能会影响模型输出的质量。我们针对七种广泛使用的LLMs进行了实验，运用了三种不同的分词工具，分析了共计182,517个标记。我们对发现的故障标记进行了分类，并描述了LLMs在处理这些故障标记时的异常表现。鉴于故障标记在嵌入空间中的聚集特性，我们提出了GlitchHunter，这是一种创新的迭代聚类方法，旨在有效识别故障标记。实验结果显示，我们的检测方法在八个开源LLMs上的表现远超三种传统基线方法。这项研究不仅首次全面剖析了故障标记问题，还为减少LLMs中分词错误提供了新的视角和方法。

> With the expanding application of Large Language Models (LLMs) in various domains, it becomes imperative to comprehensively investigate their unforeseen behaviors and consequent outcomes. In this study, we introduce and systematically explore the phenomenon of "glitch tokens", which are anomalous tokens produced by established tokenizers and could potentially compromise the models' quality of response. Specifically, we experiment on seven top popular LLMs utilizing three distinct tokenizers and involving a totally of 182,517 tokens. We present categorizations of the identified glitch tokens and symptoms exhibited by LLMs when interacting with glitch tokens. Based on our observation that glitch tokens tend to cluster in the embedding space, we propose GlitchHunter, a novel iterative clustering-based technique, for efficient glitch token detection. The evaluation shows that our approach notably outperforms three baseline methods on eight open-source LLMs. To the best of our knowledge, we present the first comprehensive study on glitch tokens. Our new detection further provides valuable insights into mitigating tokenization-related errors in LLMs.

[Arxiv](https://arxiv.org/abs/2404.09894)