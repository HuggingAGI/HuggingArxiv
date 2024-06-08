# 语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。

发布时间：2024年06月04日

`Agent

这篇论文主要介绍了基于语言模型的知识追踪（LKT）框架，该框架结合了预训练语言模型（PLMs）与知识追踪技术，以提高对学生在线学习过程中知识掌握情况的模拟能力。这种结合利用了语言模型的语义捕捉能力，有效整合了文本信息，并在多个数据集上超越了传统模型。此外，LKT还解决了KT领域的冷启动问题，并提供了优于传统模型的可解释性。因此，这篇论文更符合Agent分类，因为它涉及的是一个智能系统（Agent）如何利用语言模型来优化其任务执行，即知识追踪。` `知识追踪`

> Language Model Can Do Knowledge Tracing: Simple but Effective Method to Integrate Language Model and Knowledge Tracing Task

# 摘要

> 知识追踪（KT）是模拟学生在线学习过程中知识掌握情况的关键任务。尽管深度学习驱动的KT模型已取得显著成果，但它们主要依赖数字序列数据，未能充分利用问题和概念文本中的丰富语义信息。本文创新性地提出了基于语言模型的知识追踪（LKT）框架，该框架巧妙融合了预训练语言模型（PLMs）与KT技术。LKT借助语言模型的强大语义捕捉能力，有效整合文本信息，大幅超越了传统KT模型在多个大型数据集上的表现。此外，LKT通过PLMs捕获的语义知识，有效解决了KT领域的冷启动问题。得益于丰富的文本数据，LKT的可解释性优于传统模型。我们通过局部可解释模型无关解释技术和注意力得分分析，深入解读了LKT的性能。本研究不仅展示了PLMs与KT结合的巨大潜力，也为该领域的未来探索指明了方向。

> Knowledge Tracing (KT) is a critical task in online learning for modeling student knowledge over time. Despite the success of deep learning-based KT models, which rely on sequences of numbers as data, most existing approaches fail to leverage the rich semantic information in the text of questions and concepts. This paper proposes Language model-based Knowledge Tracing (LKT), a novel framework that integrates pre-trained language models (PLMs) with KT methods. By leveraging the power of language models to capture semantic representations, LKT effectively incorporates textual information and significantly outperforms previous KT models on large benchmark datasets. Moreover, we demonstrate that LKT can effectively address the cold-start problem in KT by leveraging the semantic knowledge captured by PLMs. Interpretability of LKT is enhanced compared to traditional KT models due to its use of text-rich data. We conducted the local interpretable model-agnostic explanation technique and analysis of attention scores to interpret the model performance further. Our work highlights the potential of integrating PLMs with KT and paves the way for future research in KT domain.

![语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。](../../../paper_images/2406.02893/x1.png)

![语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。](../../../paper_images/2406.02893/x2.png)

![语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。](../../../paper_images/2406.02893/x3.png)

![语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。](../../../paper_images/2406.02893/cold_start_zero_shot_bigfont_2.png)

![语言模型助力知识追踪：一种简洁高效的方法，巧妙融合语言模型与知识追踪任务。](../../../paper_images/2406.02893/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02893)