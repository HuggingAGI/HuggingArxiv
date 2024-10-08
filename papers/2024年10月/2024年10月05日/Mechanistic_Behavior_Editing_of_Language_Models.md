# 语言模型的行为机制调整

发布时间：2024年10月05日

`LLM理论` `人工智能`

> Mechanistic Behavior Editing of Language Models

# 摘要

> 大型语言模型通过网络规模文本训练，获得了广泛任务解决能力，尤其是在任务知识通过上下文示例融入生成先验时。然而，噪声数据中的虚假特征限制了其泛化能力。监督微调虽能增强任务特异性，但数据效率低下。研究表明，LLM 中噪声与可泛化神经回路共存，微调主要强化或抑制现有能力。基于此，我们提出 TaRot，一种新颖的任务适应方法，通过可学习旋转矩阵优化神经回路，显著提升零样本和少样本性能。实验证明，TaRot 在多个任务上平均提升 23.81% 和 11.15%。源代码已公开。

> Large Language Models trained on web-scale text acquire language generation abilities that can solve a wide range of tasks, particularly when task knowledge is refined into the generative prior using in-context examples. However, spurious features learned from noisy data hinder their generalizability. Supervised finetuning can introduce task specificity, but introduce data inefficiency. Prior studies indicate that (i) noisy neural circuitries coexist with generalizable ones within LLMs, and (ii) finetuning typically enhances (or suppresses) existing abilities without introducing newer ones. Building upon these, we propose TaRot, a novel method for task adaptation. TaRot intervenes in the neural circuitries using learnable rotation matrices that are optimized using Bayesian Optimization, on labelled samples in the order of standard few-shot prompting examples. Experiments on multiple classification and generation tasks using LLMs of varying sizes reveal the efficacy of TaRot, improving upon both zero- as well as few-shot performance, with average improvements (across models and tasks) of 23.81% and 11.15%, respectively. The source code is available at https://github.com/joykirat18/TaRot

[Arxiv](https://arxiv.org/abs/2410.04277)