# 大型语言和视觉语言模型的医学适应性的有限影响

发布时间：2024年11月13日

`LLM应用` `模型评估`

> The Limited Impact of Medical Adaptation of Large Language and Vision-Language Models

# 摘要

> 最近的几项工作试图专门为医疗应用开发基础模型，通过在公开可用的生物医学语料库上继续预训练来调整通用的大型语言模型（LLM）和视觉语言模型（VLM）。这些工作通常声称这种领域自适应预训练（DAPT）提高了下游医疗任务的性能，例如回答医疗执照考试问题。在本文中，我们将十个公共“医疗”LLM 和两个 VLM 与其相应的基础模型进行比较，得出了不同的结论：在医疗问答（QA）的零/少样本提示和有监督微调机制中，所有医疗 VLM 和几乎所有医疗 LLM 都未能始终优于其基础模型。例如，在我们考虑的 3 样本设置中的所有任务和模型对中，医疗 LLM 仅在 22.7％的情况下优于其基础模型，在 36.8％的情况下达到（统计）平局，在其余 40.5％的情况下明显不如其基础模型。我们的结论基于（i）将每个医疗模型直接与相应的基础模型进行一对一比较；（ii）在零/少样本提示中分别为每个模型优化提示；（iii）在比较中考虑统计不确定性。虽然这些基本实践在文献中并未始终采用，但我们的消融研究表明它们对结论有重大影响。同时，我们发现，在特定 QA 任务上进行微调后，医疗 LLM 可以显示出性能改进，但这些益处并未延伸到基于临床笔记的任务。我们的发现表明，最先进的通用领域模型可能已经展现出强大的医疗知识和推理能力，并为加强未来研究的结论提供了建议。

> Several recent works seek to develop foundation models specifically for medical applications, adapting general-purpose large language models (LLMs) and vision-language models (VLMs) via continued pretraining on publicly available biomedical corpora. These works typically claim that such domain-adaptive pretraining (DAPT) improves performance on downstream medical tasks, such as answering medical licensing exam questions. In this paper, we compare ten public "medical" LLMs and two VLMs against their corresponding base models, arriving at a different conclusion: all medical VLMs and nearly all medical LLMs fail to consistently improve over their base models in the zero-/few-shot prompting and supervised fine-tuning regimes for medical question-answering (QA). For instance, across all tasks and model pairs we consider in the 3-shot setting, medical LLMs only outperform their base models in 22.7% of cases, reach a (statistical) tie in 36.8% of cases, and are significantly worse than their base models in the remaining 40.5% of cases. Our conclusions are based on (i) comparing each medical model head-to-head, directly against the corresponding base model; (ii) optimizing the prompts for each model separately in zero-/few-shot prompting; and (iii) accounting for statistical uncertainty in comparisons. While these basic practices are not consistently adopted in the literature, our ablations show that they substantially impact conclusions. Meanwhile, we find that after fine-tuning on specific QA tasks, medical LLMs can show performance improvements, but the benefits do not carry over to tasks based on clinical notes. Our findings suggest that state-of-the-art general-domain models may already exhibit strong medical knowledge and reasoning capabilities, and offer recommendations to strengthen the conclusions of future studies.

[Arxiv](https://arxiv.org/abs/2411.08870)