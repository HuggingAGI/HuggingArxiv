# AlignGPT：一款具备自适应对齐功能的多模态大型语言模型，能够灵活适应不同模态间的信息对齐需求。

发布时间：2024年05月22日

`LLM理论

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在对齐能力建模上的改进，特别是在预训练和指令调优阶段如何定制和灵活匹配图像-文本对齐能力。这涉及到对LLM理论的深入研究和改进，因此属于LLM理论分类。论文中提到的AlignGPT的开发和实验结果的展示，虽然具有实际应用的潜力，但其核心贡献在于理论层面的创新和改进，而非直接的应用或Agent的设计。` `人工智能` `多模态学习`

> AlignGPT: Multi-modal Large Language Models with Adaptive Alignment Capability

# 摘要

> 多模态大型语言模型（MLLMs）在探索人工通用智能（AGI）中扮演着关键角色，其核心在于实现跨模态对齐。当前MLLMs采用预训练和指令调优两阶段训练，虽有成效，但在对齐能力建模上仍有缺陷。预训练时，模型误以为所有图像-文本对齐一致，实则不然；指令调优时，不同任务需不同对齐水平，而以往模型未充分考虑这一点。为此，我们推出了AlignGPT，预训练中为不同图像-文本对定制对齐能力，指令调优中灵活匹配，以适应多样化需求。实验证明，AlignGPT在12项基准测试中表现卓越。

> Multimodal Large Language Models (MLLMs) are widely regarded as crucial in the exploration of Artificial General Intelligence (AGI). The core of MLLMs lies in their capability to achieve cross-modal alignment. To attain this goal, current MLLMs typically follow a two-phase training paradigm: the pre-training phase and the instruction-tuning phase. Despite their success, there are shortcomings in the modeling of alignment capabilities within these models. Firstly, during the pre-training phase, the model usually assumes that all image-text pairs are uniformly aligned, but in fact the degree of alignment between different image-text pairs is inconsistent. Secondly, the instructions currently used for finetuning incorporate a variety of tasks, different tasks's instructions usually require different levels of alignment capabilities, but previous MLLMs overlook these differentiated alignment needs. To tackle these issues, we propose a new multimodal large language model AlignGPT. In the pre-training stage, instead of treating all image-text pairs equally, we assign different levels of alignment capabilities to different image-text pairs. Then, in the instruction-tuning phase, we adaptively combine these different levels of alignment capabilities to meet the dynamic alignment needs of different instructions. Extensive experimental results show that our model achieves competitive performance on 12 benchmarks.

[Arxiv](https://arxiv.org/abs/2405.14129)