# PIDformer：Transformer 遇见控制理论

发布时间：2024年02月25日

`LLM理论` `计算机视觉`

> PIDformer: Transformer Meets Control Theory

# 摘要

> 摘要：在这项工作中，我们解决了变压器架构的两个主要缺点：输入损坏和输出表示中的秩崩溃。我们揭示了自注意力作为一种自主状态空间模型，其本质上促进了其解决方案的平滑性，导致较低秩的输出和表示能力的减弱。此外，模型的稳态解对输入扰动敏感。我们将带有参考点的比例-积分-微分（PID）闭环反馈控制系统纳入模型，以提高鲁棒性和表示能力。这种集成旨在保留高频细节，同时增强模型稳定性，使其更具抗噪声能力。所得的受控状态空间模型在理论上被证明是鲁棒的，并且善于解决秩崩溃问题。受此控制框架的启发，我们推导出了一类新型的变压器，即 PID 控制的变压器（PIDformer），旨在提高鲁棒性并减轻 softmax 变压器固有的秩崩溃问题。我们通过实验评估了该模型在各种实际任务（包括对象分类、图像分割和语言建模）中相对于基线变压器的优势和鲁棒性。

> 
Abstract:In this work, we address two main shortcomings of transformer architectures: input corruption and rank collapse in their output representation. We unveil self-attention as an autonomous state-space model that inherently promotes smoothness in its solutions, leading to lower-rank outputs and diminished representation capacity. Moreover, the steady-state solution of the model is sensitive to input perturbations. We incorporate a Proportional-Integral-Derivative (PID) closed-loop feedback control system with a reference point into the model to improve robustness and representation capacity. This integration aims to preserve high-frequency details while bolstering model stability, rendering it more noise-resilient. The resulting controlled state-space model is theoretically proven robust and adept at addressing the rank collapse. Motivated by this control framework, we derive a novel class of transformers, PID-controlled Transformer (PIDformer), aimed at improving robustness and mitigating the rank-collapse issue inherent in softmax transformers. We empirically evaluate the model for advantages and robustness against baseline transformers across various practical tasks, including object classification, image segmentation, and language modeling.
    

[Arxiv](https://arxiv.org/pdf/2402.15989)