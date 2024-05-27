# SOAP：借助自我优化，提升生成代码的效率

发布时间：2024年05月23日

`LLM应用

理由：这篇论文介绍了一种名为SOAP的自我优化框架，该框架专门用于提升大型语言模型（LLMs）生成的代码的效率。它通过分析执行开销概况来调整和优化代码，从而减少执行时间和内存消耗。这种应用直接针对LLM在代码生成领域的实际问题，并通过技术手段进行改进，属于LLM的具体应用案例。因此，它被归类为LLM应用。` `软件开发` `人工智能`

> SOAP: Enhancing Efficiency of Generated Code via Self-Optimization

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了显著成就，但其生成的代码往往效率不高，导致执行时间延长和内存消耗增加。为此，我们开发了一种名为SOAP的自我优化框架，它通过分析执行开销概况来提升LLM生成代码的效率。SOAP首先利用LLM生成代码，随后在本地运行以记录执行时间和内存使用情况。这些数据被反馈给LLM，以便其调整代码以降低开销。我们在EffiBench、HumanEval和MBPP上对16个开源模型和6个闭源模型进行了详尽测试，结果显示，通过持续的自我优化，SOAP大幅提升了LLM生成代码的效率。例如，StarCoder2-15B在EffiBench上的执行时间从0.93秒锐减至0.12秒，执行时间需求降低了87.1%。同时，StarCoder2-15B的总内存使用量也从22.02Mb*s大幅降至2.03Mb*s，执行过程中的内存消耗减少了90.8%。SOAP的源代码已公开发布于https://github.com/huangd1999/SOAP。

> Large language models (LLMs) have shown remarkable progress in code generation, but their generated code often suffers from inefficiency, resulting in longer execution times and higher memory consumption. To address this issue, we propose Self Optimization based on OverheAd Profile (SOAP), a self-optimization framework that utilizes execution overhead profiles to improve the efficiency of LLM-generated code. SOAP first generates code using an LLM, then executes it locally to capture execution time and memory usage profiles. These profiles are fed back to the LLM, which then revises the code to reduce overhead. To evaluate the effectiveness of SOAP, we conduct extensive experiments on the EffiBench, HumanEval, and MBPP with 16 open-source and 6 closed-source models. Our evaluation results demonstrate that through iterative self-optimization, SOAP significantly enhances the efficiency of LLM-generated code. For example, the execution time (ET) of StarCoder2-15B for the EffiBench decreases from 0.93 (s) to 0.12 (s) which reduces 87.1% execution time requirement compared with the initial code. The total memory usage (TMU) of StarCoder2-15B also decreases from 22.02 (Mb*s) to 2.03 (Mb*s), which decreases 90.8% total memory consumption during the execution process. The source code of SOAP was released in https://github.com/huangd1999/SOAP.

[Arxiv](https://arxiv.org/abs/2405.15189)