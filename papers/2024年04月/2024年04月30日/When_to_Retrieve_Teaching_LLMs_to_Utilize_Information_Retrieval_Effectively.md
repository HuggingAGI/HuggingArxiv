# 何时检索：引导大型语言模型高效运用信息检索技术。

发布时间：2024年04月30日

`LLM应用` `信息检索` `问答系统`

> When to Retrieve: Teaching LLMs to Utilize Information Retrieval Effectively

# 摘要

> 本文阐述了大型语言模型（LLMs）在特定情境下，如何高效地利用现成的信息检索（IR）系统来回答问题，尤其是当问题需要额外上下文时。研究发现，并非所有问答场景都需要外部信息检索，有时更需依赖LLM的内在参数记忆。在PopQA数据集上的研究显示，常见问题通过LLM的参数记忆即可得到解答，而不常见的问题则需借助IR系统。据此，我们提出了一种针对LLMs的训练策略，结合开放域问答数据集进行训练，使LLMs能够在不确定答案时生成特殊标记<RET>。在PopQA数据集上的测试表明，自适应检索LLM（Adapt-LLM）在三种不同配置下均优于传统LLM：全面检索、仅使用参数记忆，以及基于问题流行度决定是否使用检索器。分析结果揭示，Adapt-LLM能够在不知如何回答时生成<RET>标记，提示需要进行信息检索；而在依赖其参数记忆时，其准确度显著提升。

> In this paper, we demonstrate how Large Language Models (LLMs) can effectively learn to use an off-the-shelf information retrieval (IR) system specifically when additional context is required to answer a given question. Given the performance of IR systems, the optimal strategy for question answering does not always entail external information retrieval; rather, it often involves leveraging the parametric memory of the LLM itself. Prior research has identified this phenomenon in the PopQA dataset, wherein the most popular questions are effectively addressed using the LLM's parametric memory, while less popular ones require IR system usage. Following this, we propose a tailored training approach for LLMs, leveraging existing open-domain question answering datasets. Here, LLMs are trained to generate a special token, <RET>, when they do not know the answer to a question. Our evaluation of the Adaptive Retrieval LLM (Adapt-LLM) on the PopQA dataset showcases improvements over the same LLM under three configurations: (i) retrieving information for all the questions, (ii) using always the parametric memory of the LLM, and (iii) using a popularity threshold to decide when to use a retriever. Through our analysis, we demonstrate that Adapt-LLM is able to generate the <RET> token when it determines that it does not know how to answer a question, indicating the need for IR, while it achieves notably high accuracy levels when it chooses to rely only on its parametric memory.

[Arxiv](https://arxiv.org/abs/2404.19705)