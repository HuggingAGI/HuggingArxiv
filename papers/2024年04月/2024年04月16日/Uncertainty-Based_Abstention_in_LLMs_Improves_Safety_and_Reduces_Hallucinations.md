# 在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。

发布时间：2024年04月16日

`LLM应用` `问答系统` `人工智能`

> Uncertainty-Based Abstention in LLMs Improves Safety and Reduces Hallucinations

# 摘要

> 大型语言模型（LLMs）的不稳定性是其广泛应用的主要障碍，这在准确性、面对无解问题的幻觉现象，以及安全性上尤为突出。在这些情况下，理想的做法是模型能够像人类一样，感知不确定性并选择不作答。本研究借鉴了分类领域的方法，探索了在问答任务中，当LLMs面临不确定性时选择不回答的可行性与效果。我们考察了两种不确定性的度量方式：统计不确定性指标和一种特别的口头表达不确定性度量，即对话中的不确定性（InDU）。通过结合使用这些不确定性度量，并对比有无人类反馈强化学习（RLHF）的模型，我们发现在所有三种情况下，基于恰当的不确定性度量而做出的不回答决策能够显著提升LLMs的可靠性。我们仅通过放弃少数高度不确定的样本，就能使准确性提升2%到8%，减少50%的幻觉现象，并通过正确识别无解问题，将安全性提高70%至99%，且几乎不增加计算成本。

> A major barrier towards the practical deployment of large language models (LLMs) is their lack of reliability. Three situations where this is particularly apparent are correctness, hallucinations when given unanswerable questions, and safety. In all three cases, models should ideally abstain from responding, much like humans, whose ability to understand uncertainty makes us refrain from answering questions we don't know. Inspired by analogous approaches in classification, this study explores the feasibility and efficacy of abstaining while uncertain in the context of LLMs within the domain of question-answering. We investigate two kinds of uncertainties, statistical uncertainty metrics and a distinct verbalized measure, termed as In-Dialogue Uncertainty (InDU). Using these uncertainty measures combined with models with and without Reinforcement Learning with Human Feedback (RLHF), we show that in all three situations, abstention based on the right kind of uncertainty measure can boost the reliability of LLMs. By sacrificing only a few highly uncertain samples we can improve correctness by 2% to 8%, avoid 50% hallucinations via correctly identifying unanswerable questions and increase safety by 70% up to 99% with almost no additional computational overhead.

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x2.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x3.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x4.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x5.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x6.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x7.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x8.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x9.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x10.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x11.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x12.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x13.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x14.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x15.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x16.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x17.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x18.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x19.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x20.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x21.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x22.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x23.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x24.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x25.png)

![在大型语言模型（LLM）中，采纳基于不确定性的策略可以显著提升模型的安全性，同时有效减少错误信息的产生，即所谓的“幻觉”现象。](../../../paper_images/2404.10960/x26.png)

[Arxiv](https://arxiv.org/abs/2404.10960)