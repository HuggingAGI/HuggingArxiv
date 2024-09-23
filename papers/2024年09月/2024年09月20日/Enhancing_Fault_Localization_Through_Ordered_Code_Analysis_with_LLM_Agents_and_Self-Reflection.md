# 利用 LLM 代理和自我反思进行有序代码分析，提升故障定位的精准度

发布时间：2024年09月20日

`LLM应用` `软件开发` `故障修复`

> Enhancing Fault Localization Through Ordered Code Analysis with LLM Agents and Self-Reflection

# 摘要

> 在软件开发中，定位和修复故障既耗时又费力。传统方法如SBFL依赖统计分析，但准确性有限。基于学习的技术虽更有效，却需大量数据且计算成本高。LLM通过增强代码理解和推理，在故障定位上展现出潜力，但仍面临令牌限制、长输入性能下降及管理复杂系统项目的挑战。为此，我们提出LLM4FL，一种结合SBFL与分治策略的新方法。通过分割数据并使用多个LLM代理进行提示链操作，LLM4FL更高效地定位故障。该方法还融入自我反思和思维链推理，使代理能迭代修复并重新排名可疑方法。我们在Defects4J基准上测试LLM4FL，结果显示其在Top-1准确性上比AutoFL高出19.27%，并超越了DeepFL和Grace等最先进技术，且无需特定任务训练。此外，我们发现覆盖分割和提示链对性能有显著影响，不同方法排序可将Top-1准确性提升多达22%。

> Locating and fixing software faults is a time-consuming and resource-intensive task in software development. Traditional fault localization methods, such as Spectrum-Based Fault Localization (SBFL), rely on statistical analysis of test coverage data but often suffer from lower accuracy. Learning-based techniques, while more effective, require extensive training data and can be computationally expensive. Recent advancements in Large Language Models (LLMs) offer promising improvements in fault localization by enhancing code comprehension and reasoning. However, these LLM-based techniques still face challenges, including token limitations, degraded performance with long inputs, and difficulties managing large-scale projects with complex systems involving multiple interacting components. To address these issues, we introduce LLM4FL, a novel LLM-agent-based fault localization approach that integrates SBFL rankings with a divide-and-conquer strategy. By dividing large coverage data into manageable groups and employing multiple LLM agents through prompt chaining, LLM4FL navigates the codebase and localizes faults more effectively. The approach also incorporates self-reflection and chain-of-thought reasoning, enabling agents to iteratively generate fixes and re-rank suspicious methods. We evaluated LLM4FL on the Defects4J (V2.0.0) benchmark, comprising 675 real-world faults from 14 open-source Java projects. Our results demonstrate that LLM4FL outperforms AutoFL by 19.27% in Top-1 accuracy and surpasses state-of-the-art supervised techniques such as DeepFL and Grace, all without task-specific training. Additionally, we highlight the impact of coverage splitting and prompt chaining on fault localization performance and show that different method ordering can improve Top-1 accuracy by up to 22%.

[Arxiv](https://arxiv.org/abs/2409.13642)