# CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。

发布时间：2024年04月19日

`LLM应用` `网络安全` `人工智能安全`

> CyberSecEval 2: A Wide-Ranging Cybersecurity Evaluation Suite for Large Language Models

# 摘要

> 大型语言模型（LLMs）带来了前所未有的安全挑战，尽管目前缺乏全面评估这些风险的工具。我们推出了BenchmarkName，一个创新的基准测试框架，旨在衡量并降低LLMs的安全风险。本研究开拓了两个新的测试维度：提示注入和代码解释器的滥用。我们对一系列业界领先的LLMs进行了评估，包括GPT-4、Mistral、Meta Llama 3 70B-Instruct和Code Llama。研究发现，防御攻击的风险仍然是一个难题，所有测试的模型在提示注入测试中的成功率介于26%到41%之间。此外，我们提出了安全性与实用性之间的权衡问题：为了提高安全性，LLMs可能会错误地拒绝一些无害的提示，从而影响其实用性。我们引入了错误拒绝率（FRR）这一概念，用以量化这种权衡。为了具体展示，我们设计了一个新的测试集，用以评估网络攻击辅助性风险的FRR。研究发现，许多LLMs能够在拒绝大多数危险请求的同时，顺利响应一些边缘性的良性请求。此外，我们还评估了LLMs在自动化软件漏洞利用这一核心网络安全任务上的能力。鉴于LLMs的攻击潜力备受关注，我们通过构建四个代表性问题的测试集来量化这一能力。结果显示，具备编码功能的模型在性能上优于那些没有编码功能的模型，但LLMs要想在漏洞利用生成上达到熟练水平，仍需进一步的研究和开发。我们的代码已开源，可供其他研究人员用来评估LLMs的安全性能。

> Large language models (LLMs) introduce new security risks, but there are few comprehensive evaluation suites to measure and reduce these risks. We present BenchmarkName, a novel benchmark to quantify LLM security risks and capabilities. We introduce two new areas for testing: prompt injection and code interpreter abuse. We evaluated multiple state-of-the-art (SOTA) LLMs, including GPT-4, Mistral, Meta Llama 3 70B-Instruct, and Code Llama. Our results show that conditioning away risk of attack remains an unsolved problem; for example, all tested models showed between 26% and 41% successful prompt injection tests. We further introduce the safety-utility tradeoff: conditioning an LLM to reject unsafe prompts can cause the LLM to falsely reject answering benign prompts, which lowers utility. We propose quantifying this tradeoff using False Refusal Rate (FRR). As an illustration, we introduce a novel test set to quantify FRR for cyberattack helpfulness risk. We find many LLMs able to successfully comply with "borderline" benign requests while still rejecting most unsafe requests. Finally, we quantify the utility of LLMs for automating a core cybersecurity task, that of exploiting software vulnerabilities. This is important because the offensive capabilities of LLMs are of intense interest; we quantify this by creating novel test sets for four representative problems. We find that models with coding capabilities perform better than those without, but that further work is needed for LLMs to become proficient at exploit generation. Our code is open source and can be used to evaluate other LLMs.

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/cyberattack_compliance_v5.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/llm_perf_ffr_tradeoff_v5.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/prompt_inject_eval_v5.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/prompt_injection_logic_vs_security_v5.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/code_exp_eval_v5.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/code_interp_scores_v6.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/bof_v3.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/string_constraint_example_v3.png)

![CyberSecEval 2：一套全面覆盖的大型语言模型网络安全评估工具集。](../../../paper_images/2404.13161/sqli_example_v3.png)

[Arxiv](https://arxiv.org/abs/2404.13161)