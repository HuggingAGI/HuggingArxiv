# DFKI-NLP 团队参与了 SemEval-2024 的第二项任务，旨在通过数据扰动和 MinMax 训练方法，推动构建更加稳健的大型语言模型。

发布时间：2024年05月01日

`分类：LLM应用

这篇论文摘要讨论了如何利用大型语言模型（LLMs）来构建一个稳健的模型，以处理临床试验报告（CTRs）上的自然语言推理（NLI）任务。这表明该论文主要关注LLM在特定领域的应用，即在临床试验报告的自然语言处理任务中。因此，这篇论文应该被归类为LLM应用。` `临床试验`

> DFKI-NLP at SemEval-2024 Task 2: Towards Robust LLMs Using Data Perturbations and MinMax Training

# 摘要

> SemEval-2024 的 NLI4CT 任务着重于利用大型语言模型（LLMs）为临床试验报告（CTRs）上的自然语言推理（NLI）构建稳健的模型。本版特别关注 CTRs 的数值、词汇和语义特点，并引入了相应的干预措施。我们设计的系统采用了最先进的 Mistral 模型，并结合辅助模型，专注于 NLI4CT 数据集的复杂输入维度。通过在数据中引入数值和首字母缩略词的扰动，我们培养了一个能够应对语义变更和数值矛盾干预的强韧系统。对数据集的深入分析揭示了 CTRs 在推理过程中的难点所在。

> The NLI4CT task at SemEval-2024 emphasizes the development of robust models for Natural Language Inference on Clinical Trial Reports (CTRs) using large language models (LLMs). This edition introduces interventions specifically targeting the numerical, vocabulary, and semantic aspects of CTRs. Our proposed system harnesses the capabilities of the state-of-the-art Mistral model, complemented by an auxiliary model, to focus on the intricate input space of the NLI4CT dataset. Through the incorporation of numerical and acronym-based perturbations to the data, we train a robust system capable of handling both semantic-altering and numerical contradiction interventions. Our analysis on the dataset sheds light on the challenging sections of the CTRs for reasoning.

[Arxiv](https://arxiv.org/abs/2405.00321)