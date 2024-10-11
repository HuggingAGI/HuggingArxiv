# TVBench：革新视频与语言的评估方式

发布时间：2024年10月10日

`LLM应用` `视频分析` `人工智能`

> TVBench: Redesigning Video-Language Evaluation

# 摘要

> 大型语言模型与视觉模型结合后，不仅表现出色，还能理解视频内容。然而，评估这些视频模型却面临独特挑战，已有多个基准被提出。本文揭示，当前最常用的视频-语言基准其实无需复杂的时间推理即可解决。我们发现现有数据集存在三大问题：单帧静态信息已足够完成任务；问题与答案文本过于详尽，模型无需视觉信息即可答对；许多问题仅凭常识即可解答，使得基准更像知识测试而非视觉推理。此外，开放式视频问答基准也存在类似问题，且LLM自动评估不可靠，无法作为替代。为此，我们推出TVBench，一个开源的视频多选问答基准，经广泛评估证实其需高水平时间理解。令人惊讶的是，多数最新顶尖视频-语言模型在TVBench上表现仅与随机相当，仅Gemini-Pro和Tarsier显著超越。

> Large language models have demonstrated impressive performance when integrated with vision models even enabling video understanding. However, evaluating these video models presents its own unique challenges, for which several benchmarks have been proposed. In this paper, we show that the currently most used video-language benchmarks can be solved without requiring much temporal reasoning. We identified three main issues in existing datasets: (i) static information from single frames is often sufficient to solve the tasks (ii) the text of the questions and candidate answers is overly informative, allowing models to answer correctly without relying on any visual input (iii) world knowledge alone can answer many of the questions, making the benchmarks a test of knowledge replication rather than visual reasoning. In addition, we found that open-ended question-answering benchmarks for video understanding suffer from similar issues while the automatic evaluation process with LLMs is unreliable, making it an unsuitable alternative. As a solution, we propose TVBench, a novel open-source video multiple-choice question-answering benchmark, and demonstrate through extensive evaluations that it requires a high level of temporal understanding. Surprisingly, we find that most recent state-of-the-art video-language models perform similarly to random performance on TVBench, with only Gemini-Pro and Tarsier clearly surpassing this baseline.

[Arxiv](https://arxiv.org/abs/2410.07752)