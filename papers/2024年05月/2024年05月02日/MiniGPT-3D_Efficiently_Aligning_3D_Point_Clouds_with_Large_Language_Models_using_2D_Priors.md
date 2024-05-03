# MiniGPT-3D：借助2D先验，高效实现3D点云与大型语言模型的精准对齐。

发布时间：2024年05月02日

`LLM应用` `计算机视觉`

> MiniGPT-3D: Efficiently Aligning 3D Point Clouds with Large Language Models using 2D Priors

# 摘要

> 大型2D视觉-语言模型（2D-LLMs）通过巧妙的投影技术，成功地将图像与语言模型相结合，引起了广泛关注。继此之后，大型3D点云-语言模型（3D-LLMs）也致力于将点云数据融入语言模型之中。但是，要实现点云与语言模型的直接对齐，往往需要高昂的训练成本，这在A100上通常需要数百个GPU小时，极大地限制了3D-LLMs的发展。本文提出了MiniGPT-3D，这是一款既高效又强大的3D-LLM，仅需在单个RTX 3090上训练27小时，便能取得多项最新技术水平（SOTA）的成果。具体而言，我们创新性地利用2D-LLMs的2D先验知识来辅助3D点云与LLMs的对齐，充分发挥了2D与3D视觉信息的相似性优势。我们设计了一种新颖的四阶段级联训练策略，用于模态对齐，并引入了一个混合查询专家模块，以高效地适应性聚合特征。同时，我们还采用了参数高效的微调技术LoRA和Norm微调，仅用4700万个可学习参数，相比现有方法减少了高达260倍。广泛的实验结果证明，MiniGPT-3D在3D对象分类和字幕生成任务上均达到了最新技术水平，且训练成本显著降低。特别值得一提的是，MiniGPT-3D在GPT-4评估中的对象字幕生成任务上，比ShapeLLM-13B高出8.12分，而后者在8个A800上的训练成本高达160个GPU小时。我们首次探索了高效的3D-LLM，为该领域带来了新的洞见。相关代码和权重已在 https://github.com/TangYuan96/MiniGPT-3D 上发布。

> Large 2D vision-language models (2D-LLMs) have gained significant attention by bridging Large Language Models (LLMs) with images using a simple projector. Inspired by their success, large 3D point cloud-language models (3D-LLMs) also integrate point clouds into LLMs. However, directly aligning point clouds with LLM requires expensive training costs, typically in hundreds of GPU-hours on A100, which hinders the development of 3D-LLMs. In this paper, we introduce MiniGPT-3D, an efficient and powerful 3D-LLM that achieves multiple SOTA results while training for only 27 hours on one RTX 3090. Specifically, we propose to align 3D point clouds with LLMs using 2D priors from 2D-LLMs, which can leverage the similarity between 2D and 3D visual information. We introduce a novel four-stage training strategy for modality alignment in a cascaded way, and a mixture of query experts module to adaptively aggregate features with high efficiency. Moreover, we utilize parameter-efficient fine-tuning methods LoRA and Norm fine-tuning, resulting in only 47.8M learnable parameters, which is up to 260x fewer than existing methods. Extensive experiments show that MiniGPT-3D achieves SOTA on 3D object classification and captioning tasks, with significantly cheaper training costs. Notably, MiniGPT-3D gains an 8.12 increase on GPT-4 evaluation score for the challenging object captioning task compared to ShapeLLM-13B, while the latter costs 160 total GPU-hours on 8 A800. We are the first to explore the efficient 3D-LLM, offering new insights to the community. Code and weights are available at https://github.com/TangYuan96/MiniGPT-3D.

[Arxiv](https://arxiv.org/abs/2405.01413)