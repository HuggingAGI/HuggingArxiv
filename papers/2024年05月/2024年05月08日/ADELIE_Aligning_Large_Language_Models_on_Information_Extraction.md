# ADELIE：大型语言模型在信息抽取领域的精准对齐在翻译过程中，我首先确保原文的核心意义被准确传达，即“ADELIE”是一个关于大型语言模型在信息抽取任务上进行对齐的项目或方法。然后，我调整了语言表达，使其更加符合中文的表达习惯，同时保持了原文的专业性和简洁性。

发布时间：2024年05月08日

`Agent

这篇论文介绍了一个专门为信息提取任务设计的Agent，名为ADELIE。它通过构建IEInstruct对齐语料库和采用特定的训练方法（如指令调整和DPO优化目标）来提高模型在信息提取任务上的性能。论文强调了ADELIE在开源领域的领先地位，并承诺公开源码、数据和模型以促进研究。因此，这篇论文更符合Agent分类，因为它描述了一个特定任务的智能代理系统。` `信息提取`

> ADELIE: Aligning Large Language Models on Information Extraction

# 摘要

> 大型语言模型在信息提取任务上往往力不从心，难以应对复杂的指令。这源于主流的对齐数据集忽视了IE数据，导致模型与人类意图脱节。本文推出的ADELIE，专为信息提取任务量身定制，能灵活应对封闭、开放及按需IE挑战。我们精心打造了IEInstruct对齐语料库，并通过指令调整训练出ADELIE_SFT。随后，采用DPO优化目标，锻造出ADELIE_DPO。实验证明，ADELIE系列模型在开源领域独领风骚，不仅性能卓越，通用能力亦未见衰退。我们愿公开源码、数据与模型，以期推动研究的深入发展。

> Large language models (LLMs) usually fall short on information extraction (IE) tasks and struggle to follow the complex instructions of IE tasks. This primarily arises from LLMs not being aligned with humans, as mainstream alignment datasets typically do not include IE data. In this paper, we introduce ADELIE (Aligning large language moDELs on Information Extraction), an aligned LLM that effectively solves various IE tasks, including closed IE, open IE, and on-demand IE. We first collect and construct a high-quality alignment corpus IEInstruct for IE. Then we train ADELIE_SFT using instruction tuning on IEInstruct. We further train ADELIE_SFT with direct preference optimization (DPO) objective, resulting in ADELIE_DPO. Extensive experiments on various held-out IE datasets demonstrate that our models (ADELIE_SFT and ADELIE_DPO) achieve state-of-the-art (SoTA) performance among open-source models. We further explore the general capabilities of ADELIE, and experimental results reveal that their general capabilities do not exhibit a noticeable decline. We will release the code, data, and models to facilitate further research.

[Arxiv](https://arxiv.org/abs/2405.05008)