# 本文旨在探讨并缓解大型语言模型中存在的语言学歧视问题。

发布时间：2024年04月29日

`LLM应用` `机器学习`

> Evaluating and Mitigating Linguistic Discrimination in Large Language Models

# 摘要

> 大型语言模型（LLMs）通过在多种语言的文本上进行训练，通常具备多语言能力，并在解决不同语言描述的任务上表现出色。但它们也可能因为训练数据在语言间的不平衡而产生语言偏见，难以对相同任务的不同语言描述保持一致的响应。在本研究中，我们从安全性和质量两个维度，首次深入探讨了 LLMs 对不同语言查询的输出一致性。通过分析两个数据集（AdvBench 和 NQ）以及四种主流 LLMs（Llama2-13b、Gemma-7b、GPT-3.5-turbo 和 Gemini-pro）的表现，我们发现在英语、法语、俄语和西班牙语的查询中，LLMs 的人类对齐能力更强，有害查询的成功越狱率平均仅为 1.04%，而在孟加拉语、格鲁吉亚语、尼泊尔语和迈蒂利语中，这一比率平均高达 27.7%。此外，对于英语、丹麦语、捷克语和斯洛文尼亚语的查询，LLMs 产出的响应质量也更高，平均 $F_1$ 分数达到 0.1494。基于这些发现，我们设计了 LDFighter，一种基于相似性投票的方法，以减少 LLMs 的语言歧视，确保为不同语言的用户提供一致的服务体验。通过在良性和有害查询上的测试，LDFighter 显著降低了越狱成功率，并提升了平均响应质量，证实了其有效性。

> By training on text in various languages, large language models (LLMs) typically possess multilingual support and demonstrate remarkable capabilities in solving tasks described in different languages. However, LLMs can exhibit linguistic discrimination due to the uneven distribution of training data across languages. That is, LLMs are hard to keep the consistency of responses when faced with the same task but depicted in different languages.
  In this study, we first explore the consistency in the LLMs' outputs responding to queries in various languages from two aspects: safety and quality. We conduct this analysis with two datasets (AdvBench and NQ) based on four LLMs (Llama2-13b, Gemma-7b, GPT-3.5-turbo and Gemini-pro). The results show that LLMs exhibit stronger human alignment capabilities with queries in English, French, Russian, and Spanish (only 1.04\% of harmful queries successfully jailbreak on average) compared to queries in Bengali, Georgian, Nepali and Maithili (27.7\% of harmful queries jailbreak successfully on average). Moreover, for queries in English, Danish, Czech and Slovenian, LLMs tend to produce responses with a higher quality (with 0.1494 $F_1$ score on average) compared to the other languages. Upon these findings, we propose LDFighter, a similarity-based voting, to mitigate the linguistic discrimination in LLMs. LDFighter ensures consistent service for different language speakers. We evaluate LDFighter with both benign queries and harmful queries. The results show that LDFighter not only significantly reduces the jailbreak success rate but also improve the response quality on average, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2404.18534)