# SWE-Bench+：LLM 编码基准的升级版

发布时间：2024年10月10日

`LLM应用` `软件工程` `数据分析`

> SWE-Bench+: Enhanced Coding Benchmark for LLMs

# 摘要

> 在软件工程领域，大型语言模型（LLM）为编码提供了有力支持。为了在实际编码场景中严格评估 LLM，Carlos 等人创建了 SWE-bench 数据集，涵盖了 2,294 个真实 GitHub 问题及其对应的拉取请求，这些数据来自 12 个常用的 Python 仓库。近期，多个基于 LLM 的工具包在此数据集上进行了开发与评估。然而，SWE-bench 的质量评估仍未系统化。本文通过实证分析 SWE-bench 数据集，填补了这一空白。我们手动筛选了 SWEAgent + GPT-4 成功解决的问题，并对比了模型生成的补丁与实际拉取请求。研究期间，SWE-Agent+GPT-4 在 SWE-bench 排行榜上位居榜首。分析发现，SWE-bench 存在两大问题：1) 32.67% 的成功补丁涉及作弊，即解决方案已在问题报告或评论中泄露；2) 31.08% 的通过补丁因测试用例不足而存疑。过滤这些问题后，SWE-Agent+GPT-4 的解决率从 12.47% 骤降至 3.97%。此外，SWE-bench 的两个变体也存在类似数据质量问题。值得注意的是，超过 94% 的问题创建于 LLM 知识截止日期之前，潜在的数据泄露风险不容忽视。

> Large Language Models (LLMs) in Software Engineering (SE) can offer assistance for coding. To facilitate a rigorous evaluation of LLMs in practical coding contexts, Carlos et al. introduced the SWE-bench dataset, which comprises 2,294 real-world GitHub issues and their corresponding pull requests, collected from 12 widely used Python repositories. Several impressive LLM-based toolkits recently are developed and evaluated on this dataset. However, a systematic evaluation of the quality of SWE-bench remains missing. In this paper, we addressed this gap by presenting an empirical analysis of the SWE-bench dataset. We conducted a manual screening of instances where SWEAgent + GPT-4 successfully resolved issues by comparing the model-generated patches with the actual pull requests. SWE-Agent+GPT-4 was at the top of SWE-bench leaderboard during the time of our study. Our analysis reveals some critical issues with the SWE-bench dataset: 1) 32.67% of the successful patches involve cheating as the solutions were directly provided in the issue report or the comments. We refer to as solution leakage problem. 2) 31.08% of the passed patches are suspicious patches due to weak test cases, i.e., the tests were not adequate to verify the correctness of a patch. When we filtered out these problematic issues, the resolution rate of SWE-Agent+GPT-4 dropped from 12.47% to 3.97%. We also observed that the same data quality issues also exist in the two variants of SWE-bench, i.e., SWE-bench Lite and SWE-Bench Verified. In addition, over 94% of the issues were created before LLM's knowledge cutoff dates, posing potential data leakage issues.

[Arxiv](https://arxiv.org/abs/2410.06992)