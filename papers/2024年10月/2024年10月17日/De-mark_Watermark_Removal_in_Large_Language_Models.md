# De-mark：大型语言模型中的水印清除术

发布时间：2024年10月17日

`LLM应用` `网络安全` `人工智能`

> De-mark: Watermark Removal in Large Language Models

# 摘要

> 水印技术通过嵌入隐蔽信息，为识别机器生成内容提供了新途径。然而，水印的鲁棒性仍待深入研究。本文介绍的De-mark框架，专为有效去除基于n-gram的水印而设计，采用创新的随机选择探测策略，评估水印强度并识别红绿列表。实验表明，De-mark在去除和利用水印方面表现出色，适用于Llama3和ChatGPT等主流模型。

> Watermarking techniques offer a promising way to identify machine-generated content via embedding covert information into the contents generated from language models (LMs). However, the robustness of the watermarking schemes has not been well explored. In this paper, we present De-mark, an advanced framework designed to remove n-gram-based watermarks effectively. Our method utilizes a novel querying strategy, termed random selection probing, which aids in assessing the strength of the watermark and identifying the red-green list within the n-gram watermark. Experiments on popular LMs, such as Llama3 and ChatGPT, demonstrate the efficiency and effectiveness of De-mark in watermark removal and exploitation tasks.

[Arxiv](https://arxiv.org/abs/2410.13808)