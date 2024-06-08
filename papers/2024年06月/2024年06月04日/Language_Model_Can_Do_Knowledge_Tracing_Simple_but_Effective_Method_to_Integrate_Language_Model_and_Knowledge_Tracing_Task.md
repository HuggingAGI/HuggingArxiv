# 语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。

发布时间：2024年06月04日

`LLM应用

这篇论文摘要描述了一种基于预训练语言模型（PLMs）的知识追踪（KT）框架，称为LKT。该框架利用语言模型的能力来捕捉文本数据中的语义信息，并将其应用于知识追踪任务中，以提高模型的性能和可解释性。这种方法特别强调了利用文本数据的优势，并解决了传统KT模型在处理文本信息方面的不足。因此，这篇论文属于LLM应用类别，因为它展示了如何将大型语言模型应用于特定的实际问题（知识追踪）中，并取得了显著的效果。` `知识追踪`

> Language Model Can Do Knowledge Tracing: Simple but Effective Method to Integrate Language Model and Knowledge Tracing Task

# 摘要

> 知识追踪（KT）对于在线学习至关重要，它旨在模拟学生的知识随时间的发展。尽管深度学习驱动的KT模型取得了显著成就，但它们主要依赖数字序列数据，未能充分利用问题和概念文本中的丰富语义信息。为此，我们提出了基于语言模型的知识追踪（LKT），这一创新框架巧妙融合了预训练语言模型（PLMs）与KT技术。LKT借助语言模型的强大能力，精准捕捉语义信息，有效整合文本数据，大幅超越了以往的KT模型，在多个大型基准数据集上表现卓越。此外，LKT通过PLMs捕获的语义知识，成功解决了KT中的冷启动问题。得益于丰富的文本数据，LKT的可解释性优于传统KT模型。我们采用局部可解释模型无关解释技术，并分析了注意力分数，以深入解读模型性能。本研究不仅展示了PLMs与KT结合的巨大潜力，也为KT领域的未来研究指明了方向。

> Knowledge Tracing (KT) is a critical task in online learning for modeling student knowledge over time. Despite the success of deep learning-based KT models, which rely on sequences of numbers as data, most existing approaches fail to leverage the rich semantic information in the text of questions and concepts. This paper proposes Language model-based Knowledge Tracing (LKT), a novel framework that integrates pre-trained language models (PLMs) with KT methods. By leveraging the power of language models to capture semantic representations, LKT effectively incorporates textual information and significantly outperforms previous KT models on large benchmark datasets. Moreover, we demonstrate that LKT can effectively address the cold-start problem in KT by leveraging the semantic knowledge captured by PLMs. Interpretability of LKT is enhanced compared to traditional KT models due to its use of text-rich data. We conducted the local interpretable model-agnostic explanation technique and analysis of attention scores to interpret the model performance further. Our work highlights the potential of integrating PLMs with KT and paves the way for future research in KT domain.

![语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。](../../../paper_images/2406.02893/x1.png)

![语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。](../../../paper_images/2406.02893/x2.png)

![语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。](../../../paper_images/2406.02893/x3.png)

![语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。](../../../paper_images/2406.02893/cold_start_zero_shot_bigfont_2.png)

![语言模型助力知识追踪：一种简洁高效的方法，融合语言模型于知识追踪任务之中。](../../../paper_images/2406.02893/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02893)