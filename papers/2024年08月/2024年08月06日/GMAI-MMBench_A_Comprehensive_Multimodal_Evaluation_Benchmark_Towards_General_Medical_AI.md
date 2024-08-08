# GMAI-MMBench：面向通用医学AI的全面多模态评估基准

发布时间：2024年08月06日

`LLM应用` `人工智能`

> GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI

# 摘要

> 大型视觉-语言模型 (LVLMs) 在处理图像、文本和生理信号等多种数据类型方面表现出色，广泛应用于多个领域。在医疗领域，LVLMs 的潜力巨大，能为诊断和治疗提供有力支持。然而，要充分发挥其潜力，建立评估其在医疗应用中效能的基准至关重要。现有基准多基于特定学术文献，聚焦单一领域，且感知粒度单一，存在临床相关性不足、评估不全面及对交互式 LVLMs 指导不足等问题。为此，我们推出了 GMAI-MMBench，这是目前最全面的通用医疗 AI 基准，数据结构分类明确，感知粒度多样。该基准涵盖 285 个数据集，涉及 39 种医学图像、18 个临床任务、18 个科室及 4 种感知粒度，采用视觉问答 (VQA) 形式。我们还引入了词汇树结构，便于用户根据需求定制评估任务，极大促进医疗 AI 的研究与应用。我们对 50 个 LVLMs 进行了评估，发现即便是先进的 GPT-4o 准确率也仅为 52%，显示了显著的提升空间。同时，我们指出了当前顶尖 LVLMs 存在的五个关键不足，这些问题的解决将推动更优医疗应用的发展。我们坚信，GMAI-MMBench 将引领社区开发新一代 LVLMs，迈向更先进的医疗 AI。

> Large Vision-Language Models (LVLMs) are capable of handling diverse data types such as imaging, text, and physiological signals, and can be applied in various fields. In the medical field, LVLMs have a high potential to offer substantial assistance for diagnosis and treatment. Before that, it is crucial to develop benchmarks to evaluate LVLMs' effectiveness in various medical applications. Current benchmarks are often built upon specific academic literature, mainly focusing on a single domain, and lacking varying perceptual granularities. Thus, they face specific challenges, including limited clinical relevance, incomplete evaluations, and insufficient guidance for interactive LVLMs. To address these limitations, we developed the GMAI-MMBench, the most comprehensive general medical AI benchmark with well-categorized data structure and multi-perceptual granularity to date. It is constructed from 285 datasets across 39 medical image modalities, 18 clinical-related tasks, 18 departments, and 4 perceptual granularities in a Visual Question Answering (VQA) format. Additionally, we implemented a lexical tree structure that allows users to customize evaluation tasks, accommodating various assessment needs and substantially supporting medical AI research and applications. We evaluated 50 LVLMs, and the results show that even the advanced GPT-4o only achieves an accuracy of 52\%, indicating significant room for improvement. Moreover, we identified five key insufficiencies in current cutting-edge LVLMs that need to be addressed to advance the development of better medical applications. We believe that GMAI-MMBench will stimulate the community to build the next generation of LVLMs toward GMAI.

[Arxiv](https://arxiv.org/abs/2408.03361)