# 里斯本计算语言学家团队在 SemEval-2024 的第二项任务中，采用了 Mistral 7B 模型并结合数据增强技术。

发布时间：2024年08月06日

`LLM应用` `临床试验`

> Lisbon Computational Linguists at SemEval-2024 Task 2: Using A Mistral 7B Model and Data Augmentation

# 摘要

> 本文介绍了我们参与 SemEval-2024 的 NLI4CT 任务的方法，该任务要求对临床试验报告的陈述进行分类。我们利用了开源大型语言模型 Mistral-7B，设计了专门的提示，并使用增强训练数据对其量化版本进行了微调。实验表明，这种方法在宏 F1 分数上表现出色，但在忠实度和一致性上仍有提升空间。所有相关代码已公开在 GitHub 上。

> This paper describes our approach to the SemEval-2024 safe biomedical Natural Language Inference for Clinical Trials (NLI4CT) task, which concerns classifying statements about Clinical Trial Reports (CTRs). We explored the capabilities of Mistral-7B, a generalist open-source Large Language Model (LLM). We developed a prompt for the NLI4CT task, and fine-tuned a quantized version of the model using an augmented version of the training dataset. The experimental results show that this approach can produce notable results in terms of the macro F1-score, while having limitations in terms of faithfulness and consistency. All the developed code is publicly available on a GitHub repository

[Arxiv](https://arxiv.org/abs/2408.03127)