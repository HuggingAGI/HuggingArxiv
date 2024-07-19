# 开源 LLM 能否媲美商业模型？本文探讨了当前 GPT 模型在生物医学任务中的少样本学习表现。

发布时间：2024年07月18日

`LLM应用`

> Can Open-Source LLMs Compete with Commercial Models? Exploring the Few-Shot Performance of Current GPT Models in Biomedical Tasks

# 摘要

> 商业LLM如GPT-4和Claude 3 Opus在NLP领域独占鳌头，而新兴的开源模型如Mixtral 8x7B和Llama 3正逐步缩小差距，提供更高效率且成本更低。这些开源LLM支持自我托管，特别适合处理敏感数据的企业和临床场景。我们在BioASQ挑战赛中测试了Claude 3 Opus、GPT-3.5-turbo和Mixtral 8x7b的性能，发现Mixtral在少-shot场景下表现出色，但在零-shot场景中表现不佳。QLoRa微调和维基百科知识的加入并未显著提升性能。实验表明，通过收集特定领域的少-shot示例，可以有效弥合商业与开源模型在零-shot场景下的性能差距。相关实验代码已公开在GitHub上。

> Commercial large language models (LLMs), like OpenAI's GPT-4 powering ChatGPT and Anthropic's Claude 3 Opus, have dominated natural language processing (NLP) benchmarks across different domains. New competing Open-Source alternatives like Mixtral 8x7B or Llama 3 have emerged and seem to be closing the gap while often offering higher throughput and being less costly to use. Open-Source LLMs can also be self-hosted, which makes them interesting for enterprise and clinical use cases where sensitive data should not be processed by third parties. We participated in the 12th BioASQ challenge, which is a retrieval augmented generation (RAG) setting, and explored the performance of current GPT models Claude 3 Opus, GPT-3.5-turbo and Mixtral 8x7b with in-context learning (zero-shot, few-shot) and QLoRa fine-tuning. We also explored how additional relevant knowledge from Wikipedia added to the context-window of the LLM might improve their performance. Mixtral 8x7b was competitive in the 10-shot setting, both with and without fine-tuning, but failed to produce usable results in the zero-shot setting. QLoRa fine-tuning and Wikipedia context did not lead to measurable performance gains. Our results indicate that the performance gap between commercial and open-source models in RAG setups exists mainly in the zero-shot setting and can be closed by simply collecting few-shot examples for domain-specific use cases. The code needed to rerun these experiments is available through GitHub.

[Arxiv](https://arxiv.org/abs/2407.13511)