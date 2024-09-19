# TART：一款开源工具增强框架，专为可解释的表格推理而生

发布时间：2024年09月18日

`LLM应用` `数据处理` `人工智能`

> TART: An Open-Source Tool-Augmented Framework for Explainable Table-based Reasoning

# 摘要

> 当前的 LLM 在理解表格结构和进行精确数值推理方面表现不佳，这对 TQA 和 TFV 等任务至关重要。为此，我们推出了 TART 框架，将 LLM 与专用工具结合。TART 包括表格格式化器、工具制造者和解释生成器三大组件，确保数据准确性和推理透明度。我们还发布了 TOOLTAB 数据集，专门用于训练 LLM 的表格工具集成能力。实验显示，TART 在数据处理精度和推理清晰度上显著优于现有方法，如思维链。特别是，TART 与 CodeLlama 结合，达到了 GPT-3.5-turbo 90.0% 的准确率，展示了其在实际应用中的强大性能。所有资源均可在 https://github.com/XinyuanLu00/TART 获取。

> Current Large Language Models (LLMs) exhibit limited ability to understand table structures and to apply precise numerical reasoning, which is crucial for tasks such as table question answering (TQA) and table-based fact verification (TFV). To address these challenges, we introduce our Tool-Augmented Reasoning framework for Tables (TART), which integrates LLMs with specialized tools. TART contains three key components: a table formatter to ensure accurate data representation, a tool maker to develop specific computational tools, and an explanation generator to maintain explainability. We also present the TOOLTAB dataset, a new benchmark designed specifically for training LLMs in table-tool integration. Our experiments indicate that TART achieves substantial improvements over existing methods (e.g., Chain-of-Thought) by improving both the precision of data processing and the clarity of the reasoning process. Notably, TART paired with CodeLlama achieves 90.0% of the accuracy of the closed-sourced LLM GPT-3.5-turbo, highlighting its robustness in diverse real-world scenarios. All the code and data are available at https://github.com/XinyuanLu00/TART.

[Arxiv](https://arxiv.org/abs/2409.11724)