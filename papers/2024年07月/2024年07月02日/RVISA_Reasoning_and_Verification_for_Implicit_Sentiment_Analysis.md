# RVISA：隐式情感分析中的推理与验证

发布时间：2024年07月02日

`LLM应用` `情感分析` `人工智能`

> RVISA: Reasoning and Verification for Implicit Sentiment Analysis

# 摘要

> 随着细粒度情感分析需求的增加，隐式情感分析在没有明显线索词的表达中面临挑战。本研究提出RVISA框架，结合DO LLM的生成能力和ED LLM的推理能力，通过三跳推理提示法明确提供情感元素，微调ED LLM成为熟练推理器，并设计简单有效的验证机制确保推理可靠性。在两个基准数据集上，我们的方法在ISA性能上达到了最先进水平。

> With an increasing social demand for fine-grained sentiment analysis (SA), implicit sentiment analysis (ISA) poses a significant challenge with the absence of salient cue words in expressions. It necessitates reliable reasoning to understand how the sentiment is aroused and thus determine implicit sentiments. In the era of Large Language Models (LLMs), Encoder-Decoder (ED) LLMs have gained popularity to serve as backbone models for SA applications, considering impressive text comprehension and reasoning ability among diverse tasks. On the other hand, Decoder-only (DO) LLMs exhibit superior natural language generation and in-context learning capabilities. However, their responses may contain misleading or inaccurate information. To identify implicit sentiment with reliable reasoning, this study proposes RVISA, a two-stage reasoning framework that harnesses the generation ability of DO LLMs and the reasoning ability of ED LLMs to train an enhanced reasoner. Specifically, we adopt three-hop reasoning prompting to explicitly furnish sentiment elements as cues. The generated rationales are utilized to fine-tune an ED LLM into a skilled reasoner. Additionally, we develop a straightforward yet effective verification mechanism to ensure the reliability of the reasoning learning. We evaluated the proposed method on two benchmark datasets and achieved state-of-the-art results in ISA performance.

[Arxiv](https://arxiv.org/abs/2407.02340)