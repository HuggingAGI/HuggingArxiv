# MIRAGE-Bench：检索增强生成系统的自动多语言基准竞技场

发布时间：2024年10月17日

`RAG` `人工智能`

> MIRAGE-Bench: Automatic Multilingual Benchmark Arena for Retrieval-Augmented Generation Systems

# 摘要

> 传统的 RAG 基准测试依赖于启发式评估，但这些评估需要人类偏好作为参考。相比之下，竞技场基准测试需要昂贵的 LLM 作为裁判。我们提出了一种简单高效的方法，结合了两者的优点。我们训练了一个学习排序模型作为“代理”裁判，使用 RAG 启发式评估生成合成排行榜。基于此，我们开发了 MIRAGE-Bench，一个涵盖 18 种语言的多语言 RAG 基准测试。该基准测试结合了启发式特征和 LLM 评估。我们测试了 19 个多语言 LLM，并实现了高相关性（Kendall Tau ($τ$) = 0.909）。目前，专有和大型开源 LLM 在多语言 RAG 中占据主导地位。MIRAGE-Bench 可在 https://github.com/vectara/mirage-bench 获取。

> Traditional Retrieval-Augmented Generation (RAG) benchmarks rely on different heuristic-based metrics for evaluation, but these require human preferences as ground truth for reference. In contrast, arena-based benchmarks, where two models compete each other, require an expensive Large Language Model (LLM) as a judge for a reliable evaluation. We present an easy and efficient technique to get the best of both worlds. The idea is to train a learning to rank model as a "surrogate" judge using RAG-based evaluation heuristics as input, to produce a synthetic arena-based leaderboard. Using this idea, We develop MIRAGE-Bench, a standardized arena-based multilingual RAG benchmark for 18 diverse languages on Wikipedia. The benchmark is constructed using MIRACL, a retrieval dataset, and extended for multilingual generation evaluation. MIRAGE-Bench evaluates RAG extensively coupling both heuristic features and LLM as a judge evaluator. In our work, we benchmark 19 diverse multilingual-focused LLMs, and achieve a high correlation (Kendall Tau ($τ$) = 0.909) using our surrogate judge learned using heuristic features with pairwise evaluations and between GPT-4o as a teacher on the MIRAGE-Bench leaderboard using the Bradley-Terry framework. We observe proprietary and large open-source LLMs currently dominate in multilingual RAG. MIRAGE-Bench is available at: https://github.com/vectara/mirage-bench.

[Arxiv](https://arxiv.org/abs/2410.13716)