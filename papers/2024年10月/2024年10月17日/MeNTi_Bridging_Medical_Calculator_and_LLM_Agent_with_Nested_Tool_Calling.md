# MeNTi：连接医疗计算器与 LLM 代理，通过嵌套工具调用实现无缝协作。

发布时间：2024年10月17日

`Agent` `人工智能`

> MeNTi: Bridging Medical Calculator and LLM Agent with Nested Tool Calling

# 摘要

> 将工具融入大型语言模型（LLM）已推动了广泛应用。然而，在专业领域，仅依赖工具无法完全应对现实复杂性，尤其在医学领域。本文聚焦医疗计算器任务，通过标准化测试评估健康状况。我们提出 MeNTi，一种通用代理架构，整合专用医疗工具包，并采用元工具和嵌套调用机制，提升 LLM 工具利用率。MeNTi 灵活选择工具并嵌套调用，解决复杂医疗场景中的实际问题，如计算器选择、槽填充和单位转换。为评估 LLM 在临床过程中的定量评估能力，我们创建了 CalcQA 基准，要求 LLM 使用医疗计算器进行计算和健康评估。CalcQA 由专业医师构建，包含 100 个病例-计算器对和 281 个医疗工具。实验结果表明，我们的框架显著提升了性能，为医学等高要求场景中的 LLM 应用开辟了新方向。

> Integrating tools into Large Language Models (LLMs) has facilitated the widespread application. Despite this, in specialized downstream task contexts, reliance solely on tools is insufficient to fully address the complexities of the real world. This particularly restricts the effective deployment of LLMs in fields such as medicine. In this paper, we focus on the downstream tasks of medical calculators, which use standardized tests to assess an individual's health status. We introduce MeNTi, a universal agent architecture for LLMs. MeNTi integrates a specialized medical toolkit and employs meta-tool and nested calling mechanisms to enhance LLM tool utilization. Specifically, it achieves flexible tool selection and nested tool calling to address practical issues faced in intricate medical scenarios, including calculator selection, slot filling, and unit conversion. To assess the capabilities of LLMs for quantitative assessment throughout the clinical process of calculator scenarios, we introduce CalcQA. This benchmark requires LLMs to use medical calculators to perform calculations and assess patient health status. CalcQA is constructed by professional physicians and includes 100 case-calculator pairs, complemented by a toolkit of 281 medical tools. The experimental results demonstrate significant performance improvements with our framework. This research paves new directions for applying LLMs in demanding scenarios of medicine.

[Arxiv](https://arxiv.org/abs/2410.13610)