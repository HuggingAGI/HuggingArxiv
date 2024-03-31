# MFORT-QA：一种多步骤、小样本量的开放式复杂表格问题解答方法

发布时间：2024年03月27日

`LLM应用` `职场信息管理` `表格问答`

> MFORT-QA: Multi-hop Few-shot Open Rich Table Question Answering

# 摘要

> 在如今快速变化的职场中，专业人士每天都要从海量文件中提炼关键信息，而这些信息往往隐藏在表格或嵌套的超链接里。表格问答技术应运而生，旨在提取这些重要数据。但传统的表格问答训练，通过提供问题对应的金标准单元格坐标来给出答案，有时并不能确保答案的准确性。幸运的是，大型语言模型的最新进展为我们使用提示从表格中提取信息提供了新途径。本文提出了一种新颖的多跳少样本开放式丰富表格问答方法（MFORT-QA），它包含两个关键步骤。首先，通过少样本学习，根据问题检索相关表格和超链接上下文，用以构建少量样本提示，供LLM如ChatGPT使用。其次，为了应对复杂问题的解答，采用思维链提示法，将问题分解为一系列子问题和推理过程，以多跳方式进行。此外，检索增强生成技术通过获取与推理和问题相关的表格和超链接上下文，进一步提升了这一过程。这些新增上下文随后辅助第一步的提示，使得LLM能够给出更加精确的答案。OTT-QA的实验结果显示，我们的抽象问答方法能显著提高传统提取性表格问答的准确度。

> In today's fast-paced industry, professionals face the challenge of summarizing a large number of documents and extracting vital information from them on a daily basis. These metrics are frequently hidden away in tables and/or their nested hyperlinks. To address this challenge, the approach of Table Question Answering (QA) has been developed to extract the relevant information. However, traditional Table QA training tasks that provide a table and an answer(s) from a gold cell coordinate(s) for a question may not always ensure extracting the accurate answer(s). Recent advancements in Large Language Models (LLMs) have opened up new possibilities for extracting information from tabular data using prompts. In this paper, we introduce the Multi-hop Few-shot Open Rich Table QA (MFORT-QA) approach, which consists of two major steps. The first step involves Few-Shot Learning (FSL), where relevant tables and associated contexts of hyperlinks are retrieved based on a given question. The retrieved content is then used to construct few-shot prompts as inputs to an LLM, such as ChatGPT. To tackle the challenge of answering complex questions, the second step leverages Chain-of-thought (CoT) prompting to decompose the complex question into a sequential chain of questions and reasoning thoughts in a multi-hop manner. Retrieval-Augmented Generation (RAG) enhances this process by retrieving relevant tables and contexts of hyperlinks that are relevant to the resulting reasoning thoughts and questions. These additional contexts are then used to supplement the prompt used in the first step, resulting in more accurate answers from an LLM. Empirical results from OTT-QA demonstrate that our abstractive QA approach significantly improves the accuracy of extractive Table QA methods.

[Arxiv](https://arxiv.org/abs/2403.19116)