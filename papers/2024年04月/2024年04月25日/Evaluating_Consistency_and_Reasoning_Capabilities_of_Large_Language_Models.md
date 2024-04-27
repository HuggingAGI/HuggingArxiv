# 探讨大型语言模型的一致性与推理能力

发布时间：2024年04月25日

`LLM应用` `学术研究` `商业金融`

> Evaluating Consistency and Reasoning Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）在学术、研究、商业和金融等多个领域被广泛应用，用于执行文本生成、摘要和翻译等任务。尽管它们普及，但这些模型有时会生成错误或误导性的信息，甚至出现幻觉现象。这种现象主要由模型的一致性和推理能力的不足所导致。LLMs 常常无法生成合理的解释或进行连贯的推理，从而导致回答不准确。它们的输出也常常不一致。本文的目标是评估并比较公共和私有 LLMs 在一致性和推理能力上的表现。实验采用 Boolq 数据集作为基准，该数据集包含了问题、答案及其解释。我们使用该数据集中的查询作为提示，向 LLMs 提出，并将它们生成的回答与基准答案进行对比。同时，我们生成解释以评估模型的推理能力。通过多次向模型提出相同的问题，观察其回答的变化，以此来评估一致性。而对于推理能力的衡量，则是通过将模型生成的解释与基准解释进行比较，使用 BERT、BLEU 和 F-1 等指标进行评分。研究发现，私有模型在一致性和推理能力上普遍优于公共模型。然而，即便是面对基础的常识性问题，也没有一个模型在一致性和推理上达到了 90% 的准确率。本研究揭示了 LLMs 中一致性和推理能力之间的密切联系，并突显了当前语言模型在推理方面所面临的挑战。

> Large Language Models (LLMs) are extensively used today across various sectors, including academia, research, business, and finance, for tasks such as text generation, summarization, and translation. Despite their widespread adoption, these models often produce incorrect and misleading information, exhibiting a tendency to hallucinate. This behavior can be attributed to several factors, with consistency and reasoning capabilities being significant contributors. LLMs frequently lack the ability to generate explanations and engage in coherent reasoning, leading to inaccurate responses. Moreover, they exhibit inconsistencies in their outputs. This paper aims to evaluate and compare the consistency and reasoning capabilities of both public and proprietary LLMs. The experiments utilize the Boolq dataset as the ground truth, comprising questions, answers, and corresponding explanations. Queries from the dataset are presented as prompts to the LLMs, and the generated responses are evaluated against the ground truth answers. Additionally, explanations are generated to assess the models' reasoning abilities. Consistency is evaluated by repeatedly presenting the same query to the models and observing for variations in their responses. For measuring reasoning capabilities, the generated explanations are compared to the ground truth explanations using metrics such as BERT, BLEU, and F-1 scores. The findings reveal that proprietary models generally outperform public models in terms of both consistency and reasoning capabilities. However, even when presented with basic general knowledge questions, none of the models achieved a score of 90\% in both consistency and reasoning. This study underscores the direct correlation between consistency and reasoning abilities in LLMs and highlights the inherent reasoning challenges present in current language models.

[Arxiv](https://arxiv.org/abs/2404.16478)