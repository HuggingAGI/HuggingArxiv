# NACL 是一个适用于 LLM 推理阶段的通用且高效的 KV 缓存管理框架，能够有效处理缓存驱逐问题。

发布时间：2024年08月07日

`LLM应用` `人工智能` `软件开发`

> NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time

# 摘要

> 大型语言模型 (LLM) 开启了 AI 应用的新纪元，带来了扩展上下文窗口的无限可能。然而，由于长上下文建模所需的 KV 缓存占用大量内存，这些模型的托管成本极高。尽管已有研究尝试从 KV 缓存中移除不必要令牌，但大多依赖于累积注意力分数的局部统计，且评估指标如短文本的困惑度并不充分。本文提出的 NACL 框架，通过单次编码操作实现更优化的 KV 缓存驱逐，结合精确的注意力分数统计与随机驱逐策略，有效减少注意力偏差，增强长上下文建模的稳定性。实验显示，NACL 在短文本和长文本任务上分别提升性能达 80% 和 76%，同时减少 KV 缓存高达 50%，性能保持超 95%。相关代码已公开于 https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL。

> Large Language Models (LLMs) have ignited an innovative surge of AI applications, marking a new era of exciting possibilities equipped with extended context windows. However, hosting these models is cost-prohibitive mainly due to the extensive memory consumption of KV Cache involving long-context modeling. Despite several works proposing to evict unnecessary tokens from the KV Cache, most of them rely on the biased local statistics of accumulated attention scores and report performance using unconvincing metric like perplexity on inadequate short-text evaluation. In this paper, we propose NACL, a general framework for long-context KV cache eviction that achieves more optimal and efficient eviction in a single operation during the encoding phase. Due to NACL's efficiency, we combine more accurate attention score statistics in PROXY TOKENS EVICTION with the diversified random eviction strategy of RANDOM EVICTION, aiming to alleviate the issue of attention bias and enhance the robustness in maintaining pivotal tokens for long-context modeling tasks. Notably, our method significantly improves the performance on short- and long-text tasks by 80% and 76% respectively, reducing KV Cache by up to 50% with over 95% performance maintenance. The code is available at https: //github.com/PaddlePaddle/Research/ tree/master/NLP/ACL2024-NACL.

[Arxiv](https://arxiv.org/abs/2408.03675)