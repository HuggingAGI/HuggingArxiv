# 利用迭代实验编程自动化大型多模态模型的性能基准测试

发布时间：2024年06月18日

`LLM应用

理由：这篇论文介绍了一个名为APEx的自动编程实验框架，它利用大型语言模型（LLM）来自动化大型多模态模型（LMMs）的评估过程。这个框架通过自然语言描述的研究问题，自动生成并执行实验，构建科学报告，并最终优化报告以向用户呈现结果。这个工具的应用性质表明它是在实际场景中使用LLM来解决特定问题，因此属于LLM应用类别。` `人工智能` `自动化测试`

> Automatic benchmarking of large multimodal models via iterative experiment programming

# 摘要

> 评估大型多模态模型（LMMs）的能力往往需要定制评估，这通常涉及大量手工劳动，使得评估既繁琐又成本高昂。本文介绍了APEx——自动编程实验框架，这是首个自动化LMMs基准测试的工具。APEx通过自然语言描述的研究问题，利用大型语言模型（LLM）和预设工具库，自动生成并执行一系列实验，逐步构建科学报告。该报告不仅指导测试流程，还根据研究进展智能选择实验并判断结果是否足以得出结论。最终，LLM会优化报告，以自然语言形式向用户呈现结果。得益于其模块化设计，APEx灵活且易于扩展，能随着新工具的加入而进化。实证表明，APEx不仅能复现现有研究成果，还支持任意分析和假设检验。

> Assessing the capabilities of large multimodal models (LMMs) often requires the creation of ad-hoc evaluations. Currently, building new benchmarks requires tremendous amounts of manual work for each specific analysis. This makes the evaluation process tedious and costly. In this paper, we present APEx, Automatic Programming of Experiments, the first framework for automatic benchmarking of LMMs. Given a research question expressed in natural language, APEx leverages a large language model (LLM) and a library of pre-specified tools to generate a set of experiments for the model at hand, and progressively compile a scientific report. The report drives the testing procedure: based on the current status of the investigation, APEx chooses which experiments to perform and whether the results are sufficient to draw conclusions. Finally, the LLM refines the report, presenting the results to the user in natural language. Thanks to its modularity, our framework is flexible and extensible as new tools become available. Empirically, APEx reproduces the findings of existing studies while allowing for arbitrary analyses and hypothesis testing.

[Arxiv](https://arxiv.org/abs/2406.12321)