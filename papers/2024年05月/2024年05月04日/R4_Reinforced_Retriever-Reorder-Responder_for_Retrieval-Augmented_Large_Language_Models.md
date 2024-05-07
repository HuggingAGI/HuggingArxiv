# R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。

发布时间：2024年05月04日

`LLM应用` `信息检索`

> R4: Reinforced Retriever-Reorder-Responder for Retrieval-Augmented Large Language Models

# 摘要

> 检索增强的大型语言模型（LLMs）通过利用信息检索系统获取的相关内容来生成准确回应，以解决幻觉问题。但现有方法在执行文本生成任务时，往往简单地将相关文档附加到LLMs的提示中，忽略了检索文档与LLMs之间细微语义结构的相互作用。尤其是在处理附加了长篇文档的输入提示时，LLMs常常会在生成过程中“中断思路”。为了解决这一问题，本研究提出了一种新的工作流程——“加强检索器-重排序-响应器”（R^4），旨在为检索增强的LLMs学习文档排序，提升其生成能力而不改变其庞大参数集。该学习过程分为两个阶段：文档顺序调整和文档表示增强。文档顺序调整通过图注意力学习，根据响应质量的加强奖励，将检索文档排序优化为开始、中间和结束的不同位置。而文档表示增强则通过文档级梯度对抗学习，针对质量较差的响应进一步细化检索文档的表示。大量实验证明，我们的流程在知识密集型任务上的事实问题回答性能优于多个强基线。相关源代码和训练模型将在论文发表后公开。

> Retrieval-augmented large language models (LLMs) leverage relevant content retrieved by information retrieval systems to generate correct responses, aiming to alleviate the hallucination problem. However, existing retriever-responder methods typically append relevant documents to the prompt of LLMs to perform text generation tasks without considering the interaction of fine-grained structural semantics between the retrieved documents and the LLMs. This issue is particularly important for accurate response generation as LLMs tend to ``lose in the middle'' when dealing with input prompts augmented with lengthy documents. In this work, we propose a new pipeline named ``Reinforced Retriever-Reorder-Responder'' (R$^4$) to learn document orderings for retrieval-augmented LLMs, thereby further enhancing their generation abilities while the large numbers of parameters of LLMs remain frozen. The reordering learning process is divided into two steps according to the quality of the generated responses: document order adjustment and document representation enhancement. Specifically, document order adjustment aims to organize retrieved document orderings into beginning, middle, and end positions based on graph attention learning, which maximizes the reinforced reward of response quality. Document representation enhancement further refines the representations of retrieved documents for responses of poor quality via document-level gradient adversarial learning. Extensive experiments demonstrate that our proposed pipeline achieves better factual question-answering performance on knowledge-intensive tasks compared to strong baselines across various public datasets. The source codes and trained models will be released upon paper acceptance.

![R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。](../../../paper_images/2405.02659/x1.png)

![R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。](../../../paper_images/2405.02659/x2.png)

![R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。](../../../paper_images/2405.02659/x3.png)

![R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。](../../../paper_images/2405.02659/x4.png)

![R4：强化版检索-重排-响应机制，专为检索增强型大型语言模型设计。](../../../paper_images/2405.02659/x5.png)

[Arxiv](https://arxiv.org/abs/2405.02659)