# 展示：SGCode，一款灵活的提示优化系统，专为安全代码生成而设计。

发布时间：2024年09月11日

`LLM应用` `软件开发` `网络安全`

> Demo: SGCode: A Flexible Prompt-Optimizing System for Secure Generation of Code

# 摘要

> 本文推出 SGCode，一个灵活的提示优化系统，专为大型语言模型 (LLM) 生成安全代码而设计。SGCode 通过前端和后端 API 集成最新提示优化技术，使用户能轻松生成无漏洞代码、审查安全分析并切换优化方法，同时洞察模型与系统性能。我们在 AWS 服务器上结合 PromSec 部署 SGCode，利用 LLM 与安全工具及轻量级生成对抗图神经网络检测并修复代码漏洞。实验证明，SGCode 作为公共工具，能有效权衡模型效用、安全代码生成与系统成本。相较于直接提示 LLM，SGCode 成本微乎其微。访问地址：http://3.131.141.63:8501/。

> This paper introduces SGCode, a flexible prompt-optimizing system to generate secure code with large language models (LLMs). SGCode integrates recent prompt-optimization approaches with LLMs in a unified system accessible through front-end and back-end APIs, enabling users to 1) generate secure code, which is free of vulnerabilities, 2) review and share security analysis, and 3) easily switch from one prompt optimization approach to another, while providing insights on model and system performance. We populated SGCode on an AWS server with PromSec, an approach that optimizes prompts by combining an LLM and security tools with a lightweight generative adversarial graph neural network to detect and fix security vulnerabilities in the generated code. Extensive experiments show that SGCode is practical as a public tool to gain insights into the trade-offs between model utility, secure code generation, and system cost. SGCode has only a marginal cost compared with prompting LLMs. SGCode is available at: http://3.131.141.63:8501/.

[Arxiv](https://arxiv.org/abs/2409.07368)