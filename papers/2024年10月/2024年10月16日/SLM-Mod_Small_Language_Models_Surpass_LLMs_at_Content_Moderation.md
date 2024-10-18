# SLM-Mod: 小语言模型在内容审核上胜过大语言模型

发布时间：2024年10月16日

`LLM应用` `社交媒体` `内容审核`

> SLM-Mod: Small Language Models Surpass LLMs at Content Moderation

# 摘要

> 大型语言模型（LLM）在内容审核等自然语言理解任务中表现出色，但实时查询成本高，且难以针对特定社区进行优化。为此，我们尝试使用开源的小型语言模型（SLM）进行社区专属内容审核。通过对比 SLM（参数少于 15B）与更大规模模型的性能，我们发现 SLM 在内容审核上表现更佳，平均准确率提升 11.5%，召回率提升 25.7%。此外，跨社区内容审核的潜力也得到了验证，这对新社区和跨平台审核技术的发展具有重要意义。未来，我们将继续探索基于语言模型的内容审核技术。相关代码和模型链接请访问：https://github.com/AGoyal0512/SLM-Mod。

> Large language models (LLMs) have shown promise in many natural language understanding tasks, including content moderation. However, these models can be expensive to query in real-time and do not allow for a community-specific approach to content moderation. To address these challenges, we explore the use of open-source small language models (SLMs) for community-specific content moderation tasks. We fine-tune and evaluate SLMs (less than 15B parameters) by comparing their performance against much larger open- and closed-sourced models. Using 150K comments from 15 popular Reddit communities, we find that SLMs outperform LLMs at content moderation -- 11.5% higher accuracy and 25.7% higher recall on average across all communities. We further show the promise of cross-community content moderation, which has implications for new communities and the development of cross-platform moderation techniques. Finally, we outline directions for future work on language model based content moderation. Code and links to HuggingFace models can be found at https://github.com/AGoyal0512/SLM-Mod.

[Arxiv](https://arxiv.org/abs/2410.13155)