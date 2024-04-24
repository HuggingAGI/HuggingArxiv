# FASTTRACK：一种为大型语言模型（LLMs）量身定制的高效精准事实追踪技术。

发布时间：2024年04月21日

`LLM应用` `信息检索`

> FASTTRACK: Fast and Accurate Fact Tracing for LLMs

# 摘要

> 事实追踪的目的是找出特定训练案例，这些案例是某个查询的知识来源。目前的方法通过比较训练样本与查询在词汇、梯度或嵌入空间等维度上的相似度来进行事实追踪。但这些方法往往难以区分仅仅是相关联的样本和真正能为查询所寻求信息提供有力证据的样本，这限制了它们的有效性。此外，这些方法需要对每个查询逐一比较训练样本的相似度，这不仅计算量大，也极大地限制了它们的实际应用前景。本文提出了FASTTRACK，这是一种创新的方法，它利用大型语言模型（LLMs）的能力来确认查询的支持性证据，并且通过减少训练数据库的规模来简化LLMs的事实追踪过程。实验结果表明，FASTTRACK在准确性和效率上都显著超越了现有技术，其F1得分比最先进的方法提升了一倍以上，同时运行速度是\texttt{TracIn}的33倍。

> Fact tracing seeks to identify specific training examples that serve as the knowledge source for a given query. Existing approaches to fact tracing rely on assessing the similarity between each training sample and the query along a certain dimension, such as lexical similarity, gradient, or embedding space. However, these methods fall short of effectively distinguishing between samples that are merely relevant and those that actually provide supportive evidence for the information sought by the query. This limitation often results in suboptimal effectiveness. Moreover, these approaches necessitate the examination of the similarity of individual training points for each query, imposing significant computational demands and creating a substantial barrier for practical applications. This paper introduces FASTTRACK, a novel approach that harnesses the capabilities of Large Language Models (LLMs) to validate supportive evidence for queries and at the same time clusters the training database towards a reduced extent for LLMs to trace facts. Our experiments show that FASTTRACK substantially outperforms existing methods in both accuracy and efficiency, achieving more than 100\% improvement in F1 score over the state-of-the-art methods while being X33 faster than \texttt{TracIn}.

[Arxiv](https://arxiv.org/abs/2404.15157)