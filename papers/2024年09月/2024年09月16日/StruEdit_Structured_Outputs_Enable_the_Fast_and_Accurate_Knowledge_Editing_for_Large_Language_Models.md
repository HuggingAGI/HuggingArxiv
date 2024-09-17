# StruEdit：通过结构化输出，实现大型语言模型的快速且精准知识编辑

发布时间：2024年09月16日

`LLM应用` `问答系统`

> StruEdit: Structured Outputs Enable the Fast and Accurate Knowledge Editing for Large Language Models

# 摘要

> 现代问答系统依赖于大型语言模型 (LLM) 提供最新答案。然而，更新自然语言输出中的知识极具挑战，因为既要识别需要修改的部分，又要确保修改后的内容连贯。这些难题源于自然语言的非结构化特性。为此，我们推出了 $\textbf{StruEdit}$，一种结构化编辑方法。首先，我们让 LLM 生成结构化的推理三元组，然后 StruEdit 迅速移除过时信息，并用最新数据一次性更新。实验表明，StruEdit 在准确性和速度上均优于其他方法。

> As the modern tool of choice for question answering, large language models (LLMs) are expected to deliver answers with up-to-date knowledge. To achieve such ideal question-answering systems, locating and then editing outdated knowledge in the natural language outputs is a general target of popular knowledge editing methods. However, this target is challenging, as both identifying which tokens to edit in the reasoning steps and ensuring the coherence of the revised reasoning chain are difficult tasks. We argue that these challenges stem from the unstructured nature of natural language outputs. To address the above challenges, we propose $\textbf{Stru}$ctural $\textbf{Edit}$ing ($\textbf{StruEdit}$), an improved baseline for knowledge editing. We first prompt LLMs to produce structured outputs consisting of reasoning triplets. Then, StruEdit removes any potentially outdated knowledge and efficiently refills the structured outputs with up-to-date information in a single step. Experimental results show that StruEdit consistently delivers the highest accuracy with lowest latency compared with other knowledge editing methods.

[Arxiv](https://arxiv.org/abs/2409.10132)