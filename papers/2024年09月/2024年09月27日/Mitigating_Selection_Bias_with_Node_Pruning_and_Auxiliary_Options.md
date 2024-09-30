# 采用节点修剪与辅助选项，巧妙化解选择偏差

发布时间：2024年09月27日

`LLM应用` `自动化系统`

> Mitigating Selection Bias with Node Pruning and Auxiliary Options

# 摘要

> 大型语言模型 (LLM) 在回答选择题时，常常偏爱某些选项，这给自动化系统带来了可靠性问题。为解决这一偏差问题，我们不仅研究了模型内部的偏差表示，还提出了两种创新方法：偏差节点剪枝 (BNP) 和辅助选项注入 (AOI)。BNP 通过消除偏差参数来调整模型，而 AOI 则是一种简单有效的输入修改技术，适用于黑箱 LLM。此外，我们引入了选择 Kullback-Leibler 散度 (CKLD) 来更准确地评估偏差。实验证明，我们的方法在多个 LLM 和数据集上表现出色，既稳健又灵活。

> Large language models (LLMs) often show unwarranted preference for certain choice options when responding to multiple-choice questions, posing significant reliability concerns in LLM-automated systems. To mitigate this selection bias problem, previous solutions utilized debiasing methods to adjust the model's input and/or output. Our work, in contrast, investigates the model's internal representation of the selection bias. Specifically, we introduce a novel debiasing approach, Bias Node Pruning (BNP), which eliminates the linear layer parameters that contribute to the bias. Furthermore, we present Auxiliary Option Injection (AOI), a simple yet effective input modification technique for debiasing, which is compatible even with black-box LLMs. To provide a more systematic evaluation of selection bias, we review existing metrics and introduce Choice Kullback-Leibler Divergence (CKLD), which addresses the insensitivity of the commonly used metrics to label imbalance. Experiments show that our methods are robust and adaptable across various datasets when applied to three LLMs.

[Arxiv](https://arxiv.org/abs/2409.18857)