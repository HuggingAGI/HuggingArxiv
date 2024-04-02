# 厌倦了不断安装插件吗？大型语言模型能够直接作为端到端的推荐系统。

发布时间：2024年03月31日

`LLM应用` `推荐系统` `用户行为分析`

> Tired of Plugins? Large Language Models Can Be End-To-End Recommenders

# 摘要

> 推荐系统致力于通过用户过往行为来预判其兴趣点。这类系统通常采用分步处理的流水线架构，需耗费大量数据对各环节进行训练，且难以适应新领域的挑战。近期，大型语言模型（LLMs）以其卓越的泛化能力，让单一模型能够应对不同场景下的多样推荐任务。然而，目前的基于LLM的推荐系统仅将LLM应用于推荐流程中的单一环节。此外，由于输入长度的限制，这些系统在将大量项目集以自然语言形式呈现给LLM时遭遇难题。为解决这些问题，我们提出了一个全新的基于LLM的一站式推荐框架——UniLLMRec。UniLLMRec通过推荐链路整合了召回、排序、重排序等多阶段任务。针对海量项目的处理，我们设计了一种创新策略，将所有项目构建成一个可动态更新和高效检索的项目树结构。UniLLMRec在零样本测试中与传统的监督模型相比展现出了巨大的潜力。同时，它还大幅提升了效率，相较于现有的基于LLM的模型，减少了86%的输入令牌需求。这样的高效率不仅加快了任务处理速度，还提高了资源的使用效率。为了便于模型理解和保证研究的可复制性，我们的代码已经开源。

> Recommender systems aim to predict user interest based on historical behavioral data. They are mainly designed in sequential pipelines, requiring lots of data to train different sub-systems, and are hard to scale to new domains. Recently, Large Language Models (LLMs) have demonstrated remarkable generalized capabilities, enabling a singular model to tackle diverse recommendation tasks across various scenarios. Nonetheless, existing LLM-based recommendation systems utilize LLM purely for a single task of the recommendation pipeline. Besides, these systems face challenges in presenting large-scale item sets to LLMs in natural language format, due to the constraint of input length. To address these challenges, we introduce an LLM-based end-to-end recommendation framework: UniLLMRec. Specifically, UniLLMRec integrates multi-stage tasks (e.g. recall, ranking, re-ranking) via chain-of-recommendations. To deal with large-scale items, we propose a novel strategy to structure all items into an item tree, which can be dynamically updated and effectively retrieved. UniLLMRec shows promising zero-shot results in comparison with conventional supervised models. Additionally, it boasts high efficiency, reducing the input token need by 86% compared to existing LLM-based models. Such efficiency not only accelerates task completion but also optimizes resource utilization. To facilitate model understanding and to ensure reproducibility, we have made our code publicly available.

[Arxiv](https://arxiv.org/abs/2404.00702)