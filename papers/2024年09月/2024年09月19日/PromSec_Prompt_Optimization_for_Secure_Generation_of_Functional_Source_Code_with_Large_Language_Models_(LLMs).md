# PromSec：通过 LLM 生成安全功能源代码的提示优化

发布时间：2024年09月19日

`LLM应用` `软件开发` `网络安全`

> PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models (LLMs)

# 摘要

> LLM 生成高质量源代码的能力虽能节省开发时间和成本，但常因训练数据不安全而引入漏洞。为此，我们提出了 PromSec 算法，通过结合 gGAN 的代码漏洞清除和 LLM 的代码生成，形成交互循环，确保生成代码的安全性和功能性。实验证明，PromSec 不仅有效提升代码安全性，还大幅减少了操作时间和成本。此外，PromSec 优化的提示可跨语言和模型通用，适用于未见过的漏洞。这一研究为 LLM 在实际软件开发中的安全应用提供了有力支持。

> The capability of generating high-quality source code using large language models (LLMs) reduces software development time and costs. However, they often introduce security vulnerabilities due to training on insecure open-source data. This highlights the need for ensuring secure and functional code generation. This paper introduces PromSec, an algorithm for prom optimization for secure and functioning code generation using LLMs. In PromSec, we combine 1) code vulnerability clearing using a generative adversarial graph neural network, dubbed as gGAN, to fix and reduce security vulnerabilities in generated codes and 2) code generation using an LLM into an interactive loop, such that the outcome of the gGAN drives the LLM with enhanced prompts to generate secure codes while preserving their functionality. Introducing a new contrastive learning approach in gGAN, we formulate code-clearing and generation as a dual-objective optimization problem, enabling PromSec to notably reduce the number of LLM inferences. PromSec offers a cost-effective and practical solution for generating secure, functional code. Extensive experiments conducted on Python and Java code datasets confirm that PromSec effectively enhances code security while upholding its intended functionality. Our experiments show that while a state-of-the-art approach fails to address all code vulnerabilities, PromSec effectively resolves them. Moreover, PromSec achieves more than an order-of-magnitude reduction in operation time, number of LLM queries, and security analysis costs. Furthermore, prompts optimized with PromSec for a certain LLM are transferable to other LLMs across programming languages and generalizable to unseen vulnerabilities in training. This study is a step in enhancing the trustworthiness of LLMs for secure and functional code generation, supporting their integration into real-world software development.

[Arxiv](https://arxiv.org/abs/2409.12699)