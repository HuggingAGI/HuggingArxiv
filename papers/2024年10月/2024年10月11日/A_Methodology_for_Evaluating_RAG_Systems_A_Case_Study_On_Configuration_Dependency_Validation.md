# RAG 系统评估方法论：配置依赖验证案例研究

发布时间：2024年10月11日

`RAG` `软件工程` `人工智能`

> A Methodology for Evaluating RAG Systems: A Case Study On Configuration Dependency Validation

# 摘要

> RAG 是一个多组件、多决策的系统，旨在提升大型语言模型的性能，并解决其在知识幻觉和更新缺失方面的短板。然而，RAG 系统的开发充满实验性，需要一套系统且合理的方法论来确保结果的可靠。尽管 RAG 技术备受关注，但目前尚无公认的评估标准。本文首次提出了一套评估 RAG 系统的蓝图方法，并在软件工程的配置依赖性验证任务中验证了其有效性。我们的两大创新点包括：(i) 一套新颖且可复用的 RAG 评估方法，附带示范指南；(ii) 基于此方法开发的 RAG 系统，在依赖性验证领域达到了顶尖准确率。关键在于，选择合适的基线和指标、进行系统化的失败分析以改进 RAG，以及透明报告关键设计决策，以促进系统的复制和评估。

> Retrieval-augmented generation (RAG) is an umbrella of different components, design decisions, and domain-specific adaptations to enhance the capabilities of large language models and counter their limitations regarding hallucination and outdated and missing knowledge. Since it is unclear which design decisions lead to a satisfactory performance, developing RAG systems is often experimental and needs to follow a systematic and sound methodology to gain sound and reliable results. However, there is currently no generally accepted methodology for RAG evaluation despite a growing interest in this technology. In this paper, we propose a first blueprint of a methodology for a sound and reliable evaluation of RAG systems and demonstrate its applicability on a real-world software engineering research task: the validation of configuration dependencies across software technologies. In summary, we make two novel contributions: (i) A novel, reusable methodological design for evaluating RAG systems, including a demonstration that represents a guideline, and (ii) a RAG system, which has been developed following this methodology, that achieves the highest accuracy in the field of dependency validation. For the blueprint's demonstration, the key insights are the crucial role of choosing appropriate baselines and metrics, the necessity for systematic RAG refinements derived from qualitative failure analysis, as well as the reporting practices of key design decision to foster replication and evaluation.

[Arxiv](https://arxiv.org/abs/2410.08801)