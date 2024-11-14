# 关于大型语言模型在语义相关任务中离散语音令牌的比较研究

发布时间：2024年11月13日

`LLM应用` `大型语言模型`

> A Comparative Study of Discrete Speech Tokens for Semantic-Related Tasks with Large Language Models

# 摘要

> 随着语音大型语言模型（Speech LLMs）的兴起，离散语音令牌因其能够与基于文本的令牌无缝集成的能力而引起了越来越多的兴趣。与大多数关注连续语音特征的研究相比，尽管基于离散令牌的 LLMs 在某些任务上显示出了有希望的结果，但这两种范式之间的性能差距很少被探讨。在本文中，我们使用轻量级 LLM（Qwen1.5-0.5B）在各种语义相关任务中对离散和连续特征进行了公平和全面的比较。我们的发现表明，连续特征通常优于离散令牌，特别是在需要细粒度语义理解的任务中。此外，本研究不仅仅是表面层次的比较，还通过确定离散令牌表现不佳背后的关键因素，如有限的令牌粒度和低效的信息保留。为了提高离散令牌的性能，我们根据分析探索了潜在的方面。我们希望我们的结果能够为推进 Speech LLMs 中的离散语音令牌提供新的见解。

> With the rise of Speech Large Language Models (Speech LLMs), there has been growing interest in discrete speech tokens for their ability to integrate with text-based tokens seamlessly. Compared to most studies that focus on continuous speech features, although discrete-token based LLMs have shown promising results on certain tasks, the performance gap between these two paradigms is rarely explored. In this paper, we present a fair and thorough comparison between discrete and continuous features across a variety of semantic-related tasks using a light-weight LLM (Qwen1.5-0.5B). Our findings reveal that continuous features generally outperform discrete tokens, particularly in tasks requiring fine-grained semantic understanding. Moreover, this study goes beyond surface-level comparison by identifying key factors behind the under-performance of discrete tokens, such as limited token granularity and inefficient information retention. To enhance the performance of discrete tokens, we explore potential aspects based on our analysis. We hope our results can offer new insights into the opportunities for advancing discrete speech tokens in Speech LLMs.

[Arxiv](https://arxiv.org/abs/2411.08742)