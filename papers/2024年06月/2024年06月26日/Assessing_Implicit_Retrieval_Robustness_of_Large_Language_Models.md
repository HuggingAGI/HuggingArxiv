# 探究大型语言模型中“隐式”检索的稳健性评估

发布时间：2024年06月26日

`RAG

这篇论文主要探讨了检索增强生成（RAG）框架中大型语言模型的检索鲁棒性问题，并提出了一种通过微调模型来提高其在检索不准确情况下的性能的方法。这与RAG框架的核心目标紧密相关，即通过外部知识提升语言模型的性能。因此，将其归类为RAG是合适的。` `机器学习`

> Assessing "Implicit" Retrieval Robustness of Large Language Models

# 摘要

> 检索增强生成框架通过外部知识提升大型语言模型，日益受到青睐。但其效果取决于模型的检索鲁棒性。若模型检索鲁棒性不足，性能便受检索器准确性所限，一旦检索内容无关，性能便大打折扣。本文探讨了大型语言模型在无需明确判断检索内容相关性下，直接输出答案的“隐式”检索鲁棒性。研究发现，通过在黄金与干扰上下文混合数据上微调，模型能有效抵御检索不准确性，同时保持准确检索时的答案提取能力。这表明，大型语言模型能通过端到端学习最终答案，隐式应对检索内容的相关与否，无需额外引入明确的关联判断过程，从而保持方法的连贯性。

> Retrieval-augmented generation has gained popularity as a framework to enhance large language models with external knowledge. However, its effectiveness hinges on the retrieval robustness of the model. If the model lacks retrieval robustness, its performance is constrained by the accuracy of the retriever, resulting in significant compromises when the retrieved context is irrelevant. In this paper, we evaluate the "implicit" retrieval robustness of various large language models, instructing them to directly output the final answer without explicitly judging the relevance of the retrieved context. Our findings reveal that fine-tuning on a mix of gold and distracting context significantly enhances the model's robustness to retrieval inaccuracies, while still maintaining its ability to extract correct answers when retrieval is accurate. This suggests that large language models can implicitly handle relevant or irrelevant retrieved context by learning solely from the supervision of the final answer in an end-to-end manner. Introducing an additional process for explicit relevance judgment can be unnecessary and disrupts the end-to-end approach.

[Arxiv](https://arxiv.org/abs/2406.18134)