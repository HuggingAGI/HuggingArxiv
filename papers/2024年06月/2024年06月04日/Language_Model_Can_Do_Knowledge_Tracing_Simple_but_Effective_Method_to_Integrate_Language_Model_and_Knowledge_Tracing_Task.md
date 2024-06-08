# 语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。

发布时间：2024年06月04日

`LLM应用

这篇论文摘要描述了一种基于语言模型的知识追踪（LKT）框架，该框架结合了预训练语言模型（PLMs）与知识追踪技术。LKT利用语言模型的能力来捕捉文本的语义信息，并在知识追踪任务中取得了优于传统模型的性能。此外，LKT还解决了冷启动问题，并增强了模型的可解释性。这一研究展示了PLMs在知识追踪领域的应用潜力，并为该领域的未来研究提供了方向。因此，这篇论文属于“LLM应用”分类。` `知识追踪`

> Language Model Can Do Knowledge Tracing: Simple but Effective Method to Integrate Language Model and Knowledge Tracing Task

# 摘要

> 知识追踪（KT）对于在线学习至关重要，它旨在模拟学生的知识随时间的发展。尽管深度学习驱动的KT模型取得了显著成果，但它们主要依赖数字序列数据，未能充分利用问题和概念文本中的丰富语义信息。为此，我们提出了基于语言模型的知识追踪（LKT），这一创新框架巧妙融合了预训练语言模型（PLMs）与KT技术。LKT借助语言模型的强大能力，精准捕捉文本的语义信息，不仅在大型数据集上超越了以往的KT模型，还巧妙解决了KT中的冷启动问题。此外，LKT因其丰富的文本数据使用，相比传统KT模型，其可解释性大大增强。我们通过局部可解释模型无关解释技术和注意力得分分析，进一步揭示了模型的性能。本研究不仅展示了PLMs与KT结合的巨大潜力，也为KT领域的未来探索指明了方向。

> Knowledge Tracing (KT) is a critical task in online learning for modeling student knowledge over time. Despite the success of deep learning-based KT models, which rely on sequences of numbers as data, most existing approaches fail to leverage the rich semantic information in the text of questions and concepts. This paper proposes Language model-based Knowledge Tracing (LKT), a novel framework that integrates pre-trained language models (PLMs) with KT methods. By leveraging the power of language models to capture semantic representations, LKT effectively incorporates textual information and significantly outperforms previous KT models on large benchmark datasets. Moreover, we demonstrate that LKT can effectively address the cold-start problem in KT by leveraging the semantic knowledge captured by PLMs. Interpretability of LKT is enhanced compared to traditional KT models due to its use of text-rich data. We conducted the local interpretable model-agnostic explanation technique and analysis of attention scores to interpret the model performance further. Our work highlights the potential of integrating PLMs with KT and paves the way for future research in KT domain.

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。](../../../paper_images/2406.02893/x1.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。](../../../paper_images/2406.02893/x2.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。](../../../paper_images/2406.02893/x3.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。](../../../paper_images/2406.02893/cold_start_zero_shot_bigfont_2.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型融入知识追踪任务中。](../../../paper_images/2406.02893/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02893)