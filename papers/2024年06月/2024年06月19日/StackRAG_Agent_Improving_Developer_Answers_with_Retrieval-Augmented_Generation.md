# StackRAG Agent：利用检索增强生成技术提升开发者答案质量

发布时间：2024年06月19日

`RAG

理由：这篇论文介绍了一种名为StackRAG的工具，它结合了Stack Overflow的知识和大型语言模型（LLMs）来提高答案的可靠性。这种方法属于检索增强生成（RAG）的范畴，因为它利用了外部知识源（Stack Overflow）来增强LLMs的生成能力。因此，这篇论文最适合归类到RAG。` `软件开发` `问答系统`

> StackRAG Agent: Improving Developer Answers with Retrieval-Augmented Generation

# 摘要

> 开发者常为寻找问题答案而耗时。Stack Overflow虽是首选，但大型语言模型（LLMs）如ChatGPT的兴起也提供了新途径。然而，单独使用这些方法各有短板：搜索答案费时费力，而LLMs可能给出不靠谱的答案。为此，我们开发了StackRAG，一种结合Stack Overflow知识与LLMs的检索增强生成工具，旨在提升答案的可靠性。初步测试表明，StackRAG生成的答案既准确又实用。

> Developers spend much time finding information that is relevant to their questions. Stack Overflow has been the leading resource, and with the advent of Large Language Models (LLMs), generative models such as ChatGPT are used frequently. However, there is a catch in using each one separately. Searching for answers is time-consuming and tedious, as shown by the many tools developed by researchers to address this issue. On the other, using LLMs is not reliable, as they might produce irrelevant or unreliable answers (i.e., hallucination). In this work, we present StackRAG, a retrieval-augmented Multiagent generation tool based on LLMs that combines the two worlds: aggregating the knowledge from SO to enhance the reliability of the generated answers. Initial evaluations show that the generated answers are correct, accurate, relevant, and useful.

![StackRAG Agent：利用检索增强生成技术提升开发者答案质量](../../../paper_images/2406.13840/Agent-Architecture.png)

[Arxiv](https://arxiv.org/abs/2406.13840)