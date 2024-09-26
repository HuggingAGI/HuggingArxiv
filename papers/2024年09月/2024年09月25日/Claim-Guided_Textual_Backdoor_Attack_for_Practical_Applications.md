# 基于声明的文本后门攻击在实际应用中的探索

发布时间：2024年09月25日

`LLM应用` `网络安全`

> Claim-Guided Textual Backdoor Attack for Practical Applications

# 摘要

> 随着自然语言处理和大型语言模型的进步，新的安全漏洞如后门攻击逐渐显现。传统后门攻击需在模型分发后进行输入操作，限制了其实际应用。为此，我们推出了Claim-Guided Backdoor Attack (CGBA)，利用文本声明作为触发器，无需额外操作。CGBA通过声明提取、聚类和有针对性的训练，使模型在特定声明上表现异常，同时保持对干净数据的正常处理。该方法在多种数据集和模型上表现出色，极大提升了实际后门攻击的可行性。相关代码和数据将在https://github.com/PaperCGBA/CGBA发布。

> Recent advances in natural language processing and the increased use of large language models have exposed new security vulnerabilities, such as backdoor attacks. Previous backdoor attacks require input manipulation after model distribution to activate the backdoor, posing limitations in real-world applicability. Addressing this gap, we introduce a novel Claim-Guided Backdoor Attack (CGBA), which eliminates the need for such manipulations by utilizing inherent textual claims as triggers. CGBA leverages claim extraction, clustering, and targeted training to trick models to misbehave on targeted claims without affecting their performance on clean data. CGBA demonstrates its effectiveness and stealthiness across various datasets and models, significantly enhancing the feasibility of practical backdoor attacks. Our code and data will be available at https://github.com/PaperCGBA/CGBA.

[Arxiv](https://arxiv.org/abs/2409.16618)