# 大型语言模型在安全代码评估中的应用：一项跨语言的实证探索

发布时间：2024年08月12日

`LLM应用` `软件开发` `网络安全`

> Large Language Models for Secure Code Assessment: A Multi-Language Empirical Study

# 摘要

> 当前的漏洞检测研究多聚焦于C/C++代码，语言多样性不足。因此，深度学习方法（包括大型语言模型LLMs）在检测其他语言软件漏洞方面的效果尚未充分探索。本文中，我们评估了LLMs在不同提示和角色策略下检测和分类CWE的有效性。实验涵盖六种顶尖预训练LLMs及五种编程语言，并构建了多语言漏洞数据集以确保代表性。结果显示，GPT-4o在少样本设置下表现最佳。此外，我们开发的CODEGUARDIAN库与VSCode集成，支持实时LLM辅助漏洞分析，并通过行业用户研究验证了其提升检测效率和准确性的效果。

> Most vulnerability detection studies focus on datasets of vulnerabilities in C/C++ code, offering limited language diversity. Thus, the effectiveness of deep learning methods, including large language models (LLMs), in detecting software vulnerabilities beyond these languages is still largely unexplored. In this paper, we evaluate the effectiveness of LLMs in detecting and classifying Common Weakness Enumerations (CWE) using different prompt and role strategies. Our experimental study targets six state-of-the-art pre-trained LLMs (GPT-3.5- Turbo, GPT-4 Turbo, GPT-4o, CodeLLama-7B, CodeLLama- 13B, and Gemini 1.5 Pro) and five programming languages: Python, C, C++, Java, and JavaScript. We compiled a multi-language vulnerability dataset from different sources, to ensure representativeness. Our results showed that GPT-4o achieves the highest vulnerability detection and CWE classification scores using a few-shot setting. Aside from the quantitative results of our study, we developed a library called CODEGUARDIAN integrated with VSCode which enables developers to perform LLM-assisted real-time vulnerability analysis in real-world security scenarios. We have evaluated CODEGUARDIAN with a user study involving 22 developers from the industry. Our study showed that, by using CODEGUARDIAN, developers are more accurate and faster at detecting vulnerabilities.

[Arxiv](https://arxiv.org/abs/2408.06428)