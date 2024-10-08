# ORAssistant：专为 OpenROAD 设计的 RAG 基础对话助手

发布时间：2024年10月04日

`RAG` `半导体` `人工智能`

> ORAssistant: A Custom RAG-based Conversational Assistant for OpenROAD

# 摘要

> 开源 EDA 工具正通过解决商业工具的复杂性、成本和访问难题，迅速革新芯片设计。大型语言模型 (LLM) 的进步通过在设置、决策和自动化等任务中提供用户支持，进一步提升了设计效率。本文介绍的 ORAssistant，基于 RAG 技术，是 OpenROAD 的对话助手，旨在通过针对安装、命令使用、流程设置和执行等常见查询的上下文响应，优化 OpenROAD 流程的用户体验。ORAssistant 现已整合 OpenROAD、OpenROAD-flow-scripts、Yosys、OpenSTA 和 KLayout，数据模型源自公开文档和 GitHub 资源。其架构可扩展，支持其他开源工具和 LLM 模型。我们采用 Google Gemini 作为基础 LLM 模型进行构建和测试，早期评估显示，基于 RAG 的模型在性能和准确性上显著优于未微调的 LLM。

> Open-source Electronic Design Automation (EDA) tools are rapidly transforming chip design by addressing key barriers of commercial EDA tools such as complexity, costs, and access. Recent advancements in Large Language Models (LLMs) have further enhanced efficiency in chip design by providing user assistance across a range of tasks like setup, decision-making, and flow automation. This paper introduces ORAssistant, a conversational assistant for OpenROAD, based on Retrieval-Augmented Generation (RAG). ORAssistant aims to improve the user experience for the OpenROAD flow, from RTL-GDSII by providing context-specific responses to common user queries, including installation, command usage, flow setup, and execution, in prose format. Currently, ORAssistant integrates OpenROAD, OpenROAD-flow-scripts, Yosys, OpenSTA, and KLayout. The data model is built from publicly available documentation and GitHub resources. The proposed architecture is scalable, supporting extensions to other open-source tools, operating modes, and LLM models. We use Google Gemini as the base LLM model to build and test ORAssistant. Early evaluation results of the RAG-based model show notable improvements in performance and accuracy compared to non-fine-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2410.03845)