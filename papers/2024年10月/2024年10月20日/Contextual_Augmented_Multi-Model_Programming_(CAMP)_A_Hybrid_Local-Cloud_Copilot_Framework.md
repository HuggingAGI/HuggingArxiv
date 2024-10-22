# CAMP：一种结合本地与云端优势的智能编程助手框架

发布时间：2024年10月20日

`LLM应用` `软件开发` `人工智能`

> Contextual Augmented Multi-Model Programming (CAMP): A Hybrid Local-Cloud Copilot Framework

# 摘要

> 云端大型语言模型 (LLM) 的进步彻底改变了 AI 辅助编程。然而，由于计算需求和沙盒限制，LLM 在 Apple 生态系统（如 iOS 应用、macOS）中的本地开发环境集成仍面临挑战。本文介绍的 CAMP 框架，通过本地 RAG 模型从代码库中提取上下文信息，优化云模型性能，增强 LLM 在本地 IDE 中的能力。该方法在 Xcode 的 Copilot 工具中实现，支持自动代码完成、文档生成、错误检测和智能用户交互。实验结果显示，CAMP 系统在代码质量和用户接受度方面表现优异，为 AI 辅助编程领域做出了重要贡献。

> The advancements in cloud-based Large Languages Models (LLMs) have revolutionized AI-assisted programming. However, their integration into certain local development environments like ones within the Apple software ecosystem (e.g., iOS apps, macOS) remains challenging due to computational demands and sandboxed constraints. This paper presents CAMP, a multi-model AI-assisted programming framework that consists of a local model that employs Retrieval-Augmented Generation (RAG) to retrieve contextual information from the codebase to facilitate context-aware prompt construction thus optimizing the performance of the cloud model, empowering LLMs' capabilities in local Integrated Development Environments (IDEs). The methodology is actualized in Copilot for Xcode, an AI-assisted programming tool crafted for Xcode that employs the RAG module to address software constraints and enables diverse generative programming tasks, including automatic code completion, documentation, error detection, and intelligent user-agent interaction. The results from objective experiments on generated code quality and subjective experiments on user adoption collectively demonstrate the pilot success of the proposed system and mark its significant contributions to the realm of AI-assisted programming.

[Arxiv](https://arxiv.org/abs/2410.15285)