# 探究大型语言模型的内在一致性与逻辑推理功能

发布时间：2024年04月25日

`分类：LLM理论` `学术研究`

> Evaluating Consistency and Reasoning Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）广泛应用于学术、研究、商业和金融等多个领域，承担着文本生成、摘要和翻译等任务。然而，尽管这些模型广受欢迎，它们却常常制造出错误和误导性的信息，似乎有一种“幻想”倾向。这种倾向的形成，一致性和推理能力是主要的影响因素。大型语言模型往往在生成解释和进行逻辑推理方面力不从心，从而导致了应答的不准确。此外，它们的输出结果也常常自相矛盾。本文的目标是对比评估公共与私有的大型语言模型在一致性和推理能力上的表现。实验采用了Boolq数据集作为基准，该数据集包含了问题、答案及相应的解释。将数据集中的查询作为提示输入给大型语言模型，然后将其生成的回答与基准答案进行比较。同时，为了评估模型的推理能力，还生成了解释。通过重复向模型提出相同的问题，观察其回答的变化，以此来衡量一致性。而推理能力的测量，则是通过将生成的解释与基准解释使用BERT、BLEU和F-1等指标进行对比。研究发现，私有模型在一致性和推理能力上普遍优于公共模型。但是，即便面对基础的常识性问题，也没有一个模型能够在一致性和推理上都达到90%的准确率。本研究揭示了大型语言模型中一致性与推理能力之间的密切联系，并指出了当前语言模型所面临的推理挑战。

> Large Language Models (LLMs) are extensively used today across various sectors, including academia, research, business, and finance, for tasks such as text generation, summarization, and translation. Despite their widespread adoption, these models often produce incorrect and misleading information, exhibiting a tendency to hallucinate. This behavior can be attributed to several factors, with consistency and reasoning capabilities being significant contributors. LLMs frequently lack the ability to generate explanations and engage in coherent reasoning, leading to inaccurate responses. Moreover, they exhibit inconsistencies in their outputs. This paper aims to evaluate and compare the consistency and reasoning capabilities of both public and proprietary LLMs. The experiments utilize the Boolq dataset as the ground truth, comprising questions, answers, and corresponding explanations. Queries from the dataset are presented as prompts to the LLMs, and the generated responses are evaluated against the ground truth answers. Additionally, explanations are generated to assess the models' reasoning abilities. Consistency is evaluated by repeatedly presenting the same query to the models and observing for variations in their responses. For measuring reasoning capabilities, the generated explanations are compared to the ground truth explanations using metrics such as BERT, BLEU, and F-1 scores. The findings reveal that proprietary models generally outperform public models in terms of both consistency and reasoning capabilities. However, even when presented with basic general knowledge questions, none of the models achieved a score of 90\% in both consistency and reasoning. This study underscores the direct correlation between consistency and reasoning abilities in LLMs and highlights the inherent reasoning challenges present in current language models.

[Arxiv](https://arxiv.org/abs/2404.16478)