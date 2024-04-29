# 在大型语言模型（LLM）支持的应用程序中，悄然兴起了一种难以为人所察觉的检索投毒攻击。

发布时间：2024年04月26日

`分类：LLM应用` `网络安全` `人工智能`

> Human-Imperceptible Retrieval Poisoning Attacks in LLM-Powered Applications

# 摘要

> 当前，借助尖端的大型语言模型（LLM）应用开发框架，越来越多的LLM应用能够通过检索增强生成（RAG）技术轻松扩充其知识库。但这些框架在设计上对外部内容风险的考虑不足，容易让攻击者有机可乘。本文揭露了LLM应用面临的一个新风险——检索投毒，攻击者借此可以操纵应用在RAG过程中生成恶意回应。攻击者通过分析LLM应用框架，精心制作出外观上与正常文档无异的文档，这些文档虽提供正确信息，但一旦作为RAG的参考，却能误导应用产生错误结果。我们的初步实验显示，攻击者能够以88.33%的高成功率误导LLM，且在现实世界应用中的成功率也高达66.67%，这充分说明了检索投毒的严重性及其潜在的广泛影响。

> Presently, with the assistance of advanced LLM application development frameworks, more and more LLM-powered applications can effortlessly augment the LLMs' knowledge with external content using the retrieval augmented generation (RAG) technique. However, these frameworks' designs do not have sufficient consideration of the risk of external content, thereby allowing attackers to undermine the applications developed with these frameworks. In this paper, we reveal a new threat to LLM-powered applications, termed retrieval poisoning, where attackers can guide the application to yield malicious responses during the RAG process. Specifically, through the analysis of LLM application frameworks, attackers can craft documents visually indistinguishable from benign ones. Despite the documents providing correct information, once they are used as reference sources for RAG, the application is misled into generating incorrect responses. Our preliminary experiments indicate that attackers can mislead LLMs with an 88.33\% success rate, and achieve a 66.67\% success rate in the real-world application, demonstrating the potential impact of retrieval poisoning.

[Arxiv](https://arxiv.org/abs/2404.17196)