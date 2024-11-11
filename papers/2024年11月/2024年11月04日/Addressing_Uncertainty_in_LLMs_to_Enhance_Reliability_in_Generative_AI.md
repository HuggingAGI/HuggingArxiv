# 解决大型语言模型中的不确定性以提高生成式人工智能的可靠性

发布时间：2024年11月04日

`LLM应用` `语言模型`

> Addressing Uncertainty in LLMs to Enhance Reliability in Generative AI

# 摘要

> 在本文中，我们提出了一种受中国餐馆过程启发的动态语义聚类方法，旨在解决大型语言模型（LLM）推理中的不确定性。我们通过计算生成的语义簇的熵来量化 LLM 对给定查询的不确定性。此外，我们提议在共形预测框架内利用这些簇的（负）可能性作为（非）一致性得分，允许模型预测一组响应而不是单个输出，从而考虑其预测中的不确定性。我们在两个著名的问答基准 COQA 和 TriviaQA 上利用两个 LLM（Llama2 和 Mistral）展示了我们的不确定性量化（UQ）技术的有效性。我们的方法在 UQ 中取得了 SOTA 性能，通过诸如 AUROC、AUARC 和 AURAC 等指标进行评估。与现有的 SOTA 共形预测基线相比，所提出的共形预测器也被证明在保持包含正确响应的相同概率保证的同时产生更小的预测集。

> In this paper, we present a dynamic semantic clustering approach inspired by the Chinese Restaurant Process, aimed at addressing uncertainty in the inference of Large Language Models (LLMs). We quantify uncertainty of an LLM on a given query by calculating entropy of the generated semantic clusters. Further, we propose leveraging the (negative) likelihood of these clusters as the (non)conformity score within Conformal Prediction framework, allowing the model to predict a set of responses instead of a single output, thereby accounting for uncertainty in its predictions. We demonstrate the effectiveness of our uncertainty quantification (UQ) technique on two well known question answering benchmarks, COQA and TriviaQA, utilizing two LLMs, Llama2 and Mistral. Our approach achieves SOTA performance in UQ, as assessed by metrics such as AUROC, AUARC, and AURAC. The proposed conformal predictor is also shown to produce smaller prediction sets while maintaining the same probabilistic guarantee of including the correct response, in comparison to existing SOTA conformal prediction baseline.

[Arxiv](https://arxiv.org/abs/2411.02381)