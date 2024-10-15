# ALLoRA：自适应学习率巧妙化解 LoRA 的致命弱点

发布时间：2024年10月12日

`LLM理论` `人工智能` `机器学习`

> ALLoRA: Adaptive Learning Rate Mitigates LoRA Fatal Flaws

# 摘要

> 低秩适应 (LoRA) 是大语言模型 (LLM) 微调的核心技术。LoRA 通过学习预训练矩阵 $W$ 的低秩扰动 $AB$，以 $W+AB$ 的方式实现模型在新任务或数据集上的对齐。然而，LoRA 在微调过程中存在三个主要限制：首先，Dropout 仅适用于长时间训练，短时间训练中无法有效正则化；其次，$B$ 的初始化为 $0$ 导致训练缓慢，Dropout 进一步加剧了这一问题；第三，缩放因子导致不同层 LoRA 模块间的交互“短视”。基于这些分析，我们提出了 ALLoRA，一种无 Dropout、无缩放的 LoRA，通过自适应学习率优化，有效缓解了上述限制，并移除了两个超参数。实证结果显示，ALLoRA 在多种设置下均优于 LoRA，包括与最新变体 DoRA 相比。消融研究进一步证明，ALLoRA 在多种 LLM 中表现最优。

> Low-Rank Adaptation (LoRA) is the bread and butter of Large Language Model (LLM) finetuning. LoRA learns an additive low-rank perturbation, $AB$, of a pretrained matrix parameter $W$ to align the model to a new task or dataset with $W+AB$. We identify three core limitations to LoRA for finetuning--a setting that employs limited amount of data and training steps. First, LoRA employs Dropout to prevent overfitting. We prove that Dropout is only suitable for long training episodes but fails to converge to a reliable regularizer for short training episodes. Second, LoRA's initialization of $B$ at $0$ creates a slow training dynamic between $A$ and $B$. That dynamic is also exacerbated by Dropout that further slows the escape from $0$ for $B$ which is particularly harmful for short training episodes. Third, the scaling factor multiplying each LoRA additive perturbation creates ``short-sighted'' interactions between the LoRA modules of different layers. Motivated by principled analysis of those limitations, we find an elegant solution: a Dropout-free, scaling-free, LoRA with Adaptive Learning rate--coined ALLoRA. By scaling the per sample and per parameter gradients with a coefficient inversely proportional to parameters' $\ell_2$ norm, ALLoRA alleviates those three limitations. As a by-product, ALLoRA removes two hyper-parameters from LoRA: the scaling factor and the dropout rate. Empirical results show that ALLoRA admits better accuracy than LoRA on various settings, including against recent LoRA variants such as Weight-Decomposed Low-Rank Adaptation (DoRA). Ablation studies show our solution is the optimal in a family of weight-dependent / output-dependent approaches on various LLMs including the latest Llama3.

[Arxiv](https://arxiv.org/abs/2410.09692)