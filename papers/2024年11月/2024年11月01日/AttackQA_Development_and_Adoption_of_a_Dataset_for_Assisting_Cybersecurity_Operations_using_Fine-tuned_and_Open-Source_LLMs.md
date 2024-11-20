# AttackQA：开发并采用一个数据集，以借助微调的和开源的大型语言模型来协助网络安全操作

发布时间：2024年11月01日

`RAG` `网络安全` `问答系统`

> AttackQA: Development and Adoption of a Dataset for Assisting Cybersecurity Operations using Fine-tuned and Open-Source LLMs

# 摘要

> 在专业领域数据集上的检索增强生成（RAG）表明，当对大型语言模型（LLMs）进行微调以生成用户查询的响应时，性能会得到提升。在本研究中，我们开发了一个名为 AttackQA 的网络安全问答（Q&A）数据集，并借此构建了一个基于 RAG 的面向安全运营中心分析师的问答系统。该数据集包含 25335 个问答对，还附有相关理由，便于进行微调与评估。其中 80%的数据集是在轻量级开源 LLM（LLama 3 8B）的协助下生成的，它在 SambaNova System 的 SN40L 专用硬件上以全 16 位精度每秒能生成超过 1100 个令牌。为保证数据集质量，我们对 LLama 3 70B 进行了微调，以检测并剔除低质量的问答对。将该数据集用于 RAG 时，我们证实与 OpenAI 最先进的专有嵌入和 LLM（GPT-4o）相比，微调开源嵌入和 LLMs 能够实现更优的准确性。此外，我们以 Llama 3.1 405B 作为评判标准来评估答案的正确性，进而创建了一个完全开源、高速的 RAG 及评估管道，并为模型准确性设立了基准。

> Retrieval-augmented generation (RAG) on specialized domain datasets has shown improved performance when large language models (LLMs) are fine-tuned for generating responses to user queries. In this study, we develop a cybersecurity question-answering (Q\&A) dataset, called AttackQA, and employ it to build a RAG-based Q\&A system designed for analysts in security operations centers. The dataset comprises 25,335 Q\&A pairs, accompanied by rationales to facilitate fine-tuning and evaluation. 80\% of the dataset was generated with help of a lightweight open-source LLM (LLama 3 8B), which produced over 1100 tokens per second with full 16-bit precision on SambaNova System's SN40L specialized hardware. To ensure dataset quality, we fine-tuned LLama 3 70B to detect and reject low-quality Q\&A pairs. In using the dataset for RAG, we demonstrate that fine-tuning open-source embeddings and LLMs can yield superior accuracy compared to OpenAI's state-of-the-art proprietary embedding and LLM (GPT-4o). Furthermore, we use Llama 3.1 405B as a judge to evaluate answer correctness, enabling the creation of a fully open-source, high-speed RAG and evaluation pipeline with a benchmark for model accuracy.

[Arxiv](https://arxiv.org/abs/2411.01073)