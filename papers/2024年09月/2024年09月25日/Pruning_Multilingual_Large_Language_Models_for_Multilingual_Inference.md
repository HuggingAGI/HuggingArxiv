# 精简多语言大型语言模型，提升多语言推理效率

发布时间：2024年09月25日

`LLM理论` `语言学` `机器翻译`

> Pruning Multilingual Large Language Models for Multilingual Inference

# 摘要

> 多语言大型语言模型 (MLLM) 在非英语语言中的零-shot 学习性能优于英语主导数据训练的模型。然而，英语与非英语语言间的性能差距仍待解决。MLLM 的高质量翻译能力表明其在语言对齐方面的熟练度。本研究探讨了如何利用这种对齐能力提升非英语语言的零-shot 性能。我们分析了 MLLM 的翻译行为，发现大量级特征在翻译中起关键作用。基于此，我们保留这些特征相关的权重，修剪其他权重，使 MLLM 在非翻译任务中也依赖这些特征。实验证明，这种策略有效提升了 MLLM 在非英语语言中的性能。

> Multilingual large language models (MLLMs), trained on multilingual balanced data, demonstrate better zero-shot learning performance in non-English languages compared to large language models trained on English-dominant data. However, the disparity in performance between English and non-English languages remains a challenge yet to be fully addressed. A distinctive characteristic of MLLMs is their high-quality translation capabilities, indicating an acquired proficiency in aligning between languages. This study explores how to enhance the zero-shot performance of MLLMs in non-English languages by leveraging their alignment capability between English and non-English languages. To achieve this, we first analyze the behavior of MLLMs when performing translation and reveal that there are large magnitude features that play a critical role in the translation process. Inspired by these findings, we retain the weights associated with operations involving the large magnitude features and prune other weights to force MLLMs to rely on these features for tasks beyond translation. We empirically demonstrate that this pruning strategy can enhance the MLLMs' performance in non-English language.

[Arxiv](https://arxiv.org/abs/2409.16911)