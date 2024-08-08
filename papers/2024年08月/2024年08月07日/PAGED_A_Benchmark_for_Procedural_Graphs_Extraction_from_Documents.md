# PAGED：文档程序图提取的基准

发布时间：2024年08月07日

`LLM应用` `软件工程` `人工智能`

> PAGED: A Benchmark for Procedural Graphs Extraction from Documents

# 摘要

> 自动提取文档中的程序图表，让用户通过视觉图表轻松掌握复杂流程，成本低廉。尽管研究有所进展，但两大问题仍待解答：现有研究是否已完美解决此任务（Q1），以及大型语言模型（LLMs）能否为此带来新契机（Q2）。为此，我们推出了新基准PAGED，配备庞大高质量数据集与标准评估体系。通过分析五大前沿基线，我们发现它们因过度依赖手写规则与数据限制，未能完美提取程序图表。我们进一步引入三款先进LLMs，并采用创新自精炼策略进行强化。实验显示，LLMs在文本元素识别上表现优异，但在逻辑结构构建上尚有不足。我们期待PAGED成为自动程序图表提取领域的里程碑，并为非序列元素间的逻辑推理研究提供新视角。

> Automatic extraction of procedural graphs from documents creates a low-cost way for users to easily understand a complex procedure by skimming visual graphs. Despite the progress in recent studies, it remains unanswered: whether the existing studies have well solved this task (Q1) and whether the emerging large language models (LLMs) can bring new opportunities to this task (Q2). To this end, we propose a new benchmark PAGED, equipped with a large high-quality dataset and standard evaluations. It investigates five state-of-the-art baselines, revealing that they fail to extract optimal procedural graphs well because of their heavy reliance on hand-written rules and limited available data. We further involve three advanced LLMs in PAGED and enhance them with a novel self-refine strategy. The results point out the advantages of LLMs in identifying textual elements and their gaps in building logical structures. We hope PAGED can serve as a major landmark for automatic procedural graph extraction and the investigations in PAGED can offer insights into the research on logic reasoning among non-sequential elements.

[Arxiv](https://arxiv.org/abs/2408.03630)