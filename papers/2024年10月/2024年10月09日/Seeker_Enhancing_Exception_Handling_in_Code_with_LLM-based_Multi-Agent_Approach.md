# Seeker：借助 LLM 多代理技术，提升代码异常处理的效率

发布时间：2024年10月09日

`Agent` `软件开发` `开源项目`

> Seeker: Enhancing Exception Handling in Code with LLM-based Multi-Agent Approach

# 摘要

> 在软件开发中，不当的异常处理会严重损害代码的健壮性。尽管异常处理要求高，但许多开发者难以应对，导致代码脆弱。尤其在开源项目中，这一问题尤为突出，影响软件生态质量。为此，我们利用大型语言模型 (LLM) 改进异常处理，并发现三个关键问题：脆弱代码检测不敏感、异常类型捕获不准确、处理方案扭曲。这些问题普遍存在，表明健壮的异常处理常被忽视。我们提出 Seeker，一个多代理框架，通过 Scanner、Detector、Predator、Ranker 和 Handler 协助 LLM 更有效地处理异常。这是首次系统研究利用 LLM 增强异常处理，为提升代码可靠性提供新思路。

> In real world software development, improper or missing exception handling can severely impact the robustness and reliability of code. Exception handling mechanisms require developers to detect, capture, and manage exceptions according to high standards, but many developers struggle with these tasks, leading to fragile code. This problem is particularly evident in open source projects and impacts the overall quality of the software ecosystem. To address this challenge, we explore the use of large language models (LLMs) to improve exception handling in code. Through extensive analysis, we identify three key issues: Insensitive Detection of Fragile Code, Inaccurate Capture of Exception Types, and Distorted Handling Solutions. These problems are widespread across real world repositories, suggesting that robust exception handling practices are often overlooked or mishandled. In response, we propose Seeker, a multi agent framework inspired by expert developer strategies for exception handling. Seeker uses agents: Scanner, Detector, Predator, Ranker, and Handler to assist LLMs in detecting, capturing, and resolving exceptions more effectively. Our work is the first systematic study on leveraging LLMs to enhance exception handling practices, providing valuable insights for future improvements in code reliability.

[Arxiv](https://arxiv.org/abs/2410.06949)