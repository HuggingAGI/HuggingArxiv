# 丛林探秘：随机森林启发的数字导向大型语言模型研究

发布时间：2024年06月07日

`LLM应用

这篇论文主要探讨了如何通过从随机森林集成模型中转移知识来训练大型语言模型（LLMs），以提高其在数值数据处理和解读方面的能力。这种方法涉及将RF的决策路径转化为自然语言表述，并用于微调LLMs，从而提升其分类能力和决策解释力。此外，论文还分析了预处理技术对数值数据表示的影响，以及这些技术如何影响分类准确性和规则正确性。因此，这篇论文属于LLM应用类别，因为它专注于LLMs在特定任务（数值数据处理和解读）中的应用和改进。` `数据处理` `机器学习`

> Through the Thicket: A Study of Number-Oriented LLMs derived from Random Forest Models

# 摘要

> 大型语言模型（LLMs）在文本处理领域大放异彩，它们不仅能从海量数据中提炼信息，还能通过思维链（CoT）模拟人类推理过程来阐释决策。LLMs的新兴应用之一是数值数据的处理与解读，通过微调，它们在基本推理方法上的表现更上一层楼。本文创新性地提出了一种训练LLMs的方法，即从随机森林（RF）集成模型中转移知识，充分利用其高效与精准。我们将RF的决策路径转化为自然语言表述，以此来微调LLMs，提升其分类能力和决策解释力。我们的方法还涉及通过既定的分类指标来验证这些规则，确保其准确无误。同时，我们也分析了预处理技术如何影响数值数据的表示，以及它们对分类准确性和规则正确性的具体影响。

> Large Language Models (LLMs) have shown exceptional performance in text processing. Notably, LLMs can synthesize information from large datasets and explain their decisions similarly to human reasoning through a chain of thought (CoT). An emerging application of LLMs is the handling and interpreting of numerical data, where fine-tuning enhances their performance over basic inference methods. This paper proposes a novel approach to training LLMs using knowledge transfer from a random forest (RF) ensemble, leveraging its efficiency and accuracy. By converting RF decision paths into natural language statements, we generate outputs for LLM fine-tuning, enhancing the model's ability to classify and explain its decisions. Our method includes verifying these rules through established classification metrics, ensuring their correctness. We also examine the impact of preprocessing techniques on the representation of numerical data and their influence on classification accuracy and rule correctness

[Arxiv](https://arxiv.org/abs/2406.04926)