# 借助影响函数剖析多模态大型语言模型的失准情况

发布时间：2024年11月18日

`LLM应用` `多模态` `语言模型`

> Dissecting Misalignment of Multimodal Large Language Models via Influence Function

# 摘要

> 多模态大型语言模型（MLLMs）常以来源多样且不可靠的数据进行训练，其中可能存在未对齐或错标了的文本-图像对，这往往引发鲁棒性问题和幻觉，致使性能降低。数据估值是检测和追踪这些未对齐情况的有效手段。不过，现有的方法用于 MLLMs 时计算成本颇高。经典的影响函数虽计算效率高，但不适用于对比学习模型，因其最初是为逐点损失设计的。此外，对比学习要最小化正样本模态间的距离，最大化负样本模态间的距离，这就需要我们从两个角度评估样本的影响。为应对这些挑战，我们推出了用于对比损失的扩展影响函数（ECIF），这是专门为对比损失打造的影响函数。ECIF 兼顾正样本和负样本，还提供了对比学习模型的闭式近似，无需重新训练。基于 ECIF，我们研发了一系列用于 MLLM 中的数据评估、未对齐检测和错误预测回溯任务的算法。实验结果显示，与传统基线方法相比，我们的 ECIF 能更精准地评估数据影响和模型对齐，从而提升了 MLLMs 的透明度和可解释性。

> Multi-modal Large Language models (MLLMs) are always trained on data from diverse and unreliable sources, which may contain misaligned or mislabeled text-image pairs. This frequently causes robustness issues and hallucinations, leading to performance degradation. Data valuation is an efficient way to detect and trace these misalignments. Nevertheless, existing methods are computationally expensive for MLLMs. While computationally efficient, the classical influence functions are inadequate for contrastive learning models because they were originally designed for pointwise loss. Additionally, contrastive learning involves minimizing the distance between the modalities of positive samples and maximizing the distance between the modalities of negative samples. This requires us to evaluate the influence of samples from both perspectives. To tackle these challenges, we introduce the Extended Influence Function for Contrastive Loss (ECIF), an influence function crafted for contrastive loss. ECIF considers both positive and negative samples and provides a closed-form approximation of contrastive learning models, eliminating the need for retraining. Building upon ECIF, we develop a series of algorithms for data evaluation in MLLM, misalignment detection, and misprediction trace-back tasks. Experimental results demonstrate our ECIF advances the transparency and interpretability of MLLMs by offering a more accurate assessment of data impact and model alignment compared to traditional baseline methods.

[Arxiv](https://arxiv.org/abs/2411.11667)