# 《数字食谱：语言模型的数字理解以及如何改进它》

发布时间：2024年11月06日

`LLM应用` `数字处理`

> Number Cookbook: Number Understanding of Language Models and How to Improve It

# 摘要

> 大型语言模型（LLM）能够解决越来越多的复杂推理任务，但在基本的数字理解和处理（例如 9.11 > 9.9）方面会出现令人惊讶的错误。后一种能力对于解决复杂的算术和数学问题至关重要，并且是大多数推理任务的基础，但之前的工作对此关注甚少，或者只讨论了几个受限的任务（如整数加法）。在本文中，我们全面研究了 LLM 的数字理解和处理能力（NUPA）。首先，我们引入了一个基准，涵盖了四种常见的数字表示和四大类中的 17 个不同的数字任务，总共产生了 41 个有意义的组合。这些任务源自中小学课程，涵盖了几乎所有日常的数字理解和处理场景，并且这些任务的规则非常简单明了。通过该基准，我们发现当前的 LLM 在许多任务中经常失败。为了研究这个问题，我们使用现有和潜在的技术（例如特殊的分词器、PE 和数字格式）训练小型模型以增强 NUPA，并使用我们的测试平台全面评估其有效性。我们还在我们提出的 NUPA 任务上对实际规模的 LLM 进行微调，发现 1）朴素的微调可以在许多但并非所有任务上大大提高 NUPA，2）令人惊讶的是，旨在增强 NUPA 的技术对于微调预训练模型证明是无效的。我们进一步探索了思维链技术对 NUPA 的影响。我们的工作朝着理解和提高 LLM 的 NUPA 迈出了初步的一步。我们的基准和代码发布在 https://github.com/GraphPKU/number_cookbook 。

> Large language models (LLMs) can solve an increasing number of complex reasoning tasks while making surprising mistakes in basic numerical understanding and processing (such as 9.11 > 9.9). The latter ability is essential for tackling complex arithmetic and mathematical problems and serves as a foundation for most reasoning tasks, but previous work paid little attention to it or only discussed several restricted tasks (like integer addition). In this paper, we comprehensively investigate the numerical understanding and processing ability (NUPA) of LLMs. Firstly, we introduce a benchmark covering four common numerical representations and 17 distinct numerical tasks in four major categories, resulting in 41 meaningful combinations in total. These tasks are derived from primary and secondary education curricula, encompassing nearly all everyday numerical understanding and processing scenarios, and the rules of these tasks are very simple and clear. Through the benchmark, we find that current LLMs fail frequently in many of the tasks. To study the problem, we train small models with existing and potential techniques for enhancing NUPA (such as special tokenizers, PEs, and number formats), comprehensively evaluating their effectiveness using our testbed. We also finetune practical-scale LLMs on our proposed NUPA tasks and find that 1) naive finetuning can improve NUPA a lot on many but not all tasks, and 2) surprisingly, techniques designed to enhance NUPA prove ineffective for finetuning pretrained models. We further explore the impact of chain-of-thought techniques on NUPA. Our work takes a preliminary step towards understanding and improving NUPA of LLMs. Our benchmark and code are released at https://github.com/GraphPKU/number_cookbook.

[Arxiv](https://arxiv.org/abs/2411.03766)