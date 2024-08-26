# DOMAINEVAL：多领域代码生成的自动构建基准

发布时间：2024年08月23日

`LLM应用` `软件开发` `计算机安全`

> DOMAINEVAL: An Auto-Constructed Benchmark for Multi-Domain Code Generation

# 摘要

> HumanEval 等代码基准广泛用于评估大型语言模型（LLM）的能力，揭示其优劣。然而，现有基准主要针对常见编程任务（如冒泡排序、最大公约数），忽略了特定领域任务（如计算、系统、密码学）。为此，我们推出了多领域代码基准 DOMAINEVAL，全面测试 LLM 的编程技能。我们的自动化流程从代码仓库中提取数据，自动构建研究对象。通过 DOMAINEVAL 测试 12 个代表性 LLM，我们发现 LLM 在计算任务上表现出色，但在密码学和系统编程上则显不足，性能差距高达 68.94%。此外，增加样本数量能提升整体性能，但领域偏见可能加剧。本研究贡献包括 DOMAINEVAL 数据集、全自动基准构建流程，以及基于 LLM 在 DOMAINEVAL 上的表现识别其在代码生成任务中的局限性，为未来研究指明方向。排行榜详见 https://domaineval.github.io/。

> Code benchmarks such as HumanEval are widely adopted to evaluate the capabilities of Large Language Models (LLMs), providing insights into their strengths and weaknesses. However, current benchmarks primarily exercise LLMs' capability on common coding tasks (e.g., bubble sort, greatest common divisor), leaving domain-specific coding tasks (e.g., computation, system, cryptography) unexplored. To fill this gap, we propose a multi-domain code benchmark, DOMAINEVAL, designed to evaluate LLMs' coding capabilities thoroughly. Our pipeline works in a fully automated manner, enabling a push-bottom construction from code repositories into formatted subjects under study. Interesting findings are observed by evaluating 12 representative LLMs against DOMAINEVAL. We notice that LLMs are generally good at computation tasks while falling short on cryptography and system coding tasks. The performance gap can be as much as 68.94% (80.94% - 12.0%) in some LLMs. We also observe that generating more samples can increase the overall performance of LLMs, while the domain bias may even increase. The contributions of this study include a code generation benchmark dataset DOMAINEVAL, encompassing six popular domains, a fully automated pipeline for constructing code benchmarks, and an identification of the limitations of LLMs in code generation tasks based on their performance on DOMAINEVAL, providing directions for future research improvements. The leaderboard is available at https://domaineval.github.io/.

[Arxiv](https://arxiv.org/abs/2408.13204)