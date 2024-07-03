# AI 编写的代码，真的无懈可击吗？通过 CodeSecEval 工具，我们评估了大型语言模型在安全代码生成方面的表现。

发布时间：2024年07月02日

`LLM应用` `软件工程` `网络安全`

> Is Your AI-Generated Code Really Secure? Evaluating Large Language Models on Secure Code Generation with CodeSecEval

# 摘要

> 大型语言模型（LLM）在代码生成与修复领域取得了显著进展，惠及了从初学者到资深开发者的广泛群体。然而，这些模型在训练过程中使用来自开源平台如GitHub的未净化数据，无形中增加了传播安全漏洞的风险。尽管已有研究探讨了代码LLM的安全性，但全面提升其安全性能仍面临挑战。为此，我们开展了一项全面研究，旨在精确评估并强化代码LLM的安全特性。我们精心设计了CodeSecEval数据集，涵盖44种关键漏洞类型，包含180个样本，为代码生成与修复任务中的模型安全评估奠定了基础。实验表明，现有模型在代码生成与修复过程中往往忽视安全问题，导致易受攻击代码的产生。为此，我们提出了一系列策略，通过利用漏洞感知信息与不安全代码解释，有效缓解安全风险。研究还揭示，某些特定类型的漏洞对模型性能构成较大挑战，影响其在实际应用中的表现。基于这些发现，我们预期本研究将对软件工程领域产生积极影响，推动开发更安全、更可靠的LLM训练与应用方法。

> Large language models (LLMs) have brought significant advancements to code generation and code repair, benefiting both novice and experienced developers. However, their training using unsanitized data from open-source repositories, like GitHub, raises the risk of inadvertently propagating security vulnerabilities. Despite numerous studies investigating the safety of code LLMs, there remains a gap in comprehensively addressing their security features. In this work, we aim to present a comprehensive study aimed at precisely evaluating and enhancing the security aspects of code LLMs. To support our research, we introduce CodeSecEval, a meticulously curated dataset designed to address 44 critical vulnerability types with 180 distinct samples. CodeSecEval serves as the foundation for the automatic evaluation of code models in two crucial tasks: code generation and code repair, with a strong emphasis on security. Our experimental results reveal that current models frequently overlook security issues during both code generation and repair processes, resulting in the creation of vulnerable code. In response, we propose different strategies that leverage vulnerability-aware information and insecure code explanations to mitigate these security vulnerabilities. Furthermore, our findings highlight that certain vulnerability types particularly challenge model performance, influencing their effectiveness in real-world applications. Based on these findings, we believe our study will have a positive impact on the software engineering community, inspiring the development of improved methods for training and utilizing LLMs, thereby leading to safer and more trustworthy model deployment.

[Arxiv](https://arxiv.org/abs/2407.02395)