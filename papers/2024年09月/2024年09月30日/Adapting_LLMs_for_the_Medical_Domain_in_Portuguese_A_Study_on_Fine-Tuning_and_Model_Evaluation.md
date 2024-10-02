# 在葡萄牙语医疗领域中，如何微调大型语言模型 (LLM) 并进行有效评估，是一项值得深入探讨的研究。

发布时间：2024年09月30日

`LLM应用` `人工智能`

> Adapting LLMs for the Medical Domain in Portuguese: A Study on Fine-Tuning and Model Evaluation

# 摘要

> 本研究旨在评估 LLM 在葡萄牙语医疗领域的应用，目标是打造一款可靠且实用的虚拟助手，助力医疗专业人员。我们使用 GPT-3.5 翻译的 HealthCareMagic-100k-en 和 MedQuAD 数据集，通过 PEFT-QLoRA 方法微调了 ChatBode-7B 模型。结果显示，经过医疗数据预训练的 InternLM2 模型表现最为出色，尤其在准确性、完整性和安全性方面。然而，源自 ChatBode 的 DrBode 模型却出现了对医疗知识的灾难性遗忘。尽管如此，这些模型在语法和连贯性上表现不俗。研究还发现，评分者间的一致性较低，这提示我们需要更严格的评估标准。这项研究为未来探索，如医疗领域多语言模型的评估、训练数据质量的提升以及更一致的评估方法的开发，奠定了基础。

> This study evaluates the performance of large language models (LLMs) as medical agents in Portuguese, aiming to develop a reliable and relevant virtual assistant for healthcare professionals. The HealthCareMagic-100k-en and MedQuAD datasets, translated from English using GPT-3.5, were used to fine-tune the ChatBode-7B model using the PEFT-QLoRA method. The InternLM2 model, with initial training on medical data, presented the best overall performance, with high precision and adequacy in metrics such as accuracy, completeness and safety. However, DrBode models, derived from ChatBode, exhibited a phenomenon of catastrophic forgetting of acquired medical knowledge. Despite this, these models performed frequently or even better in aspects such as grammaticality and coherence. A significant challenge was low inter-rater agreement, highlighting the need for more robust assessment protocols. This work paves the way for future research, such as evaluating multilingual models specific to the medical field, improving the quality of training data, and developing more consistent evaluation methodologies for the medical field.

[Arxiv](https://arxiv.org/abs/2410.00163)