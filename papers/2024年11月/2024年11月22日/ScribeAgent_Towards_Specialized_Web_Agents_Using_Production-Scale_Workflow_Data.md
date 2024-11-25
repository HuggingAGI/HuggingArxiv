# ScribeAgent：借助生产规模的工作流数据迈向专业化网络代理

发布时间：2024年11月22日

`Agent` `人工智能`

> ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data

# 摘要

> 大型语言模型（LLM）代理正在快速提升，以应对愈发复杂的网络任务。多数此类代理依靠像 GPT-4 这样的通用专有模型，着重设计更优的提示来增强规划能力。然而，通用 LLM 并非专门受训以理解诸如 HTML 等专业网络语境，它们在长期规划上常遇难题。我们探索了一种别样的途径，利用从超 250 个领域采集的、对应 60 亿标记的生产规模工作流数据对开源 LLM 进行微调。这一简单却有效的方法在现有基准上相较基于提示的代理优势显著——ScribeAgent 在 Mind2Web 上达成了最前沿的直接生成性能，在 WebArena 上比此前最佳的纯文本网络代理将任务成功率提升了 14.1%。我们进一步针对各类微调设计选择展开了详细的消融研究，并就 LLM 选择、训练方案、上下文窗口优化以及数据集大小的影响给出了见解。

> Large Language Model (LLM) agents are rapidly improving to handle increasingly complex web-based tasks. Most of these agents rely on general-purpose, proprietary models like GPT-4 and focus on designing better prompts to improve their planning abilities. However, general-purpose LLMs are not specifically trained to understand specialized web contexts such as HTML, and they often struggle with long-horizon planning. We explore an alternative approach that fine-tunes open-source LLMs using production-scale workflow data collected from over 250 domains corresponding to 6 billion tokens. This simple yet effective approach shows substantial gains over prompting-based agents on existing benchmarks -- ScribeAgent achieves state-of-the-art direct generation performance on Mind2Web and improves the task success rate by 14.1% over the previous best text-only web agents on WebArena. We further perform detailed ablation studies on various fine-tuning design choices and provide insights into LLM selection, training recipes, context window optimization, and effect of dataset sizes.

[Arxiv](https://arxiv.org/abs/2411.15004)