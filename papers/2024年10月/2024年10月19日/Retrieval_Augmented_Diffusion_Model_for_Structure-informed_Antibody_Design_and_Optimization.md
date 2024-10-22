# 结构指导抗体设计与优化的检索增强扩散模型

发布时间：2024年10月19日

`其他` `生物医药` `蛋白质工程`

> Retrieval Augmented Diffusion Model for Structure-informed Antibody Design and Optimization

# 摘要

> 抗体作为生物免疫系统的关键蛋白，能精准识别病原体抗原。生成模型的进步虽提升了抗体设计，但现有方法多无模板约束，导致优化难题与不自然序列。为此，我们提出RADAb框架，利用结构同源模体，指导模型逆向优化抗体。通过结构感知检索与双分支去噪模块，结合结构与进化信息，实现高效设计。条件扩散模型则通过全局与局部条件，迭代优化。实证显示，RADAb在抗体逆折叠与优化任务中表现卓越，为生物分子生成模型开辟新视野。

> Antibodies are essential proteins responsible for immune responses in organisms, capable of specifically recognizing antigen molecules of pathogens. Recent advances in generative models have significantly enhanced rational antibody design. However, existing methods mainly create antibodies from scratch without template constraints, leading to model optimization challenges and unnatural sequences. To address these issues, we propose a retrieval-augmented diffusion framework, termed RADAb, for efficient antibody design. Our method leverages a set of structural homologous motifs that align with query structural constraints to guide the generative model in inversely optimizing antibodies according to desired design criteria. Specifically, we introduce a structure-informed retrieval mechanism that integrates these exemplar motifs with the input backbone through a novel dual-branch denoising module, utilizing both structural and evolutionary information. Additionally, we develop a conditional diffusion model that iteratively refines the optimization process by incorporating both global context and local evolutionary conditions. Our approach is agnostic to the choice of generative models. Empirical experiments demonstrate that our method achieves state-of-the-art performance in multiple antibody inverse folding and optimization tasks, offering a new perspective on biomolecular generative models.

[Arxiv](https://arxiv.org/abs/2410.15040)