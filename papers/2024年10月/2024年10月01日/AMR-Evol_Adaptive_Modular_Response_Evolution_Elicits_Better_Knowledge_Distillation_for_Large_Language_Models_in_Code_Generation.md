# AMR-Evol：通过自适应模块化响应进化，为大型语言模型在代码生成中实现更优的知识蒸馏。

发布时间：2024年10月01日

`LLM应用` `软件开发` `人工智能`

> AMR-Evol: Adaptive Modular Response Evolution Elicits Better Knowledge Distillation for Large Language Models in Code Generation

# 摘要

> GPT4 等专有大型语言模型在代码生成中的卓越表现，促使业界尝试通过知识蒸馏（如 Code Evol-Instruct）在开源模型中复制这些能力。然而，这些尝试往往忽视了响应质量，过度依赖教师模型进行直接响应蒸馏。这种做法在处理复杂指令时，可能导致合成数据质量下降，影响知识蒸馏效果。为此，我们提出了自适应模块化响应进化（AMR-Evol）框架，通过两阶段过程优化响应蒸馏。首先，模块化分解将直接响应拆解为更易管理的子模块；接着，自适应响应进化自动与相关功能模块协同进化响应。实验结果显示，AMR-Evol 框架在 HumanEval、MBPP 和 EvalPlus 等基准测试中表现优异，显著超越基线方法。与同等规模数据训练的开源代码 LLM 相比，AMR-Evol 在 HumanEval-Plus 和 MBPP-Plus 上的性能分别提升了 +3.0 分和 +1.0 分，充分证明了其有效性。代码已开源，详见 https://github.com/ChiYeungLaw/AMR-Evol。

> The impressive performance of proprietary LLMs like GPT4 in code generation has led to a trend to replicate these capabilities in open-source models through knowledge distillation (e.g. Code Evol-Instruct). However, these efforts often neglect the crucial aspect of response quality, relying heavily on teacher models for direct response distillation. This paradigm, especially for complex instructions, can degrade the quality of synthesized data, compromising the knowledge distillation process. To this end, our study introduces the Adaptive Modular Response Evolution (AMR-Evol) framework, which employs a two-stage process to refine response distillation. The first stage, modular decomposition, breaks down the direct response into more manageable sub-modules. The second stage, adaptive response evolution, automatically evolves the response with the related function modules. Our experiments with three popular code benchmarks (HumanEval, MBPP, and EvalPlus) attest to the superiority of the AMR-Evol framework over baseline response distillation methods. By comparing with the open-source Code LLMs trained on a similar scale of data, we observed performance enhancements: more than +3.0 points on HumanEval-Plus and +1.0 points on MBPP-Plus, which underscores the effectiveness of our framework. Our codes are available at https://github.com/ChiYeungLaw/AMR-Evol.

[Arxiv](https://arxiv.org/abs/2410.00558)