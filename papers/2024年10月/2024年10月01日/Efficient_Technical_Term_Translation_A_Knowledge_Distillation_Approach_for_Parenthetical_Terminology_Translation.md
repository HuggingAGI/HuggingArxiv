# 技术术语翻译高效之道：括号术语翻译的知识蒸馏法

发布时间：2024年10月01日

`LLM应用` `专业领域`

> Efficient Technical Term Translation: A Knowledge Distillation Approach for Parenthetical Terminology Translation

# 摘要

> 本文探讨了技术术语翻译的难题，这对于专业领域的沟通至关重要。我们提出了括号术语翻译（PTT）任务，通过在翻译术语旁显示原文，减少不准确性。我们生成了PTT数据集，并利用知识蒸馏微调NMT和sLMs。此外，我们设计了新的评估指标，综合考量翻译准确性和术语括号展示。研究发现，sLMs并非始终优于NMT，微调比少样本提示更有效，特别是在目标语言中继续预训练的模型中。这些发现推动了更可靠的术语翻译方法的发展。

> This paper addresses the challenge of accurately translating technical terms, which are crucial for clear communication in specialized fields. We introduce the Parenthetical Terminology Translation (PTT) task, designed to mitigate potential inaccuracies by displaying the original term in parentheses alongside its translation. To implement this approach, we generated a representative PTT dataset using a collaborative approach with large language models and applied knowledge distillation to fine-tune traditional Neural Machine Translation (NMT) models and small-sized Large Language Models (sLMs). Additionally, we developed a novel evaluation metric to assess both overall translation accuracy and the correct parenthetical presentation of terms. Our findings indicate that sLMs did not consistently outperform NMT models, with fine-tuning proving more effective than few-shot prompting, particularly in models with continued pre-training in the target language. These insights contribute to the advancement of more reliable terminology translation methodologies.

[Arxiv](https://arxiv.org/abs/2410.00683)