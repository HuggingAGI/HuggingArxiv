# UniOQA：大型语言模型下的知识图谱问答统一框架

发布时间：2024年06月04日

`LLM应用

这篇论文摘要描述了一个名为UniOQA的框架，该框架利用大型语言模型（LLMs）来提高中文开放领域知识图谱上的问答准确性。它通过微调LLM来转换问题为Cypher语言，并引入了直接答案预测作为补充。此外，还采用了实体与关系替换算法和动态决策算法来优化答案准确性。这个框架特别强调了LLMs在问答系统中的应用，因此属于LLM应用分类。` `知识图谱` `问答系统`

> UniOQA: A Unified Framework for Knowledge Graph Question Answering with Large Language Models

# 摘要

> OwnThink 作为近期推出的最全面的中文开放领域知识图谱，尽管已有研究尝试在其上进行问答（OQA），但模型表示能力的局限性限制了问答准确性的进一步提升。本文提出的 UniOQA 框架，通过整合两个互补的并行流程，打破了传统方法的局限。UniOQA 利用 LLMs 进行精确问答，并引入直接答案预测作为经济高效的补充。首先，通过微调 LLM 将问题转换为 Cypher 语言，解决了语义理解和幻觉问题。接着，采用实体与关系替换算法确保 CQL 的可执行性。同时，将 RAG 过程适配至知识图谱，以提升问答准确性。最终，通过动态决策算法优化答案准确性。实验显示，UniOQA 将逻辑准确率提升至 21.2%，执行准确率至 54.9%，刷新了该领域的最佳记录。消融实验进一步验证了 UniOQA 的强大表示能力及其性能的显著提升。

> OwnThink stands as the most extensive Chinese open-domain knowledge graph introduced in recent times. Despite prior attempts in question answering over OwnThink (OQA), existing studies have faced limitations in model representation capabilities, posing challenges in further enhancing overall accuracy in question answering. In this paper, we introduce UniOQA, a unified framework that integrates two complementary parallel workflows. Unlike conventional approaches, UniOQA harnesses large language models (LLMs) for precise question answering and incorporates a direct-answer-prediction process as a cost-effective complement. Initially, to bolster representation capacity, we fine-tune an LLM to translate questions into the Cypher query language (CQL), tackling issues associated with restricted semantic understanding and hallucinations. Subsequently, we introduce the Entity and Relation Replacement algorithm to ensure the executability of the generated CQL. Concurrently, to augment overall accuracy in question answering, we further adapt the Retrieval-Augmented Generation (RAG) process to the knowledge graph. Ultimately, we optimize answer accuracy through a dynamic decision algorithm. Experimental findings illustrate that UniOQA notably advances SpCQL Logical Accuracy to 21.2% and Execution Accuracy to 54.9%, achieving the new state-of-the-art results on this benchmark. Through ablation experiments, we delve into the superior representation capacity of UniOQA and quantify its performance breakthrough.

![UniOQA：大型语言模型下的知识图谱问答统一框架](../../../paper_images/2406.02110/all.png)

![UniOQA：大型语言模型下的知识图谱问答统一框架](../../../paper_images/2406.02110/ir.png)

![UniOQA：大型语言模型下的知识图谱问答统一框架](../../../paper_images/2406.02110/case.png)

![UniOQA：大型语言模型下的知识图谱问答统一框架](../../../paper_images/2406.02110/pyraa.png)

![UniOQA：大型语言模型下的知识图谱问答统一框架](../../../paper_images/2406.02110/2.png)

[Arxiv](https://arxiv.org/abs/2406.02110)