# 表格数据任务的智能提示生成系统在这个系统中，我们将探索如何自动生成有效的提示，以帮助用户更好地理解和处理表格数据。通过智能算法，系统能够识别数据的关键特征，并据此生成针对性的提示，从而提高用户在处理表格数据任务时的效率和准确性。

发布时间：2024年05月09日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）高效处理结构化的表格数据集，特别是面对列数众多的数据集时。它提出了一种自动提示生成系统，该系统能够适应多种LLMs，并且对训练的需求很低。论文中的方法通过基于强化学习的算法和基于单元格相似性的策略，有效地处理了表格数据集中的列管理和样本示例选择问题。这种方法在多个数据集上进行了测试，并在数据插补、错误检测和实体匹配等下游任务上提升了性能。因此，这篇论文属于LLM应用类别，因为它专注于LLMs在实际数据处理任务中的应用和优化。` `数据处理` `人工智能`

> An Automatic Prompt Generation System for Tabular Data Tasks

# 摘要

> 在各行各业，高效处理表格数据至关重要，尤其是面对列数众多的数据集。大型语言模型（LLMs）凭借精心设计的提示在多任务上大放异彩。然而，为结构化的表格数据集设计有效提示颇具挑战，因需巧妙管理众多列。本文创新性地提出了一种自动提示生成系统，适用于多种LLMs，且训练需求极低。该系统包含两种新颖方法：一是基于强化学习的算法，用于精准识别并排序任务相关列；二是基于单元格相似性的策略，用于优化少量样本示例的选择。我们的方法在66个数据集上经过严格测试，显著提升了三个下游任务的性能：数据插补、错误检测和实体匹配，涉及两种尖端LLMs：Google flan-t5-xxl和Mixtral 8x7B。

> Efficient processing of tabular data is important in various industries, especially when working with datasets containing a large number of columns. Large language models (LLMs) have demonstrated their ability on several tasks through carefully crafted prompts. However, creating effective prompts for tabular datasets is challenging due to the structured nature of the data and the need to manage numerous columns. This paper presents an innovative auto-prompt generation system suitable for multiple LLMs, with minimal training. It proposes two novel methods; 1) A Reinforcement Learning-based algorithm for identifying and sequencing task-relevant columns 2) Cell-level similarity-based approach for enhancing few-shot example selection. Our approach has been extensively tested across 66 datasets, demonstrating improved performance in three downstream tasks: data imputation, error detection, and entity matching using two distinct LLMs; Google flan-t5-xxl and Mixtral 8x7B.

[Arxiv](https://arxiv.org/abs/2405.05618)