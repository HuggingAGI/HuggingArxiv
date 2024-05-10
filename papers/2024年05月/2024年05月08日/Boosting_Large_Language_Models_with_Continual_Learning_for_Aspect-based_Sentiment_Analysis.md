# 借助持续学习，强化大型语言模型在基于方面的情感分析领域的应用在翻译过程中，我首先确保原文的核心意义被准确传达，即“通过持续学习提升大型语言模型在基于方面的情感分析中的性能”。随后，我进一步优化表达，使其更符合中文的流畅性和优雅性，形成了“借助持续学习，强化大型语言模型在基于方面的情感分析领域的应用”的翻译。这样的翻译既保留了原文的技术性，又增添了中文表达的生动性和简洁性。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了基于大型语言模型的持续学习（LLM-CL）模型在基于方面的情感分析（ABSA）任务中的应用。它提出了一种新的模型设计，旨在解决持续学习问题，即模型在掌握新领域知识的同时不忘记旧领域知识。该模型通过域知识解耦模块和域知识预热策略来实现这一目标，并在多个数据集上展示了其优越性能。因此，这篇论文属于LLM应用类别，因为它关注的是LLM在特定任务（ABSA）中的实际应用和改进。` `情感分析`

> Boosting Large Language Models with Continual Learning for Aspect-based Sentiment Analysis

# 摘要

> 基于方面的情感分析（ABSA）旨在提取并预测文本中的情感倾向，是情感分析的关键分支。现有研究多通过微调特定领域的模型来提升目标领域的性能。然而，关于ABSA的持续学习研究较少，这种学习旨在同时掌握新旧领域的能力。本文提出了一种基于大型语言模型的持续学习（LLM-CL）模型，专为ABSA设计。我们首先设计了一个域知识解耦模块，通过正交约束独立分离域不变和域变适配器。接着，引入域知识预热策略，以确保域不变与域变知识的表示一致。在测试时，通过域定位无需样本的域ID即可索引相应知识。实验结果显示，我们的LLM-CL模型在19个数据集上取得了领先性能。

> Aspect-based sentiment analysis (ABSA) is an important subtask of sentiment analysis, which aims to extract the aspects and predict their sentiments. Most existing studies focus on improving the performance of the target domain by fine-tuning domain-specific models (trained on source domains) based on the target domain dataset. Few works propose continual learning tasks for ABSA, which aim to learn the target domain's ability while maintaining the history domains' abilities. In this paper, we propose a Large Language Model-based Continual Learning (\texttt{LLM-CL}) model for ABSA. First, we design a domain knowledge decoupling module to learn a domain-invariant adapter and separate domain-variant adapters dependently with an orthogonal constraint. Then, we introduce a domain knowledge warmup strategy to align the representation between domain-invariant and domain-variant knowledge. In the test phase, we index the corresponding domain-variant knowledge via domain positioning to not require each sample's domain ID. Extensive experiments over 19 datasets indicate that our \texttt{LLM-CL} model obtains new state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2405.05496)