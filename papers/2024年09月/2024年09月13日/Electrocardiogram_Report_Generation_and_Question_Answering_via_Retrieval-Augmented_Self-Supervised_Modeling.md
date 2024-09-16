# 基于检索增强的自监督模型，实现心电图报告的生成与问答

发布时间：2024年09月13日

`LLM应用` `心脏病学`

> Electrocardiogram Report Generation and Question Answering via Retrieval-Augmented Self-Supervised Modeling

# 摘要

> 解读心电图并生成详细报告在心脏病学中颇具挑战，常需专业知识和大量时间。为此，我们推出 ECG-ReGen，一种基于检索的 ECG 报告生成与问答方法。通过自监督学习优化 ECG 编码器，实现高效相似性搜索和报告检索。结合预训练、动态检索与大型语言模型（LLM）精炼，ECG-ReGen 精准分析 ECG 数据并解答相关问题，有望提升患者护理。实验显示，在 PTB-XL 和 MIMIC-IV-ECG 数据集上，ECG-ReGen 在报告生成方面表现卓越，跨领域亦然。此外，使用现成 LLM 进行零-shot 问答时，ECG-QA 数据集上性能与全监督方法相当。此方法融合自监督编码器与 LLM，为 ECG 精准解读提供高效可扩展方案，极大助力临床决策。

> Interpreting electrocardiograms (ECGs) and generating comprehensive reports remain challenging tasks in cardiology, often requiring specialized expertise and significant time investment. To address these critical issues, we propose ECG-ReGen, a retrieval-based approach for ECG-to-text report generation and question answering. Our method leverages a self-supervised learning for the ECG encoder, enabling efficient similarity searches and report retrieval. By combining pre-training with dynamic retrieval and Large Language Model (LLM)-based refinement, ECG-ReGen effectively analyzes ECG data and answers related queries, with the potential of improving patient care. Experiments conducted on the PTB-XL and MIMIC-IV-ECG datasets demonstrate superior performance in both in-domain and cross-domain scenarios for report generation. Furthermore, our approach exhibits competitive performance on ECG-QA dataset compared to fully supervised methods when utilizing off-the-shelf LLMs for zero-shot question answering. This approach, effectively combining self-supervised encoder and LLMs, offers a scalable and efficient solution for accurate ECG interpretation, holding significant potential to enhance clinical decision-making.

[Arxiv](https://arxiv.org/abs/2409.08788)