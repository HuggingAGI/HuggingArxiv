# 揭示NLG评估器的弱点：大型语言模型驱动的统一对抗框架

发布时间：2024年05月23日

`LLM应用

这篇论文主要讨论了自然语言生成系统（NLG）的自动评估问题，并提出了一种名为AdvEval的黑盒对抗框架，用于生成能够引发人类与评估工具间显著分歧的数据。该框架利用大型语言模型（LLM）作为数据生成源和评估者，通过自动优化反馈来生成对抗性数据。论文的实验结果显示，AdvEval能够显著削弱多种评估工具的性能。因此，这篇论文属于LLM应用类别，因为它探讨了LLM在NLG评估中的应用，并提出了一种新的评估方法。` `评估工具`

> Unveiling the Achilles' Heel of NLG Evaluators: A Unified Adversarial Framework Driven by Large Language Models

# 摘要

> 自然语言生成系统的自动评估一直是个难题。新近研究虽已发现多种神经度量与人类评价相契合，但这些评估工具对对抗性干扰的抵抗力仍鲜为人知，主要是因为获取不同NLG评估任务的对抗性数据颇具挑战。为此，我们推出了AdvEval，一种专为NLG评估者设计的黑盒对抗框架。它旨在生成能引发人类与评估工具间显著分歧的数据。受大型语言模型在文本生成与评估上成功的启发，我们利用这些模型既作为数据生成源，也作为黄金标准评估者。通过自动优化来自黄金与受害者评估者的反馈，我们生成了对抗性数据。实验覆盖了12种评估工具和11个NLG数据集，涉及对话、摘要及问题评估等任务。结果表明，AdvEval能显著削弱多种评估工具的性能，证明了其有效性。

> The automatic evaluation of natural language generation (NLG) systems presents a long-lasting challenge. Recent studies have highlighted various neural metrics that align well with human evaluations. Yet, the robustness of these evaluators against adversarial perturbations remains largely under-explored due to the unique challenges in obtaining adversarial data for different NLG evaluation tasks. To address the problem, we introduce AdvEval, a novel black-box adversarial framework against NLG evaluators. AdvEval is specially tailored to generate data that yield strong disagreements between human and victim evaluators. Specifically, inspired by the recent success of large language models (LLMs) in text generation and evaluation, we adopt strong LLMs as both the data generator and gold evaluator. Adversarial data are automatically optimized with feedback from the gold and victim evaluator. We conduct experiments on 12 victim evaluators and 11 NLG datasets, spanning tasks including dialogue, summarization, and question evaluation. The results show that AdvEval can lead to significant performance degradation of various victim metrics, thereby validating its efficacy.

[Arxiv](https://arxiv.org/abs/2405.14646)