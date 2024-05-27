# SOAP：自我优化提升生成代码效率

发布时间：2024年05月23日

`LLM应用

理由：这篇论文介绍了一个名为SOAP的自优化框架，该框架专门用于提高大型语言模型（LLMs）生成的代码的效率。它通过记录和分析代码的执行时间和内存使用情况，然后反馈给LLM以指导其优化代码。这种方法直接应用于LLM的输出，即生成的代码，以改善其性能，因此属于LLM应用类别。论文中提到的测试和结果展示了对LLM生成代码效率的具体改进，进一步证实了这一点。` `软件开发` `人工智能`

> SOAP: Enhancing Efficiency of Generated Code via Self-Optimization

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了显著成就，但生成的代码往往效率不高，导致执行缓慢且内存消耗大。为此，我们开发了基于执行开销概况的自优化框架（SOAP），旨在提升LLM生成代码的效率。SOAP首先利用LLM生成代码，随后在本地运行以记录执行时间和内存使用情况。这些数据反馈给LLM，指导其优化代码以降低开销。我们在EffiBench、HumanEval和MBPP上对16个开源及6个闭源模型进行了详尽测试，结果显示，通过迭代自优化，SOAP大幅提升了LLM生成代码的效率。例如，StarCoder2-15B在EffiBench上的执行时间从0.93秒锐减至0.12秒，执行时间需求降低了87.1%；总内存使用量也从22.02Mb*s降至2.03Mb*s，执行过程中的内存消耗减少了90.8%。SOAP的源代码已公开于https://github.com/huangd1999/SOAP。

> Large language models (LLMs) have shown remarkable progress in code generation, but their generated code often suffers from inefficiency, resulting in longer execution times and higher memory consumption. To address this issue, we propose Self Optimization based on OverheAd Profile (SOAP), a self-optimization framework that utilizes execution overhead profiles to improve the efficiency of LLM-generated code. SOAP first generates code using an LLM, then executes it locally to capture execution time and memory usage profiles. These profiles are fed back to the LLM, which then revises the code to reduce overhead. To evaluate the effectiveness of SOAP, we conduct extensive experiments on the EffiBench, HumanEval, and MBPP with 16 open-source and 6 closed-source models. Our evaluation results demonstrate that through iterative self-optimization, SOAP significantly enhances the efficiency of LLM-generated code. For example, the execution time (ET) of StarCoder2-15B for the EffiBench decreases from 0.93 (s) to 0.12 (s) which reduces 87.1% execution time requirement compared with the initial code. The total memory usage (TMU) of StarCoder2-15B also decreases from 22.02 (Mb*s) to 2.03 (Mb*s), which decreases 90.8% total memory consumption during the execution process. The source code of SOAP was released in https://github.com/huangd1999/SOAP.

[Arxiv](https://arxiv.org/abs/2405.15189)