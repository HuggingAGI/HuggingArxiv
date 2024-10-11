# RealVul: LLM 能否助力我们发现 Web 应用中的漏洞？

发布时间：2024年10月09日

`LLM应用` `软件开发` `网络安全`

> RealVul: Can We Detect Vulnerabilities in Web Applications with LLM?

# 摘要

> 大型语言模型 (LLM) 的最新进展激发了其在软件漏洞检测中的潜力。然而，针对 PHP 语言漏洞的研究尚显不足，样本提取与处理的难题也制约了模型捕捉特定漏洞特征的能力。为此，我们推出了 RealVul，首个专为 PHP 漏洞检测设计的 LLM 框架。通过引入漏洞候选检测方法及规范化等技术，RealVul 能精简代码、剔除冗余信息，同时精准定位潜在漏洞触发点，助力模型深入学习漏洞样本。此外，我们还通过优化数据合成方法，弥补了 PHP 漏洞样本的不足。为验证 RealVul 的性能，我们采用五个不同代码 LLM 对 180 个 PHP 项目的漏洞数据进行了全面分析。结果显示，RealVul 在有效性和泛化能力上均显著超越现有方法，大幅提升了模型的漏洞检测能力。

> The latest advancements in large language models (LLMs) have sparked interest in their potential for software vulnerability detection. However, there is currently a lack of research specifically focused on vulnerabilities in the PHP language, and challenges in extracting samples and processing persist, hindering the model's ability to effectively capture the characteristics of specific vulnerabilities. In this paper, we present RealVul, the first LLM-based framework designed for PHP vulnerability detection, addressing these issues. By vulnerability candidate detection methods and employing techniques such as normalization, we can isolate potential vulnerability triggers while streamlining the code and eliminating unnecessary semantic information, enabling the model to better understand and learn from the generated vulnerability samples. We also address the issue of insufficient PHP vulnerability samples by improving data synthesis methods. To evaluate RealVul's performance, we conduct an extensive analysis using five distinct code LLMs on vulnerability data from 180 PHP projects. The results demonstrate a significant improvement in both effectiveness and generalization compared to existing methods, effectively boosting the vulnerability detection capabilities of these models.

[Arxiv](https://arxiv.org/abs/2410.07573)