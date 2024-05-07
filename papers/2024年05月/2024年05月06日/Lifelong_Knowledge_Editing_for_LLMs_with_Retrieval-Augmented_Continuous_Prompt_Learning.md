# 在大型语言模型（LLMs）中，通过检索增强的连续提示学习方法，实现了终身知识的持续编辑与更新。

发布时间：2024年05月06日

`LLM应用` `人工智能` `机器学习`

> Lifelong Knowledge Editing for LLMs with Retrieval-Augmented Continuous Prompt Learning

# 摘要

> 模型编辑的目标是在不重新训练的情况下修正大型语言模型（LLMs）中的陈旧或错误信息。面对持续更新的LLMs，终身模型编辑成为了一项极具挑战性的任务。以往的研究多集中于单次或批量编辑，但在长期编辑过程中，由于知识遗忘和性能下降，这些方法往往力不从心。尽管基于检索的方法能够缓解这些问题，但其在将检索到的知识整合进模型时，过程缓慢且繁琐。本研究提出了RECIPE，一种结合了检索评估的连续提示学习方法，旨在提升终身学习中的编辑和推理效率。RECIPE将知识陈述转化为精炼且信息丰富的连续提示，这些提示会附加在LLM的输入查询嵌入前，以高效地提炼基于知识的响应。此外，它还整合了一个知识哨兵（KS），作为中介来计算动态阈值，判断检索库中是否存在相关知识。我们的检索器和提示编码器共同训练，以达到编辑的可靠性、通用性和局部性。在实验中，RECIPE在多个LLMs和编辑数据集上进行了全面评估，显示出卓越的编辑性能，并能保持LLMs的整体性能，同时具备快速的编辑和推理速度。

> Model editing aims to correct outdated or erroneous knowledge in large language models (LLMs) without the need for costly retraining. Lifelong model editing is the most challenging task that caters to the continuous editing requirements of LLMs. Prior works primarily focus on single or batch editing; nevertheless, these methods fall short in lifelong editing scenarios due to catastrophic knowledge forgetting and the degradation of model performance. Although retrieval-based methods alleviate these issues, they are impeded by slow and cumbersome processes of integrating the retrieved knowledge into the model. In this work, we introduce RECIPE, a RetriEval-augmented ContInuous Prompt lEarning method, to boost editing efficacy and inference efficiency in lifelong learning. RECIPE first converts knowledge statements into short and informative continuous prompts, prefixed to the LLM's input query embedding, to efficiently refine the response grounded on the knowledge. It further integrates the Knowledge Sentinel (KS) that acts as an intermediary to calculate a dynamic threshold, determining whether the retrieval repository contains relevant knowledge. Our retriever and prompt encoder are jointly trained to achieve editing properties, i.e., reliability, generality, and locality. In our experiments, RECIPE is assessed extensively across multiple LLMs and editing datasets, where it achieves superior editing performance. RECIPE also demonstrates its capability to maintain the overall performance of LLMs alongside showcasing fast editing and inference speed.

[Arxiv](https://arxiv.org/abs/2405.03279)