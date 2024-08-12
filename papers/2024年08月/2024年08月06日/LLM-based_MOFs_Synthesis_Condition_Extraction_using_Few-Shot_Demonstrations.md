# 利用少量示例演示提取基于 LLM 的 MOFs 合成条件

发布时间：2024年08月06日

`LLM应用` `材料科学` `人工智能`

> LLM-based MOFs Synthesis Condition Extraction using Few-Shot Demonstrations

# 摘要

> 提取金属有机框架（MOFs）的合成条件，一直是科研难题，对设计新型MOFs至关重要。大型语言模型（LLMs）的兴起，为这一难题带来了革命性解决方案，最新研究显示，从MOFs文献中提取条件的准确率超过90%。然而，我们发现，多数现有方法仍依赖于基础的零-shot学习，缺乏专业知识可能导致性能下降。为此，我们创新性地引入了少-shot情境学习范式，优化了LLM在材料合成条件提取中的应用。首先，我们设计了人机协同的数据筛选流程，确保少-shot学习的高质量示例。接着，我们采用基于RAG技术的BM25算法，智能挑选适用于每个MOF提取的少-shot示例。实验结果显示，在随机抽取的84,898个MOFs数据集中，我们的少-shot方法在自动评估下，相比原生零-shot LLM，平均F1性能提升了14.8%，且评估更为客观。此外，实际材料实验验证，我们的方法在MOFs结构推断性能上，较基准零-shot LLM平均提升了29.4%。

> The extraction of Metal-Organic Frameworks (MOFs) synthesis conditions from literature text has been challenging but crucial for the logical design of new MOFs with desirable functionality. The recent advent of large language models (LLMs) provides disruptively new solution to this long-standing problem and latest researches have reported over 90% F1 in extracting correct conditions from MOFs literature. We argue in this paper that most existing synthesis extraction practices with LLMs stay with the primitive zero-shot learning, which could lead to downgraded extraction and application performance due to the lack of specialized knowledge. This work pioneers and optimizes the few-shot in-context learning paradigm for LLM extraction of material synthesis conditions. First, we propose a human-AI joint data curation process to secure high-quality ground-truth demonstrations for few-shot learning. Second, we apply a BM25 algorithm based on the retrieval-augmented generation (RAG) technique to adaptively select few-shot demonstrations for each MOF's extraction. Over a dataset randomly sampled from 84,898 well-defined MOFs, the proposed few-shot method achieves much higher average F1 performance (0.93 vs. 0.81, +14.8%) than the native zero-shot LLM using the same GPT-4 model, under fully automatic evaluation that are more objective than the previous human evaluation. The proposed method is further validated through real-world material experiments: compared with the baseline zero-shot LLM, the proposed few-shot approach increases the MOFs structural inference performance (R^2) by 29.4% in average.

[Arxiv](https://arxiv.org/abs/2408.04665)