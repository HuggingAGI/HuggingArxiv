# [标题：“RAGged Edges”揭示了检索增强型聊天机器人这一把双刃剑的复杂性。该研究探讨了在提升聊天机器人性能的同时，检索增强技术所带来的挑战与局限性。]

发布时间：2024年03月02日

`RAG`

> RAGged Edges: The Double-Edged Sword of Retrieval-Augmented Chatbots

> ChatGPT等大型语言模型展现了人工智能的巨大飞跃，然而它们易产生“幻觉”——生成看似真实却为虚构的信息，这一问题至关重要，特别是在最近的法庭案例中，ChatGPT的运用导致了对不存在法律判决的引用。本文研究如何借助检索增强生成（RAG）技术，通过融合外部知识与输入提示来有效抑制这种“幻觉”。我们在精心设计、旨在诱发“幻觉”的提示下，对比试验了RAG和标准LLM的效果。实验结果显示，尽管RAG在某些情境下能提升准确度，但在面对与模型预训练知识直接矛盾的提示时仍可能出现误判。这一发现揭示了“幻觉”问题的复杂本质，强调需要更为稳健的解决方案以确保LLM在现实应用中的可靠性。我们提供了一些关于RAG部署的实践建议，并就开发更值得信赖的LLM展开了深入探讨。

> Large language models (LLMs) like ChatGPT demonstrate the remarkable progress of artificial intelligence. However, their tendency to hallucinate -- generate plausible but false information -- poses a significant challenge. This issue is critical, as seen in recent court cases where ChatGPT's use led to citations of non-existent legal rulings. This paper explores how Retrieval-Augmented Generation (RAG) can counter hallucinations by integrating external knowledge with prompts. We empirically evaluate RAG against standard LLMs using prompts designed to induce hallucinations. Our results show that RAG increases accuracy in some cases, but can still be misled when prompts directly contradict the model's pre-trained understanding. These findings highlight the complex nature of hallucinations and the need for more robust solutions to ensure LLM reliability in real-world applications. We offer practical recommendations for RAG deployment and discuss implications for the development of more trustworthy LLMs.

[Arxiv](https://arxiv.org/abs/2403.01193)