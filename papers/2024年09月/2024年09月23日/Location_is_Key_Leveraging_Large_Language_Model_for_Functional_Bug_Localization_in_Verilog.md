# 位置至关重要：借助大型语言模型，精准定位 Verilog 中的功能性错误。

发布时间：2024年09月23日

`LLM应用` `电子工程` `硬件设计`

> Location is Key: Leveraging Large Language Model for Functional Bug Localization in Verilog

# 摘要

> 在硬件设计验证中，Verilog代码的错误定位既关键又耗时。尽管大型语言模型（LLMs）展现了强大的编程能力，但尚未有研究探索其在Verilog错误定位中的应用。本文推出的Location-is-Key，是一个开源的LLM解决方案，专门用于定位Verilog代码中的功能错误。LiK在定位准确率上表现出色，测试数据集上的pass@1准确率达到93.3%，超越了GPT-4的77.9%，与Claude-3.5的90.8%不相上下。更重要的是，LiK的错误定位显著提升了GPT-3.5的修复效率，功能pass@1从40.39%跃升至58.92%，凸显了错误定位在LLM辅助Verilog调试中的关键作用。与传统方法不同，LiK仅需设计规范和错误代码片段，无需复杂的测试平台或EDA工具。这一研究不仅验证了LLMs在Verilog错误定位中的可行性，也为自动Verilog代码调试开辟了新路径。

> Bug localization in Verilog code is a crucial and time-consuming task during the verification of hardware design. Since introduction, Large Language Models (LLMs) have showed their strong programming capabilities. However, no work has yet considered using LLMs for bug localization in Verilog code. This paper presents Location-is-Key, an opensource LLM solution to locate functional errors in Verilog snippets. LiK achieves high localization accuracy, with a pass@1 localization accuracy of 93.3% on our test dataset based on RTLLM, surpassing GPT-4's 77.9% and comparable to Claude-3.5's 90.8%. Additionally, the bug location obtained by LiK significantly improves GPT-3.5's bug repair efficiency (Functional pass@1 increased from 40.39% to 58.92%), highlighting the importance of bug localization in LLM-based Verilog debugging. Compared to existing methods, LiK only requires the design specification and the erroneous code snippet, without the need for testbenches, assertions, or any other EDA tools. This research demonstrates the feasibility of using LLMs for Verilog error localization, thus providing a new direction for automatic Verilog code debugging.

[Arxiv](https://arxiv.org/abs/2409.15186)