# CreativEval：探究大型语言模型在硬件代码创造中的表现

发布时间：2024年04月12日

`LLM应用` `硬件设计` `创新评估`

> CreativEval: Evaluating Creativity of LLM-Based Hardware Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成上的高效性和有效性使其在硬件设计领域得到广泛应用。现有研究主要关注LLMs在寄存器传输级别代码生成的功能准确性，却忽略了它们在创造性方面的潜力，即生成新颖独特解决方案的能力，这一点由于难以量化而鲜为人知。为了填补这一研究空缺，我们设计了CreativeEval框架，专门用于评估LLMs在硬件设计生成中的创新能力。通过一系列提示和后处理技术，我们对流畅性、灵活性、原创性和详细性这四个创造性维度进行了量化评估。经过对多个知名LLMs（如GPT系列模型、CodeLlama和VeriGen）的评估，数据显示GPT-3.5在硬件设计创新生成方面表现最为突出。

> Large Language Models (LLMs) have proved effective and efficient in generating code, leading to their utilization within the hardware design process. Prior works evaluating LLMs' abilities for register transfer level code generation solely focus on functional correctness. However, the creativity associated with these LLMs, or the ability to generate novel and unique solutions, is a metric not as well understood, in part due to the challenge of quantifying this quality.
  To address this research gap, we present CreativeEval, a framework for evaluating the creativity of LLMs within the context of generating hardware designs. We quantify four creative sub-components, fluency, flexibility, originality, and elaboration, through various prompting and post-processing techniques. We then evaluate multiple popular LLMs (including GPT models, CodeLlama, and VeriGen) upon this creativity metric, with results indicating GPT-3.5 as the most creative model in generating hardware designs.

[Arxiv](https://arxiv.org/abs/2404.08806)