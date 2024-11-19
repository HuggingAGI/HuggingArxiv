# 一项有关基于 LLM 的自动错误修复代理的实证探究

发布时间：2024年11月15日

`Agent` `漏洞修复`

> An Empirical Study on LLM-based Agents for Automated Bug Fixing

# 摘要

> 大型语言模型（LLMs）和基于 LLM 的智能体已能自动修复漏洞，它们通过与开发环境互动、迭代验证及代码修改，展现出处理软件缺陷的能力。不过，对于这些智能体和非智能体系统的系统性分析仍很有限，尤其是在顶尖系统的性能差异方面。本文中，我们在 SWE-bench Lite 基准上对七个专有及开源系统的自动漏洞修复进行了研究。首先，我们评估了每个系统的整体表现，记录了所有系统都能或都不能解决的情况，并探究了为何某些情况只有特定类型的系统能解决。我们还对比了文件和行级别的故障定位精准度，评估了漏洞重现能力，确定了只有通过动态重现才能解决的情况。经分析，我们认为，无论是 LLM 本身还是智能体流程的设计，都需要进一步优化，以增强智能体在漏洞修复中的成效。

> Large language models (LLMs) and LLM-based Agents have been applied to fix bugs automatically, demonstrating the capability in addressing software defects by engaging in development environment interaction, iterative validation and code modification. However, systematic analysis of these agent and non-agent systems remain limited, particularly regarding performance variations among top-performing ones. In this paper, we examine seven proprietary and open-source systems on the SWE-bench Lite benchmark for automated bug fixing. We first assess each system's overall performance, noting instances solvable by all or none of these sytems, and explore why some instances are uniquely solved by specific system types. We also compare fault localization accuracy at file and line levels and evaluate bug reproduction capabilities, identifying instances solvable only through dynamic reproduction. Through analysis, we concluded that further optimization is needed in both the LLM itself and the design of Agentic flow to improve the effectiveness of the Agent in bug fixing.

[Arxiv](https://arxiv.org/abs/2411.10213)