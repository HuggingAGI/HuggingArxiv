# 利用迭代实验编程自动化大型多模态模型的性能基准测试

发布时间：2024年06月18日

`LLM应用

这篇论文介绍了一个名为APEx的框架，它利用大型语言模型（LLM）自动化大型多模态模型（LMMs）的基准测试过程。用户通过自然语言提出研究问题，APEx则自动设计并执行实验，生成科学报告。这个工具展示了LLM在自动化和优化评估过程中的应用，因此属于LLM应用类别。` `人工智能` `科研工具`

> Automatic benchmarking of large multimodal models via iterative experiment programming

# 摘要

> 评估大型多模态模型（LMMs）往往需要定制评估，而构建新基准则需大量手工劳动，导致评估过程既繁琐又成本高昂。本文推出的APEx框架，即自动编程实验，是首个自动化LMMs基准测试的工具。用户只需以自然语言提出研究问题，APEx便能借助大型语言模型（LLM）和预设工具库，自动设计并执行实验，逐步生成科学报告。该报告不仅指导测试流程，还根据研究进展智能选择实验并判断结论的充分性。最终，LLM会优化报告，以自然语言呈现结果给用户。得益于其模块化设计，APEx灵活且易于扩展，能随着新工具的加入而进化。实证表明，APEx不仅能复现现有研究成果，还支持任意分析和假设检验。

> Assessing the capabilities of large multimodal models (LMMs) often requires the creation of ad-hoc evaluations. Currently, building new benchmarks requires tremendous amounts of manual work for each specific analysis. This makes the evaluation process tedious and costly. In this paper, we present APEx, Automatic Programming of Experiments, the first framework for automatic benchmarking of LMMs. Given a research question expressed in natural language, APEx leverages a large language model (LLM) and a library of pre-specified tools to generate a set of experiments for the model at hand, and progressively compile a scientific report. The report drives the testing procedure: based on the current status of the investigation, APEx chooses which experiments to perform and whether the results are sufficient to draw conclusions. Finally, the LLM refines the report, presenting the results to the user in natural language. Thanks to its modularity, our framework is flexible and extensible as new tools become available. Empirically, APEx reproduces the findings of existing studies while allowing for arbitrary analyses and hypothesis testing.

[Arxiv](https://arxiv.org/abs/2406.12321)