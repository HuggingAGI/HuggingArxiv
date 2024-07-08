# 半监督学习助力代码切换ASR，结合大型语言模型过滤器提升识别效果。

发布时间：2024年07月04日

`LLM应用` `语音识别` `机器学习`

> Semi-supervised Learning for Code-Switching ASR with Large Language Model Filter

# 摘要

> 代码切换现象，即不同语言的词汇在同一句话中交替出现，由于相关数据稀缺，构建高效的自动语音识别系统颇具挑战。本文提出，在半监督学习框架下，利用丰富的无监督单语语音数据来强化CS-ASR系统，尤其是在CS数据有限的情况下。我们构建了一个通用范式，将噪声学生训练应用于CS-ASR任务，并引入了LLM-Filter，通过设计精妙的提示模板，激活大型语言模型在单语数据筛选和伪标签优化中的校正功能。实验结果显示，我们的方法在CS任务上不仅大幅超越了传统监督与半监督学习方法，甚至在CS英语部分的表现也优于全监督的理想上限。此外，我们还探讨了口音对AESRC数据集的影响，发现当单语数据包含特定语言特征时，我们的方法能带来额外增益。

> Code-switching (CS) phenomenon occurs when words or phrases from different languages are alternated in a single sentence. Due to data scarcity, building an effective CS Automatic Speech Recognition (ASR) system remains challenging. In this paper, we propose to enhance CS-ASR systems by utilizing rich unsupervised monolingual speech data within a semi-supervised learning framework, particularly when access to CS data is limited. To achieve this, we establish a general paradigm for applying noisy student training (NST) to the CS-ASR task. Specifically, we introduce the LLM-Filter, which leverages well-designed prompt templates to activate the correction capability of large language models (LLMs) for monolingual data selection and pseudo-labels refinement during NST. Our experiments on the supervised ASRU-CS and unsupervised AISHELL-2 and LibriSpeech datasets show that our method not only achieves significant improvements over supervised and semi-supervised learning baselines for the CS task, but also attains better performance compared with the fully-supervised oracle upper-bound on the CS English part. Additionally, we further investigate the influence of accent on AESRC dataset and demonstrate that our method can get achieve additional benefits when the monolingual data contains relevant linguistic characteristic.

[Arxiv](https://arxiv.org/abs/2407.04219)