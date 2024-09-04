# ProphetFuzz：借助大型语言模型，仅凭文档即可全自动预测并模糊测试高风险选项组合。

发布时间：2024年09月01日

`LLM应用` `软件安全` `漏洞测试`

> ProphetFuzz: Fully Automated Prediction and Fuzzing of High-Risk Option Combinations with Only Documentation via Large Language Model

# 摘要

> 选项组合漏洞在软件安全测试中是一大难题，因其搜索空间巨大。传统方法通过变异或过滤技术处理，但效率低下，因为它们将所有组合视为同等可能存在漏洞，导致大量时间浪费在无漏洞目标上。本文中，我们采用精心设计的提示工程，引导大型语言模型预测高风险选项组合，并自动进行模糊测试，无需人工介入。我们开发的工具ProphetFuzz在52个程序的数据集上进行了测试，耗时10.44个CPU年。ProphetFuzz以平均每个程序8.69美元的成本，成功预测了1748个高风险组合。实验显示，72小时模糊测试后，ProphetFuzz发现了364个独特漏洞，占预测高风险组合的12.30%，比同期最先进技术高出32.85%。此外，我们对最新版本的程序进行了持续模糊测试，发现了140个漏洞，其中93个得到开发者确认，21个获得CVE编号。

> Vulnerabilities related to option combinations pose a significant challenge in software security testing due to their vast search space. Previous research primarily addressed this challenge through mutation or filtering techniques, which inefficiently treated all option combinations as having equal potential for vulnerabilities, thus wasting considerable time on non-vulnerable targets and resulting in low testing efficiency. In this paper, we utilize carefully designed prompt engineering to drive the large language model (LLM) to predict high-risk option combinations (i.e., more likely to contain vulnerabilities) and perform fuzz testing automatically without human intervention. We developed a tool called ProphetFuzz and evaluated it on a dataset comprising 52 programs collected from three related studies. The entire experiment consumed 10.44 CPU years. ProphetFuzz successfully predicted 1748 high-risk option combinations at an average cost of only \$8.69 per program. Results show that after 72 hours of fuzzing, ProphetFuzz discovered 364 unique vulnerabilities associated with 12.30\% of the predicted high-risk option combinations, which was 32.85\% higher than that found by state-of-the-art in the same timeframe. Additionally, using ProphetFuzz, we conducted persistent fuzzing on the latest versions of these programs, uncovering 140 vulnerabilities, with 93 confirmed by developers and 21 awarded CVE numbers.

[Arxiv](https://arxiv.org/abs/2409.00922)