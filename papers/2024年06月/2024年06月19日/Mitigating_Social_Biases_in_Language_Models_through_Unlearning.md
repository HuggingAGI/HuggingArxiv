# 借助遗忘技术，我们致力于消除语言模型中的社会偏见。

发布时间：2024年06月19日

`LLM应用

这篇论文主要探讨了如何通过机器遗忘技术减轻语言模型中的偏差问题，特别是针对大型开源语言模型如LLaMA-2和OPT。研究中采用了两种遗忘技术：分区对比梯度遗忘（PCGU）和通过任务向量进行否定，并进行了实证分析以评估这些技术在减少模型偏差方面的效果。这些技术旨在在较低的成本下消除模型中的不良行为，这与LLM的应用层面紧密相关，因此将其归类为LLM应用。` `机器学习` `人工智能`

> Mitigating Social Biases in Language Models through Unlearning

# 摘要

> 随着语言模型（LMs）的广泛应用，如何减轻其偏差已成为一个紧迫的问题。目前，许多方法集中在数据预处理和模型微调上，这些方法既耗时又计算成本高。因此，机器遗忘技术因其能够在较低成本下消除预训练或微调模型中的不良行为而受到关注。本研究中，我们探讨了两种遗忘技术：分区对比梯度遗忘（PCGU）和通过任务向量进行否定，旨在减少如LLaMA-2和OPT等先进开源LMs中的社会偏差。我们还为大型模型开发了分布式PCGU。实证分析显示，通过任务向量进行否定的方法在去偏差方面表现更佳，且对模型性能和困惑度的影响最小。在LLaMA-27B模型上，该方法成功将偏差分数降低了11.8%。

> Mitigating bias in language models (LMs) has become a critical problem due to the widespread deployment of LMs. Numerous approaches revolve around data pre-processing and fine-tuning of language models, tasks that can be both time-consuming and computationally demanding. Consequently, there is a growing interest in machine unlearning techniques given their capacity to induce the forgetting of undesired behaviors of the existing pre-trained or fine-tuned models with lower computational cost. In this work, we explore two unlearning methods, (1) Partitioned Contrastive Gradient Unlearning (PCGU) applied on decoder models and (2) Negation via Task Vector, to reduce social biases in state-of-the-art and open-source LMs such as LLaMA-2 and OPT. We also implement distributed PCGU for large models. It is empirically shown, through quantitative and qualitative analyses, that negation via Task Vector method outperforms PCGU in debiasing with minimum deterioration in performance and perplexity of the models. On LLaMA-27B, negation via Task Vector reduces the bias score by 11.8%

![借助遗忘技术，我们致力于消除语言模型中的社会偏见。](../../../paper_images/2406.13551/pcgu-bias_ablation.png)

![借助遗忘技术，我们致力于消除语言模型中的社会偏见。](../../../paper_images/2406.13551/pcgu-ppl_ablation.png)

![借助遗忘技术，我们致力于消除语言模型中的社会偏见。](../../../paper_images/2406.13551/tv-bias_ablation.png)

![借助遗忘技术，我们致力于消除语言模型中的社会偏见。](../../../paper_images/2406.13551/tv-ppl_ablation.png)

[Arxiv](https://arxiv.org/abs/2406.13551)