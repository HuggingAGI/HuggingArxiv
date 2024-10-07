# One2set 与大型语言模型联手，成为关键短语生成的黄金搭档。

发布时间：2024年10月04日

`LLM应用` `信息提取`

> One2set + Large Language Model: Best Partners for Keyphrase Generation

# 摘要

> 关键短语生成 (KPG) 旨在自动提取文档的核心概念。主流方法包括 one2seq 和 one2set。近期，大型语言模型 (LLM) 在 KPG 中的应用备受关注。初步实验显示，单一模型难以同时实现高召回率和精确度。分析发现：one2set 召回率高，但训练中监督信号分配不当；LLM 擅长选择，但现有方法常产生冗余。为此，我们提出“生成-选择”框架，先用 one2set 生成候选，再用 LLM 筛选关键短语。我们还进行了两项改进：设计基于最优传输的分配策略，以及将选择建模为序列标注任务。实验表明，该框架在多个数据集上显著超越现有模型，尤其在预测缺失关键短语方面表现突出。

> Keyphrase generation (KPG) aims to automatically generate a collection of phrases representing the core concepts of a given document. The dominant paradigms in KPG include one2seq and one2set. Recently, there has been increasing interest in applying large language models (LLMs) to KPG. Our preliminary experiments reveal that it is challenging for a single model to excel in both recall and precision. Further analysis shows that: 1) the one2set paradigm owns the advantage of high recall, but suffers from improper assignments of supervision signals during training; 2) LLMs are powerful in keyphrase selection, but existing selection methods often make redundant selections. Given these observations, we introduce a generate-then-select framework decomposing KPG into two steps, where we adopt a one2set-based model as generator to produce candidates and then use an LLM as selector to select keyphrases from these candidates. Particularly, we make two important improvements on our generator and selector: 1) we design an Optimal Transport-based assignment strategy to address the above improper assignments; 2) we model the keyphrase selection as a sequence labeling task to alleviate redundant selections. Experimental results on multiple benchmark datasets show that our framework significantly surpasses state-of-the-art models, especially in absent keyphrase prediction.

[Arxiv](https://arxiv.org/abs/2410.03421)