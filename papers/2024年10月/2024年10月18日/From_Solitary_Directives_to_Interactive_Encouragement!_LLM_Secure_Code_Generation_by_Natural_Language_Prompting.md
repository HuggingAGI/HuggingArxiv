# 从单一指令到互动激励，自然语言提示助力 LLM 安全代码生成。

发布时间：2024年10月18日

`LLM应用` `软件开发` `网络安全`

> From Solitary Directives to Interactive Encouragement! LLM Secure Code Generation by Natural Language Prompting

# 摘要

> 大型语言模型 (LLM) 在代码生成领域展现出巨大潜力，但其安全性和可用性仍需深入研究。为此，我们推出了 SecCode 框架，通过创新的交互式鼓励提示 (EP) 技术，仅使用自然语言 (NL) 提示生成安全代码。SecCode 分三个阶段运行：代码生成、漏洞检测与修复、漏洞交叉检查与代码优化，通过多次迭代提升安全性。实验表明，SecCode 在多个 LLM 和基准数据集上表现优异，显著提高了代码安全性。例如，经过 10 次 EP 迭代，修复成功率高达 89%。这是首次仅用 NL 提示实现安全代码生成，我们已开源代码，期待社区共同推进这一领域。

> Large Language Models (LLMs) have shown remarkable potential in code generation, making them increasingly important in the field. However, the security issues of generated code have not been fully addressed, and the usability of LLMs in code generation still requires further exploration.
  This work introduces SecCode, a framework that leverages an innovative interactive encouragement prompting (EP) technique for secure code generation with \textit{only NL} prompts. This approach ensures that the prompts can be easily shared and understood by general users. SecCode functions through three stages: 1) Code Generation using NL Prompts; 2) Code Vulnerability Detection and Fixing, utilising our proposed encouragement prompting; 3) Vulnerability Cross-Checking and Code Security Refinement. These stages are executed in multiple interactive iterations to progressively enhance security. By using both proprietary LLMs (i.e., GPT-3.5 Turbo, GPT-4 and GPT-4o) and open-source LLMs (i.e., Llama 3.1 8B Instruct, DeepSeek Coder V2 Lite Instruct) evaluated on three benchmark datasets, extensive experimental results show that our proposed SecCode greatly outperforms compared baselines, generating secure code with a high vulnerability correction rate. For example, SecCode exhibits a high fix success rate of over 76\% after running 5 automated EP interactive iterations and over 89\% after running 10 automated EP interactive iterations. To the best of our knowledge, this work is the first to formulate secure code generation with NL prompts only. We have open-sourced our code and encourage the community to focus on secure code generation.

[Arxiv](https://arxiv.org/abs/2410.14321)