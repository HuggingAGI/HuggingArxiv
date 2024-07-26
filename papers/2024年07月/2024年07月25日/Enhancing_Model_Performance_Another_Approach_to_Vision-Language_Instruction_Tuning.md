# 提升模型性能：探索视觉与语言指令调优的新途径

发布时间：2024年07月25日

`LLM应用` `人工智能` `计算机视觉`

> Enhancing Model Performance: Another Approach to Vision-Language Instruction Tuning

# 摘要

> 大型语言模型与视觉-语言任务的融合，标志着人工智能领域的一次重大飞跃，展现了 LLM 作为多才多艺的通用聊天机器人的广阔前景。当前的研究趋势着重于视觉与语言的深度融合，旨在打造能适应更复杂现实场景的模型。我们创新性地提出了“瓶颈适配器”方法，专为提升这些复杂模型的多模态能力而设计，通过“多模态模型调优”实现整个框架的协同优化。该方法通过轻量级适配器，巧妙连接图像编码器与 LLM，避免了庞大神经网络的复杂性。与传统模块化训练不同，我们采用端到端优化策略，结合适配器，以更精简的参数集实现高效联合优化。实验结果显示，我们的方法以 90.12\% 的准确率，超越了人类表现（88.4\%）及 LaVIN-7B（89.41\%），展现出卓越性能。

> The integration of large language models (LLMs) with vision-language (VL) tasks has been a transformative development in the realm of artificial intelligence, highlighting the potential of LLMs as a versatile general-purpose chatbot. However, the current trend in this evolution focuses on the integration of vision and language to create models that can operate in more diverse and real-world contexts. We present a novel approach, termed Bottleneck Adapter, specifically crafted for enhancing the multimodal functionalities of these complex models, enabling joint optimization of the entire multimodal LLM framework through a process known as Multimodal Model Tuning (MMT). Our approach utilizes lightweight adapters to connect the image encoder and LLM without the need for large, complex neural networks. Unlike the conventional modular training schemes, our approach adopts an end-to-end optimization regime, which, when combined with the adapters, facilitates the joint optimization using a significantly smaller parameter set. Our method exhibits robust performance with 90.12\% accuracy, outperforming both human-level performance (88.4\%) and LaVIN-7B (89.41\%).

[Arxiv](https://arxiv.org/abs/2407.17813)