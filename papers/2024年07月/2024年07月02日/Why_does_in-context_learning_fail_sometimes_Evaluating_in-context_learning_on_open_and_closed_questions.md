# 为何 in-context learning 有时会失效？探讨其在开放与封闭问题上的表现。

发布时间：2024年07月02日

`LLM理论` `科学研究`

> Why does in-context learning fail sometimes? Evaluating in-context learning on open and closed questions

# 摘要

> 我们评估了in-context learning在开放与封闭问题中的表现，考虑了任务的新颖性和难度。为此，我们设计了一个包含复杂科学问题的创新基准，每个问题都附有不同相关性的背景信息。令人意外的是，与主题更契合的背景信息并不总是优于相关性较低的背景。这一现象在开放性问题和高难度或新颖问题中尤为显著。这一发现凸显了大型语言模型在处理不同类型问题时的根本差异，并强调了对in-context learning进行更全面评估的必要性。同时，这也引发了一个新问题：如何在检索增强生成（RAG）系统中为大型语言模型选择最优背景信息。我们的研究暗示，这一问题的答案可能高度依赖于具体应用，并可能受问题格式、难度感知以及信息的新颖性或流行度等因素影响。

> We measure the performance of in-context learning as a function of task novelty and difficulty for open and closed questions. For that purpose, we created a novel benchmark consisting of hard scientific questions, each paired with a context of various relevancy. We show that counter-intuitively, a context that is more aligned with the topic does not always help more than a less relevant context. This effect is especially visible for open questions and questions of high difficulty or novelty. This result reveals a fundamental difference between the treatment of close-form and open-form questions by large-language models and shows a need for a more robust evaluation of in-context learning on the variety of different types of questions. It also poses a new question of how to optimally select a context for large language models, especially in the context of Retrieval Augmented Generation (RAG) systems. Our results suggest that the answer to this question can be highly application-dependent and might be contingent on factors including the format of the question, the perceived difficulty level of the questions, and the novelty or popularity of the information we seek.

[Arxiv](https://arxiv.org/abs/2407.02028)