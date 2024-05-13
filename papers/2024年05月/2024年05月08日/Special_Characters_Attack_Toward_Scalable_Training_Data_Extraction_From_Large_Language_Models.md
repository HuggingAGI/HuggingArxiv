# 特殊字符攻击：揭秘大型语言模型训练数据的提取之谜在这项研究中，我们探讨了一种新颖的攻击手段——特殊字符攻击，它旨在从大型语言模型中提取训练数据。通过精心设计的特殊字符组合，我们能够揭示模型背后的知识库，为数据隐私和安全带来新的挑战。

发布时间：2024年05月08日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在处理特殊字符时的记忆和信息泄露问题，并提出了一种特殊字符攻击（SCA）来测试和分析这一问题。研究内容涉及LLMs的理论层面，特别是模型对训练数据的记忆和敏感性，以及如何通过特殊字符触发信息泄露。因此，它更符合LLM理论这一分类，因为它关注的是模型内部的工作原理和潜在的安全漏洞，而不是直接的应用场景或代理（Agent）的行为。` `数据安全` `人工智能伦理`

> Special Characters Attack: Toward Scalable Training Data Extraction From Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多任务中表现卓越，但近期研究发现，这些模型可能会记忆训练数据，甚至被简单的重复标记诱导泄露信息。本文深入探讨，指出特定特殊字符及其与英文字母的组合能更强烈地触发记忆，导致数据泄露问题加剧。由于LLMs在包含大量特殊字符的数据上训练，模型可能记住了这些字符与文本内容的关联。基于此，我们提出了一种简单而高效的特殊字符攻击（SCA），用以诱导数据泄露。实验证明，SCA对顶级LLMs极为有效，能泄露包括代码库、网页和个人身份信息在内的多样化训练数据，有时还会产生连续不断的输出。此外，通过分析泄露数据，我们揭示了训练数据语料库的组成，这对于预训练高性能LLMs至关重要。我们的研究有助于理解LLMs对特殊字符的敏感性，并指出了改进的方向。

> Large language models (LLMs) have achieved remarkable performance on a wide range of tasks. However, recent studies have shown that LLMs can memorize training data and simple repeated tokens can trick the model to leak the data. In this paper, we take a step further and show that certain special characters or their combinations with English letters are stronger memory triggers, leading to more severe data leakage. The intuition is that, since LLMs are trained with massive data that contains a substantial amount of special characters (e.g. structural symbols {, } of JSON files, and @, # in emails and online posts), the model may memorize the co-occurrence between these special characters and the raw texts. This motivates us to propose a simple but effective Special Characters Attack (SCA) to induce training data leakage. Our experiments verify the high effectiveness of SCA against state-of-the-art LLMs: they can leak diverse training data, such as code corpus, web pages, and personally identifiable information, and sometimes generate non-stop outputs as a byproduct. We further show that the composition of the training data corpus can be revealed by inspecting the leaked data -- one crucial piece of information for pre-training high-performance LLMs. Our work can help understand the sensitivity of LLMs to special characters and identify potential areas for improvement.

[Arxiv](https://arxiv.org/abs/2405.05990)