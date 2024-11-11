# HtmlRAG：在 RAG 系统中，对于建模检索到的知识，HTML 比纯文本更好。

发布时间：2024年11月05日

`RAG` `问答系统` `检索系统`

> HtmlRAG: HTML is Better Than Plain Text for Modeling Retrieved Knowledge in RAG Systems

# 摘要

> 检索增强生成（RAG）已被证明能够提高知识能力并缓解大型语言模型（LLM）的幻觉问题。网络是 RAG 系统中使用的外部知识的主要来源，许多商业系统如 ChatGPT 和 Perplexity 都将网络搜索引擎作为其主要检索系统。通常，此类 RAG 系统检索搜索结果，下载结果的 HTML 源，然后从 HTML 源中提取纯文本。纯文本文档或块被输入到 LLM 中以增强生成。然而，在这个基于纯文本的 RAG 过程中，HTML 中固有的许多结构和语义信息，如标题和表格结构，都丢失了。为了缓解这个问题，我们提出了 HtmlRAG，它在 RAG 中使用 HTML 而不是纯文本作为检索知识的格式。我们认为 HTML 在对外部文档中的知识进行建模方面优于纯文本，并且大多数 LLM 具有强大的理解 HTML 的能力。然而，利用 HTML 带来了新的挑战。HTML 包含诸如标签、JavaScript 和 CSS 规范等附加内容，这给 RAG 系统带来了额外的输入标记和噪声。为了解决这个问题，我们提出了 HTML 清理、压缩和修剪策略，以在缩短 HTML 的同时最大限度地减少信息丢失。具体而言，我们设计了一种基于两步块树的修剪方法，修剪无用的 HTML 块并仅保留 HTML 的相关部分。在六个问答数据集上的实验证实了在 RAG 系统中使用 HTML 的优越性。

> Retrieval-Augmented Generation (RAG) has been shown to improve knowledge capabilities and alleviate the hallucination problem of LLMs. The Web is a major source of external knowledge used in RAG systems, and many commercial systems such as ChatGPT and Perplexity have used Web search engines as their major retrieval systems. Typically, such RAG systems retrieve search results, download HTML sources of the results, and then extract plain texts from the HTML sources. Plain text documents or chunks are fed into the LLMs to augment the generation. However, much of the structural and semantic information inherent in HTML, such as headings and table structures, is lost during this plain-text-based RAG process. To alleviate this problem, we propose HtmlRAG, which uses HTML instead of plain text as the format of retrieved knowledge in RAG. We believe HTML is better than plain text in modeling knowledge in external documents, and most LLMs possess robust capacities to understand HTML. However, utilizing HTML presents new challenges. HTML contains additional content such as tags, JavaScript, and CSS specifications, which bring extra input tokens and noise to the RAG system. To address this issue, we propose HTML cleaning, compression, and pruning strategies, to shorten the HTML while minimizing the loss of information. Specifically, we design a two-step block-tree-based pruning method that prunes useless HTML blocks and keeps only the relevant part of the HTML. Experiments on six QA datasets confirm the superiority of using HTML in RAG systems.

[Arxiv](https://arxiv.org/abs/2411.02959)