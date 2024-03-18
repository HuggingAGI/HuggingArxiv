# [FaaF：提出“事实即函数”方法，用于评估 RAG 系统的表现。](https://arxiv.org/abs/2403.03888)

发布时间：2024年03月06日

`RAG`

> FaaF: Facts as a Function for the evaluation of RAG systems

> 针对RAG系统的性能评估，能否准确从参考源检索并回忆事实至关重要，这关乎其检索与生成的双重品质。尽管如此，如何确保这一评估过程既可靠又高效仍是一个棘手问题。尽管已有研究致力于通过提示语言模型（LM）进行事实验证，但在面对信息残缺或错误时，这些方法的可靠性打了折扣。为此，我们引入了一种名为“Facts as a Function”（FaaF）的新颖事实验证方案，它巧妙运用了LM的功能调用机制，并构建了一个用于RAG系统事实回忆评估的框架。相较于传统的基于提示的方法，FaaF在面对信息不完整的文本时，能显著提升识别出缺乏依据事实的能力，同时还能大幅提升效率、降低成本数倍。

> Factual recall from a reference source is crucial for evaluating the performance of Retrieval Augmented Generation (RAG) systems, as it directly probes into the quality of both retrieval and generation. However, it still remains a challenge to perform this evaluation reliably and efficiently. Recent work has focused on fact verification via prompting language model (LM) evaluators, however we demonstrate that these methods are unreliable in the presence of incomplete or inaccurate information. We introduce Facts as a Function (FaaF), a new approach to fact verification that utilizes the function calling abilities of LMs and a framework for RAG factual recall evaluation. FaaF substantially improves the ability of LMs to identify unsupported facts in text with incomplete information whilst improving efficiency and lowering cost by several times, compared to prompt-based approaches.

[Arxiv](https://arxiv.org/abs/2403.03888)