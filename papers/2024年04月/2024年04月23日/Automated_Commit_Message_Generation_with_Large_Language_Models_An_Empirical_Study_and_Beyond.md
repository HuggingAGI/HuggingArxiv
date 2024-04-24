# 大型语言模型在自动生成提交信息方面的应用：一项实证研究及其更深远的探讨

发布时间：2024年04月23日

`LLM应用` `软件开发`

> Automated Commit Message Generation with Large Language Models: An Empirical Study and Beyond

# 摘要

> 提交信息生成（CMG）技术致力于自动生成基于代码变更的提交信息，这对于促进开发者协作和开源软件（OSS）的发展至关重要。近期，大型语言模型（LLMs）在多样的代码相关任务中展现了其广泛的应用潜力。然而，关于系统性地探究LLMs在这一领域的有效性的研究却寥寥无几。本文开展了首次全面实验，旨在探究我们利用LLMs生成高质量提交信息的进展。在一项初步分析的启发下，我们首先根据行业标准清洗了最流行的CMG数据集。随后，我们重新评估了多种尖端的CMG方法，并与LLMs进行了比较，结果表明LLMs在性能上超越了现有的尖端CMG技术。进一步地，我们根据OSS的实践，提出了包括准确性、完整性、适用性和可读性在内的四个手动评估指标，并对不同的LLMs进行了评估。研究发现，GPT-3.5在整体表现上最为出色，但不同的LLMs各有千秋。为了进一步提升LLMs在CMG任务中的表现，我们设计了一个高效的基于检索的上下文学习（ICL）框架——ERICommiter，它通过两步过滤过程提高检索效率，并采用语义/词汇为基础的检索算法来构建ICL示例。广泛的实验证明，ERICommiter在多种编程语言的代码差异上显著提高了LLMs的CMG性能，并且在保持几乎相同性能的同时显著减少了检索时间。本研究不仅增进了我们对LLMs在CMG领域潜力的理解，也为那些希望在日常工作中利用这些工具的实践者提供了宝贵的洞见。

> Commit Message Generation (CMG) approaches aim to automatically generate commit messages based on given code diffs, which facilitate collaboration among developers and play a critical role in Open-Source Software (OSS). Very recently, Large Language Models (LLMs) have demonstrated extensive applicability in diverse code-related task. But few studies systematically explored their effectiveness using LLMs. This paper conducts the first comprehensive experiment to investigate how far we have been in applying LLM to generate high-quality commit messages. Motivated by a pilot analysis, we first clean the most widely-used CMG dataset following practitioners' criteria. Afterward, we re-evaluate diverse state-of-the-art CMG approaches and make comparisons with LLMs, demonstrating the superior performance of LLMs against state-of-the-art CMG approaches. Then, we further propose four manual metrics following the practice of OSS, including Accuracy, Integrity, Applicability, and Readability, and assess various LLMs accordingly. Results reveal that GPT-3.5 performs best overall, but different LLMs carry different advantages. To further boost LLMs' performance in the CMG task, we propose an Efficient Retrieval-based In-Context Learning (ICL) framework, namely ERICommiter, which leverages a two-step filtering to accelerate the retrieval efficiency and introduces semantic/lexical-based retrieval algorithm to construct the ICL examples. Extensive experiments demonstrate the substantial performance improvement of ERICommiter on various LLMs for code diffs of different programming languages. Meanwhile, ERICommiter also significantly reduces the retrieval time while keeping almost the same performance. Our research contributes to the understanding of LLMs' capabilities in the CMG field and provides valuable insights for practitioners seeking to leverage these tools in their workflows.

[Arxiv](https://arxiv.org/abs/2404.14824)