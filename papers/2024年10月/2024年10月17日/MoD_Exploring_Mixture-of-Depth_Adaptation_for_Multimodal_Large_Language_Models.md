# MoD：探索多模态大型语言模型的深度混合适应策略

发布时间：2024年10月17日

`LLM应用` `人工智能` `计算机视觉`

> MoD: Exploring Mixture-of-Depth Adaptation for Multimodal Large Language Models

# 摘要

> 尽管多模态大型语言模型 (MLLM) 取得了显著进展，但其高计算成本仍是实际部署的障碍。受自然语言处理中深度混合 (MoD) 的启发，我们提出了一种创新的 $γ$-MoD 策略，通过“激活令牌”的角度来解决这一问题。$γ$-MoD 引入了一种新的度量标准——注意力图的秩 (ARank)，以指导 MoD 在 MLLM 中的部署，从而有效识别并替换冗余层。此外，我们还提出了两种新颖的设计——共享视觉语言路由器和掩码路由学习，以最大化 MLLM 的计算稀疏性，同时保持其性能。实验结果显示，$γ$-MoD 不仅显著提升了效率，还展现了强大的泛化能力。例如，在仅轻微性能下降（-1.5%）的情况下，$γ$-MoD 可将 LLaVA-HR 的训练和推理时间分别减少 31.0% 和 53.2%。

> Despite the significant progress in multimodal large language models (MLLMs), their high computational cost remains a barrier to real-world deployment. Inspired by the mixture of depths (MoDs) in natural language processing, we aim to address this limitation from the perspective of ``activated tokens''. Our key insight is that if most tokens are redundant for the layer computation, then can be skipped directly via the MoD layer. However, directly converting the dense layers of MLLMs to MoD layers leads to substantial performance degradation. To address this issue, we propose an innovative MoD adaptation strategy for existing MLLMs called $γ$-MoD. In $γ$-MoD, a novel metric is proposed to guide the deployment of MoDs in the MLLM, namely rank of attention maps (ARank). Through ARank, we can effectively identify which layer is redundant and should be replaced with the MoD layer. Based on ARank, we further propose two novel designs to maximize the computational sparsity of MLLM while maintaining its performance, namely shared vision-language router and masked routing learning. With these designs, more than 90% dense layers of the MLLM can be effectively converted to the MoD ones. To validate our method, we apply it to three popular MLLMs, and conduct extensive experiments on 9 benchmark datasets. Experimental results not only validate the significant efficiency benefit of $γ$-MoD to existing MLLMs but also confirm its generalization ability on various MLLMs. For example, with a minor performance drop, i.e., -1.5%, $γ$-MoD can reduce the training and inference time of LLaVA-HR by 31.0% and 53.2%, respectively.

[Arxiv](https://arxiv.org/abs/2410.13859)