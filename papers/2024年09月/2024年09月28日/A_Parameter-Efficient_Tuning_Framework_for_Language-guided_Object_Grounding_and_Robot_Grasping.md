# 一种参数高效的调优框架，专为语言引导的对象定位和机器人抓取设计

发布时间：2024年09月28日

`Agent` `机器人` `计算机视觉`

> A Parameter-Efficient Tuning Framework for Language-guided Object Grounding and Robot Grasping

# 摘要

> 语言引导的机器人抓取任务需要机器人整合视觉和语言的多模态信息，以预测抓取动作。尽管多模态大型语言模型 (MLLM) 的方法显示出潜力，但其高计算和数据需求限制了本地部署。为此，我们提出了一种基于 CLIP 的多模态参数高效调优 (PET) 框架，适用于三种任务：引用表达分割 (RES)、引用抓取合成 (RGS) 和引用抓取可操作性 (RGA)。我们的创新包括双向视觉-语言适配器和深度融合分支，前者对齐多模态输入以实现像素级语言理解，后者结合几何线索以提升抓取预测。实验显示，在 RES 任务中，我们的方法优于现有方法。在 RGS 和 RGA 任务中，模型不仅能有效解释简单语言描述的对象属性，还能处理复杂的空间推理场景，如多个相同对象的存在。

> The language-guided robot grasping task requires a robot agent to integrate multimodal information from both visual and linguistic inputs to predict actions for target-driven grasping. While recent approaches utilizing Multimodal Large Language Models (MLLMs) have shown promising results, their extensive computation and data demands limit the feasibility of local deployment and customization. To address this, we propose a novel CLIP-based multimodal parameter-efficient tuning (PET) framework designed for three language-guided object grounding and grasping tasks: (1) Referring Expression Segmentation (RES), (2) Referring Grasp Synthesis (RGS), and (3) Referring Grasp Affordance (RGA). Our approach introduces two key innovations: a bi-directional vision-language adapter that aligns multimodal inputs for pixel-level language understanding and a depth fusion branch that incorporates geometric cues to facilitate robot grasping predictions. Experiment results demonstrate superior performance in the RES object grounding task compared with existing CLIP-based full-model tuning or PET approaches. In the RGS and RGA tasks, our model not only effectively interprets object attributes based on simple language descriptions but also shows strong potential for comprehending complex spatial reasoning scenarios, such as multiple identical objects present in the workspace.

[Arxiv](https://arxiv.org/abs/2409.19457)