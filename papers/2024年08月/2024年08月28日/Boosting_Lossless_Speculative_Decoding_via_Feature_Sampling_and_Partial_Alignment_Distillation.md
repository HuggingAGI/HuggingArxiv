# 利用特征采样与部分对齐蒸馏技术，提升无损推测解码的性能。

发布时间：2024年08月28日

`LLM理论` `人工智能` `软件开发`

> Boosting Lossless Speculative Decoding via Feature Sampling and Partial Alignment Distillation

# 摘要

> 无损推测解码技术通过轻量级草稿模型生成候选树结构，再由目标大型语言模型并行验证，从而加速LLM推理。本文重新审视现有方法，提出FSPAD，通过特征采样和部分对齐蒸馏两大创新，优化无损推测解码。实验涵盖多种模型和任务，FSPAD在各领域均表现卓越，超越现有技术。

> Lossless speculative decoding accelerates target large language model (LLM) inference by employing a lightweight draft model for generating tree-structured candidates, which are subsequently verified in parallel by the target LLM. Currently, effective approaches leverage feature-level rather than token-level autoregression within the draft model to facilitate more straightforward predictions and enhanced knowledge distillation. In this paper, we reassess these approaches and propose FSPAD (Feature Sampling and Partial Alignment Distillation for Lossless Speculative Decoding), which introduces two straightforward and effective components within the existing framework to boost lossless speculative decoding. Firstly, FSPAD utilizes token embeddings to sample features of the target LLM in high-dimensional space before feeding them into the draft model, due to the inherent uncertainty of the features preventing the draft model from obtaining the specific token output by the target LLM. Secondly, FSPAD introduces partial alignment distillation to weaken the draft model's connection between features and logits, aiming to reduce the conflict between feature alignment and logit confidence during training. Our experiments include both greedy and non-greedy decoding on the largest and smallest models from the Vicuna and LLaMA3-Instruct series, as well as tasks in multi-turn conversation, translation, summarization, question answering, mathematical reasoning, and retrieval-augmented generation. The results show that FSPAD outperforms the state-of-the-art method across all the aforementioned tasks and target LLMs.

[Arxiv](https://arxiv.org/abs/2408.15562)