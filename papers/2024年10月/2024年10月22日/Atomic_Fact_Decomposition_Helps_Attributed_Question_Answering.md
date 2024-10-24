# 原子事实分解有助于属性问答

发布时间：2024年10月22日

`LLM应用` `问答系统` `知识图谱`

> Atomic Fact Decomposition Helps Attributed Question Answering

# 摘要

> 归因问答（AQA）旨在为给定的问题提供一个值得信赖的答案和可靠的归因报告。检索是一种被广泛采用的方法，包括两种一般范式：先检索后读取（RTR）和事后检索。最近，大型语言模型（LLM）已经显示出显著的熟练程度，促使研究人员对 AQA 的兴趣日益增长。然而，基于 RTR 的 AQA 经常受到不相关知识和快速变化的信息的影响，即使采用了 LLM，而基于事后检索的 AQA 则在理解具有复杂逻辑的长篇答案以及精确识别需要修改的内容和保留原始意图方面存在困难。为了解决这些问题，本文提出了一个基于原子事实分解的检索和编辑（ARE）框架，该框架通过指令调整的 LLM 将生成的长篇答案分解为分子子句和原子事实。值得注意的是，指令调整的 LLM 是使用从大规模知识图谱（KG）生成的精心构建的数据集进行微调的。这个过程涉及从给定的一组实体中提取一跳邻居，并将结果转换为连贯的长篇文本。随后，ARE 利用搜索引擎检索与原子事实相关的证据，将这些证据输入基于 LLM 的验证器，以确定事实是否需要扩展以进行重新检索或编辑。此外，编辑后的事实被回溯到原始答案中，并根据分子子句和原子事实之间的关系聚合证据。广泛的评估表明，我们提出的方法在几个数据集上的性能优于最先进的方法，另外还提出了一个新的指标 $Attr_{p}$ 用于评估证据归因的精度。

> Attributed Question Answering (AQA) aims to provide both a trustworthy answer and a reliable attribution report for a given question. Retrieval is a widely adopted approach, including two general paradigms: Retrieval-Then-Read (RTR) and post-hoc retrieval. Recently, Large Language Models (LLMs) have shown remarkable proficiency, prompting growing interest in AQA among researchers. However, RTR-based AQA often suffers from irrelevant knowledge and rapidly changing information, even when LLMs are adopted, while post-hoc retrieval-based AQA struggles with comprehending long-form answers with complex logic, and precisely identifying the content needing revision and preserving the original intent. To tackle these problems, this paper proposes an Atomic fact decomposition-based Retrieval and Editing (ARE) framework, which decomposes the generated long-form answers into molecular clauses and atomic facts by the instruction-tuned LLMs. Notably, the instruction-tuned LLMs are fine-tuned using a well-constructed dataset, generated from large scale Knowledge Graphs (KGs). This process involves extracting one-hop neighbors from a given set of entities and transforming the result into coherent long-form text. Subsequently, ARE leverages a search engine to retrieve evidences related to atomic facts, inputting these evidences into an LLM-based verifier to determine whether the facts require expansion for re-retrieval or editing. Furthermore, the edited facts are backtracked into the original answer, with evidence aggregated based on the relationship between molecular clauses and atomic facts. Extensive evaluations demonstrate the superior performance of our proposed method over the state-of-the-arts on several datasets, with an additionally proposed new metric $Attr_{p}$ for evaluating the precision of evidence attribution.

[Arxiv](https://arxiv.org/abs/2410.16708)