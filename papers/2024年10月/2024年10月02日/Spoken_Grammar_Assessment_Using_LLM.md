# 利用 LLM 进行口语语法测评

发布时间：2024年10月02日

`LLM应用` `语音识别`

> Spoken Grammar Assessment Using LLM

# 摘要

> 口语评估系统（SLA）专注于通过分析朗读和即兴表达来评估发音和流利度，而语法和词汇的评估则依赖于书面评估系统（WLA）。WLA系统通常从有限的数据库中抽取句子，容易导致预测和训练。本文提出了一种端到端的SLA系统，直接从口语中评估语法，使WLA系统不再必要。通过引入大型语言模型（LLM），我们使评估变得难以预测和训练。此外，结合自定义语言模型的混合ASR在口语语法评估中超越了现有最先进的ASR技术。

> Spoken language assessment (SLA) systems restrict themselves to evaluating the pronunciation and oral fluency of a speaker by analysing the read and spontaneous spoken utterances respectively. The assessment of language grammar or vocabulary is relegated to written language assessment (WLA) systems. Most WLA systems present a set of sentences from a curated finite-size database of sentences thereby making it possible to anticipate the test questions and train oneself. In this paper, we propose a novel end-to-end SLA system to assess language grammar from spoken utterances thus making WLA systems redundant; additionally, we make the assessment largely unteachable by employing a large language model (LLM) to bring in variations in the test. We further demonstrate that a hybrid automatic speech recognition (ASR) with a custom-built language model outperforms the state-of-the-art ASR engine for spoken grammar assessment.

[Arxiv](https://arxiv.org/abs/2410.01579)