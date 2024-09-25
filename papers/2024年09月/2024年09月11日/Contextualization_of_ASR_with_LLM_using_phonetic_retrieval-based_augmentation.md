# 利用语音检索增强技术，通过 LLM 为 ASR 注入上下文

发布时间：2024年09月11日

`LLM应用` `语音识别` `智能助手`

> Contextualization of ASR with LLM using phonetic retrieval-based augmentation

# 摘要

> 大型语言模型（LLM）在处理音频和文本等多模态信号方面表现出色，能够根据语音输入生成相应的口语或文本回复。然而，当输入为语音时，识别个人命名实体（如电话簿中的联系人）仍具挑战。为此，我们提出了一种基于检索的解决方案：首先，LLM 在无上下文情况下检测语音中的命名实体；接着，利用该实体从个人数据库中检索发音相似的实体并输入 LLM；最后，进行上下文感知的 LLM 解码。在语音助手任务中，我们的方法相较于无上下文的基线系统，词错误率降低了 30.2%，命名实体错误率降低了 73.6%。此外，我们的设计避免了使用完整的命名实体数据库，确保了高效性，并适用于大规模数据库。

> Large language models (LLMs) have shown superb capability of modeling multimodal signals including audio and text, allowing the model to generate spoken or textual response given a speech input. However, it remains a challenge for the model to recognize personal named entities, such as contacts in a phone book, when the input modality is speech. In this work, we start with a speech recognition task and propose a retrieval-based solution to contextualize the LLM: we first let the LLM detect named entities in speech without any context, then use this named entity as a query to retrieve phonetically similar named entities from a personal database and feed them to the LLM, and finally run context-aware LLM decoding. In a voice assistant task, our solution achieved up to 30.2% relative word error rate reduction and 73.6% relative named entity error rate reduction compared to a baseline system without contextualization. Notably, our solution by design avoids prompting the LLM with the full named entity database, making it highly efficient and applicable to large named entity databases.

[Arxiv](https://arxiv.org/abs/2409.15353)