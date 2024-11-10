# 通过对比学习区分大型语言模型生成的代码和人类编写的代码

发布时间：2024年11月07日

`LLM应用` `软件工程` `代码检测`

> Distinguishing LLM-generated from Human-written Code by Contrastive Learning

# 摘要

> 大型语言模型（LLM），如 OpenAI 发布的 ChatGPT，由于其在各种任务中生成高质量内容的能力而受到了工业界和学术界的极大关注。尽管 LLM 具有令人印象深刻的能力，但人们对其在新闻、教育和软件工程等各个领域的潜在风险越来越担忧。最近，已经提出了几个商业和开源的 LLM 生成内容检测器，然而，这些检测器主要是为检测自然语言内容而设计的，没有考虑程序代码的特定特征。本文旨在通过提出一种基于对比学习框架和使用 UniXcoder 构建的语义编码器的新型 ChatGPT 生成代码检测器 CodeGPTSensor 来填补这一空白。为了评估 CodeGPTSensor 在区分 ChatGPT 生成的代码和人工编写的代码方面的有效性，我们首先策划了一个大规模的人机比较语料库（HMCorp），其中包括 55 万对人工编写和 ChatGPT 生成的代码（即 28.8 万对 Python 代码对和 22.2 万对 Java 代码对）。基于 HMCorp 数据集，我们对 ChatGPT 生成代码的特征进行的定性和定量分析揭示了区分 ChatGPT 生成的代码和人工编写的代码及其代表性特征所面临的挑战和机遇。我们的实验结果表明，CodeGPTSensor 能够有效地识别 ChatGPT 生成的代码，优于所有选定的基线。

> Large language models (LLMs), such as ChatGPT released by OpenAI, have attracted significant attention from both industry and academia due to their demonstrated ability to generate high-quality content for various tasks. Despite the impressive capabilities of LLMs, there are growing concerns regarding their potential risks in various fields, such as news, education, and software engineering. Recently, several commercial and open-source LLM-generated content detectors have been proposed, which, however, are primarily designed for detecting natural language content without considering the specific characteristics of program code. This paper aims to fill this gap by proposing a novel ChatGPT-generated code detector, CodeGPTSensor, based on a contrastive learning framework and a semantic encoder built with UniXcoder. To assess the effectiveness of CodeGPTSensor on differentiating ChatGPT-generated code from human-written code, we first curate a large-scale Human and Machine comparison Corpus (HMCorp), which includes 550K pairs of human-written and ChatGPT-generated code (i.e., 288K Python code pairs and 222K Java code pairs). Based on the HMCorp dataset, our qualitative and quantitative analysis of the characteristics of ChatGPT-generated code reveals the challenge and opportunity of distinguishing ChatGPT-generated code from human-written code with their representative features. Our experimental results indicate that CodeGPTSensor can effectively identify ChatGPT-generated code, outperforming all selected baselines.

[Arxiv](https://arxiv.org/abs/2411.04704)