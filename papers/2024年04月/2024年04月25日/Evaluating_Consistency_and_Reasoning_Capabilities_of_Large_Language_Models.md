# 探究大型语言模型的内在一致性与逻辑推理功能

发布时间：2024年04月25日

`LLM应用` `人工智能`

> Evaluating Consistency and Reasoning Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）广泛应用于多个领域，如学术、研究、商业和金融，处理文本生成、摘要和翻译等任务。尽管它们备受青睐，但这些模型有时会生成错误或误导性的信息，存在“幻觉”现象。这一问题主要归咎于模型的一致性和推理能力的不足。LLMs 常常无法生成合理的解释或进行连贯的推理，导致回答不准确。它们的输出也常常自相矛盾。本研究旨在评估公共和专有 LLMs 在一致性和推理能力上的表现。我们采用 Boolq 数据集作为基准，该数据集包含问题、答案及其解释。我们将数据集中的查询作为提示输入 LLMs，并将其生成的回答与基准答案进行比较。同时，我们生成解释以评估模型的推理能力。通过多次提出相同问题，观察模型回答的变化来评估其一致性。而推理能力的评估，则通过将模型生成的解释与基准解释进行比较，使用 BERT、BLEU 和 F-1 等指标进行量化。研究发现，专有模型在一致性和推理能力上普遍优于公共模型。然而，即便是面对基础常识问题，也没有模型在这两个方面达到 90% 的准确率。本研究揭示了 LLMs 中一致性与推理能力之间的密切联系，并指出了当前语言模型在推理方面所面临的挑战。

> Large Language Models (LLMs) are extensively used today across various sectors, including academia, research, business, and finance, for tasks such as text generation, summarization, and translation. Despite their widespread adoption, these models often produce incorrect and misleading information, exhibiting a tendency to hallucinate. This behavior can be attributed to several factors, with consistency and reasoning capabilities being significant contributors. LLMs frequently lack the ability to generate explanations and engage in coherent reasoning, leading to inaccurate responses. Moreover, they exhibit inconsistencies in their outputs. This paper aims to evaluate and compare the consistency and reasoning capabilities of both public and proprietary LLMs. The experiments utilize the Boolq dataset as the ground truth, comprising questions, answers, and corresponding explanations. Queries from the dataset are presented as prompts to the LLMs, and the generated responses are evaluated against the ground truth answers. Additionally, explanations are generated to assess the models' reasoning abilities. Consistency is evaluated by repeatedly presenting the same query to the models and observing for variations in their responses. For measuring reasoning capabilities, the generated explanations are compared to the ground truth explanations using metrics such as BERT, BLEU, and F-1 scores. The findings reveal that proprietary models generally outperform public models in terms of both consistency and reasoning capabilities. However, even when presented with basic general knowledge questions, none of the models achieved a score of 90\% in both consistency and reasoning. This study underscores the direct correlation between consistency and reasoning abilities in LLMs and highlights the inherent reasoning challenges present in current language models.

[Arxiv](https://arxiv.org/abs/2404.16478)