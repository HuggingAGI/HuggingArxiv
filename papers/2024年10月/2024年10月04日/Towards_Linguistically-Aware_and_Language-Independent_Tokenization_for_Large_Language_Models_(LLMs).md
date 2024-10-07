# 为大型语言模型（LLM）打造语言学感知且跨语言的 Tokenization 方案

发布时间：2024年10月04日

`LLM理论` `人工智能`

> Towards Linguistically-Aware and Language-Independent Tokenization for Large Language Models (LLMs)

# 摘要

> 本文深入探讨了最先进的大型语言模型（LLM）所采用的分词技术，及其对不同语言服务成本和可用性的影响，尤其是低资源语言。研究涵盖了GPT-4、GPT-3、DaVinci及BERT等多种模型，分析了它们在分词上的差异，并探讨了子词分词中的语言表示难题。研究强调，对于资源匮乏的语言，开发过程中应更加注重语言意识。此外，本文通过电子健康记录（EHR）系统的实际案例，展示了分词选择的重要性。本研究旨在推动AI服务开发中的国际化（I18N）实践，特别强调包容性，尤其是那些在AI领域中传统上被忽视的语言。

> This paper presents a comprehensive study on the tokenization techniques employed by state-of-the-art large language models (LLMs) and their implications on the cost and availability of services across different languages, especially low resource languages. The analysis considers multiple LLMs, including GPT-4 (using cl100k_base embeddings), GPT-3 (with p50k_base embeddings), and DaVinci (employing r50k_base embeddings), as well as the widely used BERT base tokenizer. The study evaluates the tokenization variability observed across these models and investigates the challenges of linguistic representation in subword tokenization. The research underscores the importance of fostering linguistically-aware development practices, especially for languages that are traditionally under-resourced. Moreover, this paper introduces case studies that highlight the real-world implications of tokenization choices, particularly in the context of electronic health record (EHR) systems. This research aims to promote generalizable Internationalization (I18N) practices in the development of AI services in this domain and beyond, with a strong emphasis on inclusivity, particularly for languages traditionally underrepresented in AI applications.

[Arxiv](https://arxiv.org/abs/2410.03568)