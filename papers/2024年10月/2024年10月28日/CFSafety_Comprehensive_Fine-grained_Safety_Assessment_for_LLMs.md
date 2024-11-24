# CFSafety：对大型语言模型的全面且精细的安全评估

发布时间：2024年10月28日

`LLM应用` `语言模型` `安全评估`

> CFSafety: Comprehensive Fine-grained Safety Assessment for LLMs

# 摘要

> 随着大型语言模型（LLMs）快速演进，它们给我们的工作和日常生活带来了巨大便利，可同时也引入了诸多安全风险。这些模型会生成具有社会偏见或不道德内容的文本，在特定的对抗性指令下，甚至可能煽动非法活动。所以，对LLMs进行严格的安全评估极为关键。在此次研究中，我们引入了一个名为CFSafety的安全评估基准，它融合了5个经典安全场景和5种指令攻击，共计10类安全问题，从而构成了一个包含25000个提示的测试集。此测试集用于评估LLMs的自然语言生成（NLG）能力，通过简单的道德判断和1至5的安全评级量表进行评分。运用这个基准，我们测试了包括GPT系列在内的八个热门LLMs。结果显示，尽管GPT-4的安全性能出色，但包括该模型在内的LLMs的安全有效性仍有待提高。与本研究相关的数据和代码在GitHub上可获取。

> As large language models (LLMs) rapidly evolve, they bring significant conveniences to our work and daily lives, but also introduce considerable safety risks. These models can generate texts with social biases or unethical content, and under specific adversarial instructions, may even incite illegal activities. Therefore, rigorous safety assessments of LLMs are crucial. In this work, we introduce a safety assessment benchmark, CFSafety, which integrates 5 classic safety scenarios and 5 types of instruction attacks, totaling 10 categories of safety questions, to form a test set with 25k prompts. This test set was used to evaluate the natural language generation (NLG) capabilities of LLMs, employing a combination of simple moral judgment and a 1-5 safety rating scale for scoring. Using this benchmark, we tested eight popular LLMs, including the GPT series. The results indicate that while GPT-4 demonstrated superior safety performance, the safety effectiveness of LLMs, including this model, still requires improvement. The data and code associated with this study are available on GitHub.

[Arxiv](https://arxiv.org/abs/2410.21695)