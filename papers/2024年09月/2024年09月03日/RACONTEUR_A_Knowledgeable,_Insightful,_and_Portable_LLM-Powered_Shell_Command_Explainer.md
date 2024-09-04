# RACONTEUR：一款集知识、洞察与便携性于一体的 LLM 驱动 Shell 命令解释器

发布时间：2024年09月03日

`LLM应用` `网络安全` `人工智能`

> RACONTEUR: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer

# 摘要

> 恶意 shell 命令常是网络攻击的核心，但其复杂且隐蔽的代码结构令安全分析师难以理解。大型语言模型 (LLM) 的发展为 shell 命令提供了易于理解的解释。然而，通用 LLM 在解释 shell 命令时缺乏专业知识，且易产生误导。本文介绍的 Raconteur，是一款由 LLM 驱动、知识丰富、表达力强的 shell 命令解释器。它不仅解释命令的行为，还阐明其目的，并将解释转化为 MITRE ATT&CK 定义的标准技术与战术，助力理解命令的高级意图。为解释未公开的命令，我们还开发了文档检索器，辅助解释过程。通过大规模数据集的训练与实验，Raconteur 展现了其在 shell 命令解释中的高质量与深度洞察能力。

> Malicious shell commands are linchpins to many cyber-attacks, but may not be easy to understand by security analysts due to complicated and often disguised code structures. Advances in large language models (LLMs) have unlocked the possibility of generating understandable explanations for shell commands. However, existing general-purpose LLMs suffer from a lack of expert knowledge and a tendency to hallucinate in the task of shell command explanation. In this paper, we present Raconteur, a knowledgeable, expressive and portable shell command explainer powered by LLM. Raconteur is infused with professional knowledge to provide comprehensive explanations on shell commands, including not only what the command does (i.e., behavior) but also why the command does it (i.e., purpose). To shed light on the high-level intent of the command, we also translate the natural-language-based explanation into standard technique & tactic defined by MITRE ATT&CK, the worldwide knowledge base of cybersecurity. To enable Raconteur to explain unseen private commands, we further develop a documentation retriever to obtain relevant information from complementary documentations to assist the explanation process. We have created a large-scale dataset for training and conducted extensive experiments to evaluate the capability of Raconteur in shell command explanation. The experiments verify that Raconteur is able to provide high-quality explanations and in-depth insight of the intent of the command.

[Arxiv](https://arxiv.org/abs/2409.02074)