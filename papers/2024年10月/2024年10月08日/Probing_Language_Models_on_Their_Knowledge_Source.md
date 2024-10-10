# 探索语言模型如何运用其知识来源

发布时间：2024年10月08日

`LLM理论` `人工智能`

> Probing Language Models on Their Knowledge Source

# 摘要

> LLM 在处理内部学习知识（PK）和外部提供知识（CK）时，常常面临选择难题。本文提出了一种创新框架，旨在揭示 LLM 如何在 PK 和 CK 之间做出选择。通过设计与模型内部知识相悖的提示，我们发现特定激活模式能揭示知识来源。实验表明，中层激活，尤其是与输入关系相关的部分，对预测知识选择至关重要，为构建更可靠、能有效处理知识冲突的模型提供了新思路。

> Large Language Models (LLMs) often encounter conflicts between their learned, internal (parametric knowledge, PK) and external knowledge provided during inference (contextual knowledge, CK). Understanding how LLMs models prioritize one knowledge source over the other remains a challenge. In this paper, we propose a novel probing framework to explore the mechanisms governing the selection between PK and CK in LLMs. Using controlled prompts designed to contradict the model's PK, we demonstrate that specific model activations are indicative of the knowledge source employed. We evaluate this framework on various LLMs of different sizes and demonstrate that mid-layer activations, particularly those related to relations in the input, are crucial in predicting knowledge source selection, paving the way for more reliable models capable of handling knowledge conflicts effectively.

[Arxiv](https://arxiv.org/abs/2410.05817)