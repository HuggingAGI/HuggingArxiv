# 探究大型语言模型的连贯性与逻辑推理功能

发布时间：2024年04月25日

`LLM应用` `学术研究`

> Evaluating Consistency and Reasoning Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）广泛应用于学术、研究、商业和金融等多个领域，执行文本生成、摘要和翻译等任务。然而，尽管它们广受欢迎，这些模型却常常制造出错误和具有误导性的信息，似乎有“幻觉”倾向。这一现象主要归咎于它们的一致性和推理能力的不足。LLMs往往无法生成合理的解释，也难以进行连贯的推理，从而导致了不准确的回答，并且它们的输出结果常常自相矛盾。本文的目标是评估并对比公共与专有LLMs在一致性和推理能力上的表现。研究使用了Boolq数据集作为基准，该数据集包含了问题、答案及其对应的解释。我们将数据集中的查询作为提示输入LLMs，并将其生成的回答与基准答案进行比较。同时，我们也生成了解释，以评估模型的推理能力。通过多次向模型提出相同的问题，观察其回答的变化，以此来评估一致性。而推理能力的衡量，则是通过将生成的解释与基准解释使用BERT、BLEU和F-1分数等指标进行比较。研究发现，专有模型在一致性和推理能力上普遍优于公共模型。但即便面对基础的常识性问题，也没有一个模型在一致性和推理上得分超过90%。本研究突出了LLMs中一致性和推理能力之间的密切联系，并揭示了当前语言模型在推理方面的内在挑战。

> Large Language Models (LLMs) are extensively used today across various sectors, including academia, research, business, and finance, for tasks such as text generation, summarization, and translation. Despite their widespread adoption, these models often produce incorrect and misleading information, exhibiting a tendency to hallucinate. This behavior can be attributed to several factors, with consistency and reasoning capabilities being significant contributors. LLMs frequently lack the ability to generate explanations and engage in coherent reasoning, leading to inaccurate responses. Moreover, they exhibit inconsistencies in their outputs. This paper aims to evaluate and compare the consistency and reasoning capabilities of both public and proprietary LLMs. The experiments utilize the Boolq dataset as the ground truth, comprising questions, answers, and corresponding explanations. Queries from the dataset are presented as prompts to the LLMs, and the generated responses are evaluated against the ground truth answers. Additionally, explanations are generated to assess the models' reasoning abilities. Consistency is evaluated by repeatedly presenting the same query to the models and observing for variations in their responses. For measuring reasoning capabilities, the generated explanations are compared to the ground truth explanations using metrics such as BERT, BLEU, and F-1 scores. The findings reveal that proprietary models generally outperform public models in terms of both consistency and reasoning capabilities. However, even when presented with basic general knowledge questions, none of the models achieved a score of 90\% in both consistency and reasoning. This study underscores the direct correlation between consistency and reasoning abilities in LLMs and highlights the inherent reasoning challenges present in current language models.

[Arxiv](https://arxiv.org/abs/2404.16478)