# 利用情感增强嵌入的LLM实现情感感知回复生成

发布时间：2024年10月02日

`LLM应用` `心理治疗` `人工智能`

> Emotion-Aware Response Generation Using Affect-Enriched Embeddings with LLMs

# 摘要

> 在自动化心理治疗中，聊天机器人需要提供富有同理心且连贯的回应。本研究针对这一挑战，提出了一种新方法，通过整合NRC情感词典、VADER、WordNet和SentiWordNet等多情感词典，以及LLAMA 2、Flan-T5、ChatGPT 3.0和ChatGPT 4.0等先进LLM，来增强模型的情感和上下文理解能力。我们分析了超过2,000个心理治疗会话记录，涵盖焦虑、抑郁、创伤和成瘾等主题，将记录分割并使用BERT、GPT-3和RoBERTa计算情感嵌入，存储于FAISS数据库中，以便快速检索相关片段。实验结果显示，这种方法显著提升了模型的同理心、连贯性、信息量和流畅性。研究强调了情感嵌入在心理治疗中提升LLM性能的关键作用。

> There is a need for empathetic and coherent responses in automated chatbot-facilitated psychotherapy sessions. This study addresses the challenge of enhancing the emotional and contextual understanding of large language models (LLMs) in psychiatric applications. We introduce a novel framework that integrates multiple emotion lexicons, including NRC Emotion Lexicon, VADER, WordNet, and SentiWordNet, with state-of-the-art LLMs such as LLAMA 2, Flan-T5, ChatGPT 3.0, and ChatGPT 4.0. The primary dataset comprises over 2,000 therapy session transcripts from the Counseling and Psychotherapy database, covering discussions on anxiety, depression, trauma, and addiction. We segment the transcripts into smaller chunks, enhancing them with lexical features and computing embeddings using BERT, GPT-3, and RoBERTa to capture semantic and emotional nuances. These embeddings are stored in a FAISS vector database, enabling efficient similarity search and clustering based on cosine similarity. Upon user query, the most relevant segments are retrieved and provided as context to the LLMs, significantly improving the models' ability to generate empathetic and contextually appropriate responses. Experimental evaluations demonstrate that in-corporating emotion lexicons enhances empathy, coherence, informativeness, and fluency scores. Our findings highlight the critical role of emotional embeddings in improving LLM performance for psychotherapy.

[Arxiv](https://arxiv.org/abs/2410.01306)