# SparseInfer：无需训练就能预测激活稀疏性，从而实现 LLM 的快速推理

发布时间：2024年11月19日

`LLM应用` `语言模型` `推理优化`

> SparseInfer: Training-free Prediction of Activation Sparsity for Fast LLM Inference

# 摘要

> 利用稀疏性对于优化大型语言模型的推理极为关键。然而，当下的LLM使用SiLU作为激活函数，其激活稀疏性微乎其微。近期研究提议用ReLU取代SiLU以产生显著的激活稀疏性，且通过微调表明下游任务的准确率未降低。但要充分利用这一点，需要训练一个预测器来估算这种稀疏性。在本文中，我们推出了SparseInfer，这是一个针对ReLU域LLM激活稀疏性的简单、轻量且无需训练的预测器，它仅通过对比输入和权重的符号位来预测激活稀疏性。为弥补可能的预测不精准，启用了预测器保守性的自适应调节，这也能作为优化LLM推理的控制把手。所提方法相比现有技术，推理速度大幅提升，准确率损失可忽略不计，在1%p以内。

> Leveraging sparsity is crucial for optimizing large language model inference. however, modern LLMs employing SiLU as their activation function exhibit minimal activation sparsity. Recent research has proposed replacing SiLU with ReLU to induce significant activation sparsity and showed no downstream task accuracy degradation through fine tuning. However, taking full advantage of it required training a predictor to estimate this sparsity. In this paper, we introduce SparseInfer, a simple, light weight, and training free predictor for activation sparsity of ReLU field LLMs, in which activation sparsity is predicted by comparing only the sign bits of inputs and weights. To compensate for possible prediction inaccuracy, an adaptive tuning of the predictor's conservativeness is enabled, which can also serve as a control knob for optimizing LLM inference. The proposed method achieves approximately faster inference speed over the state of the art, with negligible accuracy loss of within 1%p.

[Arxiv](https://arxiv.org/abs/2411.12692)