# HexaCoder：借助 Oracle 引导的合成数据，实现安全代码生成。

发布时间：2024年09月10日

`LLM应用` `软件开发` `网络安全`

> HexaCoder: Secure Code Generation via Oracle-Guided Synthetic Training Data

# 摘要

> 大型语言模型（LLM）在自动代码生成领域展现出巨大潜力，支撑着 GitHub Copilot 等工具。然而，最新研究表明，许多 LLM 生成的代码存在严重安全漏洞。尽管先前研究尝试通过训练生成安全代码的模型来解决这一问题，但受限于数据获取困难和数据准备繁琐，效果有限。本文提出 HexaCoder，一种通过自动合成安全代码来提升 LLM 生成安全代码能力的新方法，有效减轻了寻找合适训练数据的负担。HexaCoder 包含两大核心组件：oracle 引导的数据合成管道和两步安全代码生成流程。数据合成管道利用先进 LLM 修复漏洞代码，生成特定 CWE 类型的漏洞与修复代码对。安全 oracle 识别并修复漏洞，通过扩展或编辑代码，结合 LoRA 方法创建微调数据对。微调数据集包含必要的安全库和代码，为两步生成法奠定基础，使模型在生成主代码前集成安全库，相比基线方法，生成的漏洞代码减少高达 85%。我们在四个 LLM 上对三个基准进行了广泛评估，结果显示 HexaCoder 不仅显著提升代码安全性，还保持了高度的功能正确性。

> Large language models (LLMs) have shown great potential for automatic code generation and form the basis for various tools such as GitHub Copilot. However, recent studies highlight that many LLM-generated code contains serious security vulnerabilities. While previous work tries to address this by training models that generate secure code, these attempts remain constrained by limited access to training data and labor-intensive data preparation.
  In this paper, we introduce HexaCoder, a novel approach to enhance the ability of LLMs to generate secure codes by automatically synthesizing secure codes, which reduces the effort of finding suitable training data. HexaCoder comprises two key components: an oracle-guided data synthesis pipeline and a two-step process for secure code generation. The data synthesis pipeline generates pairs of vulnerable and fixed codes for specific Common Weakness Enumeration (CWE) types by utilizing a state-of-the-art LLM for repairing vulnerable code. A security oracle identifies vulnerabilities, and a state-of-the-art LLM repairs them by extending and/or editing the codes, creating data pairs for fine-tuning using the Low-Rank Adaptation (LoRA) method. Each example of our fine-tuning dataset includes the necessary security-related libraries and code that form the basis of our novel two-step generation approach. This allows the model to integrate security-relevant libraries before generating the main code, significantly reducing the number of generated vulnerable codes by up to 85% compared to the baseline methods. We perform extensive evaluations on three different benchmarks for four LLMs, demonstrating that HexaCoder not only improves the security of the generated code but also maintains a high level of functional correctness.

[Arxiv](https://arxiv.org/abs/2409.06446)