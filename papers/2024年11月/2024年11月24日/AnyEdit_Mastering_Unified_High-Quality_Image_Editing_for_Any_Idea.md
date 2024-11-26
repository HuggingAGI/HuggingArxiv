# AnyEdit：精通针对任何构想的统一高品质图像编辑

发布时间：2024年11月24日

`LLM应用` `图像编辑`

> AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea

# 摘要

> 基于指令的图像编辑旨在借助自然语言指令对特定图像元素进行修改。然而，此领域现有的模型往往难以精准执行复杂的用户指令，原因在于它们是基于低质量数据且编辑类型有限进行训练的。我们推出了 AnyEdit，这是一个全面的多模态指令编辑数据集，涵盖 250 万个高质量编辑对，涉及 20 种编辑类型和五个领域。我们从初始数据多样性、自适应编辑过程以及编辑结果的自动选择这三个方面来保证 AnyEdit 数据集的多样性和质量。利用该数据集，我们进一步训练了一个带有任务感知路由和可学习任务嵌入的新型 AnyEdit Stable Diffusion，用于统一图像编辑。在三个基准数据集上进行的综合实验显示，AnyEdit 持续提高了基于扩散的编辑模型的性能。这为开发支持人类创造力的指令驱动图像编辑模型展现了良好前景。

> Instruction-based image editing aims to modify specific image elements with natural language instructions. However, current models in this domain often struggle to accurately execute complex user instructions, as they are trained on low-quality data with limited editing types. We present AnyEdit, a comprehensive multi-modal instruction editing dataset, comprising 2.5 million high-quality editing pairs spanning over 20 editing types and five domains. We ensure the diversity and quality of the AnyEdit collection through three aspects: initial data diversity, adaptive editing process, and automated selection of editing results. Using the dataset, we further train a novel AnyEdit Stable Diffusion with task-aware routing and learnable task embedding for unified image editing. Comprehensive experiments on three benchmark datasets show that AnyEdit consistently boosts the performance of diffusion-based editing models. This presents prospects for developing instruction-driven image editing models that support human creativity.

[Arxiv](https://arxiv.org/abs/2411.15738)