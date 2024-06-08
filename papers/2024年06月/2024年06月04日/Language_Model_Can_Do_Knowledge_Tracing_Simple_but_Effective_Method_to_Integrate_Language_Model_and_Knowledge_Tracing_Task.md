# 语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。

发布时间：2024年06月04日

`Agent

理由：这篇论文主要介绍了一种新的知识追踪（KT）框架，即基于语言模型的知识追踪（LKT），它利用预训练语言模型（PLMs）来更好地理解和追踪学生的知识发展。这种框架可以被视为一个智能代理（Agent），因为它能够处理和分析学生的学习数据，并据此做出决策或提供反馈。此外，论文中提到的LKT模型通过其处理文本数据的能力，增强了模型的可解释性和性能，这与Agent的功能和目标相符，即通过智能处理数据来优化决策过程。因此，这篇论文更适合归类为Agent。` `知识追踪`

> Language Model Can Do Knowledge Tracing: Simple but Effective Method to Integrate Language Model and Knowledge Tracing Task

# 摘要

> 知识追踪（KT）对于在线学习至关重要，它旨在模拟学生的知识随时间的发展。尽管深度学习驱动的KT模型取得了显著成就，但它们主要依赖数字序列数据，未能充分利用问题和概念文本中的丰富语义信息。本文创新性地提出了基于语言模型的知识追踪（LKT），这一框架巧妙地将预训练语言模型（PLMs）融入KT实践中。LKT借助语言模型的强大能力，精准捕捉语义信息，有效融合文本数据，大幅超越了以往的KT模型，在多个大型数据集上表现卓越。此外，LKT通过PLMs捕获的语义知识，成功解决了KT领域的冷启动难题。得益于丰富的文本数据，LKT的可解释性远超传统KT模型。我们通过局部可解释模型无关解释技术和注意力分数分析，深入揭示了模型性能。本研究不仅展示了PLMs与KT结合的巨大潜力，也为KT领域的未来探索指明了方向。

> Knowledge Tracing (KT) is a critical task in online learning for modeling student knowledge over time. Despite the success of deep learning-based KT models, which rely on sequences of numbers as data, most existing approaches fail to leverage the rich semantic information in the text of questions and concepts. This paper proposes Language model-based Knowledge Tracing (LKT), a novel framework that integrates pre-trained language models (PLMs) with KT methods. By leveraging the power of language models to capture semantic representations, LKT effectively incorporates textual information and significantly outperforms previous KT models on large benchmark datasets. Moreover, we demonstrate that LKT can effectively address the cold-start problem in KT by leveraging the semantic knowledge captured by PLMs. Interpretability of LKT is enhanced compared to traditional KT models due to its use of text-rich data. We conducted the local interpretable model-agnostic explanation technique and analysis of attention scores to interpret the model performance further. Our work highlights the potential of integrating PLMs with KT and paves the way for future research in KT domain.

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。](../../../paper_images/2406.02893/x1.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。](../../../paper_images/2406.02893/x2.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。](../../../paper_images/2406.02893/x3.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。](../../../paper_images/2406.02893/cold_start_zero_shot_bigfont_2.png)

![语言模型助力知识追踪：一种简洁高效的方法，将语言模型与知识追踪任务巧妙结合。](../../../paper_images/2406.02893/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02893)