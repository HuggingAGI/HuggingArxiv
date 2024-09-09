# 借助大型语言模型，精炼 Wikidata 的分类体系

发布时间：2024年09月06日

`LLM应用` `知识图谱` `数据管理`

> Refining Wikidata Taxonomy using Large Language Models

# 摘要

> Wikidata 因其协作特性而拥有复杂的分类法，存在实例与类之间的模糊性、分类路径的不准确性、循环问题及类间冗余等挑战。手动清理既耗时又易出错。我们推出 WiKC，利用 LLM 和图挖掘技术自动优化 Wikidata 分类法。通过零-shot 提示，我们实现了链接切割和类合并等操作。从内在和外在角度评估，WiKC 在实体类型任务中展现了其实用价值。

> Due to its collaborative nature, Wikidata is known to have a complex taxonomy, with recurrent issues like the ambiguity between instances and classes, the inaccuracy of some taxonomic paths, the presence of cycles, and the high level of redundancy across classes. Manual efforts to clean up this taxonomy are time-consuming and prone to errors or subjective decisions. We present WiKC, a new version of Wikidata taxonomy cleaned automatically using a combination of Large Language Models (LLMs) and graph mining techniques. Operations on the taxonomy, such as cutting links or merging classes, are performed with the help of zero-shot prompting on an open-source LLM. The quality of the refined taxonomy is evaluated from both intrinsic and extrinsic perspectives, on a task of entity typing for the latter, showing the practical interest of WiKC.

[Arxiv](https://arxiv.org/abs/2409.04056)