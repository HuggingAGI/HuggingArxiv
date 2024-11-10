# 利用低秩适应的贝叶斯重新参数化对大型语言模型进行稳健且高效的微调

发布时间：2024年11月06日

`LLM应用` `模型微调`

> Robust and Efficient Fine-tuning of LLMs with Bayesian Reparameterization of Low-Rank Adaptation

# 摘要

> 大型语言模型（LLMs）由于其规模巨大，微调时资源消耗极高。虽然低秩适应是一种突出的参数高效微调方法，但它对超参数选择敏感，导致在微调下游任务时模型性能不稳定。本文强调了在低秩微调中有效参数化的重要性，以减少估计器方差并提高最终模型输出的稳定性。我们提出了MonteCLoRA，一种高效的微调技术，采用蒙特卡罗估计来学习具有低预期方差的低秩参数的无偏后验估计，仅使用O(1)个额外参数即可稳定微调后的LLMs。MonteCLoRA在准确性和鲁棒性方面显示出显著的改进，在使用预训练的RoBERTa-base的自然语言理解任务中，比现有的高效微调方法准确率提高了高达3.8％，鲁棒性提高了8.6％。此外，在使用预训练的LLaMA-1-7B的生成任务中，MonteCLoRA展示了强大的零样本性能，方差比当代高效微调方法低50％。本文中呈现的理论和实证结果强调了参数化和超先验如何在低秩参数空间中平衡探索与利用，从而在高效微调期间实现更优和更稳健的参数估计。

> Large Language Models (LLMs) are highly resource-intensive to fine-tune due to their enormous size. While low-rank adaptation is a prominent parameter-efficient fine-tuning approach, it suffers from sensitivity to hyperparameter choices, leading to instability in model performance on fine-tuning downstream tasks. This paper highlights the importance of effective parameterization in low-rank fine-tuning to reduce estimator variance and enhance the stability of final model outputs. We propose MonteCLoRA, an efficient fine-tuning technique, employing Monte Carlo estimation to learn an unbiased posterior estimation of low-rank parameters with low expected variance, which stabilizes fine-tuned LLMs with only O(1) additional parameters. MonteCLoRA shows significant improvements in accuracy and robustness, achieving up to 3.8% higher accuracy and 8.6% greater robustness than existing efficient fine-tuning methods on natural language understanding tasks with pre-trained RoBERTa-base. Furthermore, in generative tasks with pre-trained LLaMA-1-7B, MonteCLoRA demonstrates robust zero-shot performance with 50% lower variance than the contemporary efficient fine-tuning methods. The theoretical and empirical results presented in the paper underscore how parameterization and hyperpriors balance exploration-exploitation in the low-rank parametric space, therefore leading to more optimal and robust parameter estimation during efficient fine-tuning.

[Arxiv](https://arxiv.org/abs/2411.04358)