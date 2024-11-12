# 对于类似 GPT 的深度模型的提示高效微调，以使用随机优化技术减少幻觉并提高科学文本生成中的可重复性

发布时间：2024年11月10日

`LLM应用` `质谱计算` `科学文本生成`

> Prompt-Efficient Fine-Tuning for GPT-like Deep Models to Reduce Hallucination and to Improve Reproducibility in Scientific Text Generation Using Stochastic Optimisation Techniques

# 摘要

> 大型语言模型（LLM）越来越多地被用于复杂的科学文本生成任务，但它们经常在准确性、一致性和幻觉控制方面存在局限性。本论文介绍了一种为类 GPT 模型量身定制的参数高效微调（PEFT）方法，旨在减轻幻觉并提高可重复性，特别是在质谱计算领域。我们使用质谱文献的专门语料库，实现了低秩适配（LoRA）适配器来优化 GPT-2，称为 MS-GPT。通过应用于 LLM 的新评估方法，包括 BLEU、ROUGE 和困惑度得分，微调后的 MS-GPT 模型与基线 GPT-2 相比，表现出更优的文本连贯性和可重复性，这通过 Wilcoxon 秩和检验的统计分析得到证实。此外，我们提出了一种基于受控提示下模型输出的余弦相似度的可重复性指标，展示了 MS-GPT 增强的稳定性。这项研究突出了 PEFT 在为科学情境优化 LLM 方面的潜力，降低了计算成本，同时提高了模型的可靠性。

> Large Language Models (LLMs) are increasingly adopted for complex scientific text generation tasks, yet they often suffer from limitations in accuracy, consistency, and hallucination control. This thesis introduces a Parameter-Efficient Fine-Tuning (PEFT) approach tailored for GPT-like models, aiming to mitigate hallucinations and enhance reproducibility, particularly in the computational domain of mass spectrometry. We implemented Low-Rank Adaptation (LoRA) adapters to refine GPT-2, termed MS-GPT, using a specialized corpus of mass spectrometry literature. Through novel evaluation methods applied to LLMs, including BLEU, ROUGE, and Perplexity scores, the fine-tuned MS-GPT model demonstrated superior text coherence and reproducibility compared to the baseline GPT-2, confirmed through statistical analysis with the Wilcoxon rank-sum test. Further, we propose a reproducibility metric based on cosine similarity of model outputs under controlled prompts, showcasing MS-GPT's enhanced stability. This research highlights PEFT's potential to optimize LLMs for scientific contexts, reducing computational costs while improving model reliability.

[Arxiv](https://arxiv.org/abs/2411.06445)