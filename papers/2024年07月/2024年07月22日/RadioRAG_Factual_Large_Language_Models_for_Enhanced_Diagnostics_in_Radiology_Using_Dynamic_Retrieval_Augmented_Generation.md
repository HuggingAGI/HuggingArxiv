# RadioRAG：通过动态检索增强生成技术，提升放射学诊断准确性的事实性大型语言模型。

发布时间：2024年07月22日

`RAG` `放射学`

> RadioRAG: Factual Large Language Models for Enhanced Diagnostics in Radiology Using Dynamic Retrieval Augmented Generation

# 摘要

> 大型语言模型（LLM）在医学AI领域取得了显著进展，但常因静态训练数据集而产生过时或不准确信息。检索增强生成（RAG）通过整合外部数据源缓解了这一问题。我们开发的放射学RAG（RadioRAG）是一个端到端框架，实时从权威放射学在线资源检索数据。通过专门的放射学问答数据集（RadioQA）评估，RadioRAG在回答放射学特定问题时，显著提升了LLM的诊断准确性，相对改进高达54%。特别是在乳腺成像和急诊放射学领域，RadioRAG的表现甚至超过了未使用RAG的模型。然而，不同LLM的改进程度不一，GPT-3.5-turbo和Mixtral-8x7B-instruct-v0.1显著提升，而Mistral-7B-instruct-v0.2则无改进。这表明，当LLM能够访问特定领域数据时，其性能将得到显著提升。对于放射学领域，RadioRAG提供了一个强大的框架，大幅提升了问答的诊断准确性和事实性。

> Large language models (LLMs) have advanced the field of artificial intelligence (AI) in medicine. However LLMs often generate outdated or inaccurate information based on static training datasets. Retrieval augmented generation (RAG) mitigates this by integrating outside data sources. While previous RAG systems used pre-assembled, fixed databases with limited flexibility, we have developed Radiology RAG (RadioRAG) as an end-to-end framework that retrieves data from authoritative radiologic online sources in real-time. RadioRAG is evaluated using a dedicated radiologic question-and-answer dataset (RadioQA). We evaluate the diagnostic accuracy of various LLMs when answering radiology-specific questions with and without access to additional online information via RAG. Using 80 questions from RSNA Case Collection across radiologic subspecialties and 24 additional expert-curated questions, for which the correct gold-standard answers were available, LLMs (GPT-3.5-turbo, GPT-4, Mistral-7B, Mixtral-8x7B, and Llama3 [8B and 70B]) were prompted with and without RadioRAG. RadioRAG retrieved context-specific information from www.radiopaedia.org in real-time and incorporated them into its reply. RadioRAG consistently improved diagnostic accuracy across all LLMs, with relative improvements ranging from 2% to 54%. It matched or exceeded question answering without RAG across radiologic subspecialties, particularly in breast imaging and emergency radiology. However, degree of improvement varied among models; GPT-3.5-turbo and Mixtral-8x7B-instruct-v0.1 saw notable gains, while Mistral-7B-instruct-v0.2 showed no improvement, highlighting variability in its effectiveness. LLMs benefit when provided access to domain-specific data beyond their training data. For radiology, RadioRAG establishes a robust framework that substantially improves diagnostic accuracy and factuality in radiological question answering.

[Arxiv](https://arxiv.org/abs/2407.15621)