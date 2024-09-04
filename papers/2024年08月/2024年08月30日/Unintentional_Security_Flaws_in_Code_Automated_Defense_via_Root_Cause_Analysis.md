# 代码中潜藏的安全漏洞，可通过根本原因分析实现自动化防御。

发布时间：2024年08月30日

`LLM应用` `软件开发` `网络安全`

> Unintentional Security Flaws in Code: Automated Defense via Root Cause Analysis

# 摘要

> 软件安全问题依然严峻，尤其是初级开发人员因缺乏全面的安全知识而参与代码编写时。尽管有工具辅助编写安全代码，但其修复漏洞的实际效果尚未明确。现有方法多聚焦于漏洞的分类与定位，却未明确指出问题根源代码段，这对开发者修复漏洞至关重要。为此，我们开展了一项研究，评估现有方法在帮助初级开发者确保代码安全方面的有效性。研究发现，当前工具仅能提升36.2%的代码安全性。问卷调查显示，开发者面临的主要难题之一是不清楚漏洞根源代码。基于此，我们开发了T5-RCGCN工具包，结合T5语言模型与图卷积网络进行漏洞分类与定位，并利用DeepLiftSHAP识别根源代码段。在三个数据集上对56名初级开发者进行测试，结果显示代码安全性提升了28.9%，且开发者对漏洞根源的理解加深，独立确保代码安全的能力提高了17.0%。这表明该工具不仅能在短期内提升安全性，还能促进开发者技能的长期成长。

> Software security remains a critical concern, particularly as junior developers, often lacking comprehensive knowledge of security practices, contribute to codebases. While there are tools to help developers proactively write secure code, their actual effectiveness in helping developers fix their vulnerable code remains largely unmeasured. Moreover, these approaches typically focus on classifying and localizing vulnerabilities without highlighting the specific code segments that are the root cause of the issues, a crucial aspect for developers seeking to fix their vulnerable code. To address these challenges, we conducted a comprehensive study evaluating the efficacy of existing methods in helping junior developers secure their code. Our findings across five types of security vulnerabilities revealed that current tools enabled developers to secure only 36.2\% of vulnerable code. Questionnaire results from these participants further indicated that not knowing the code that was the root cause of the vulnerability was one of their primary challenges in repairing the vulnerable code. Informed by these insights, we developed an automated vulnerability root cause (RC) toolkit called T5-RCGCN, that combines T5 language model embeddings with a graph convolutional network (GCN) for vulnerability classification and localization. Additionally, we integrated DeepLiftSHAP to identify the code segments that were the root cause of the vulnerability. We tested T5-RCGCN with 56 junior developers across three datasets, showing a 28.9\% improvement in code security compared to previous methods. Developers using the tool also gained a deeper understanding of vulnerability root causes, resulting in a 17.0\% improvement in their ability to secure code independently. These results demonstrate the tool's potential for both immediate security enhancement and long-term developer skill growth.

[Arxiv](https://arxiv.org/abs/2409.00199)