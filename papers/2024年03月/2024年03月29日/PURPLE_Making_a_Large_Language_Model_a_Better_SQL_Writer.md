# PURPLE：打造更优秀的SQL编程的大型语言模型

发布时间：2024年03月29日

`LLM应用` `数据库管理`

> PURPLE: Making a Large Language Model a Better SQL Writer

# 摘要

> 大型语言模型（LLM）在将自然语言转换为SQL（NL2SQL）方面的作用日益凸显。这些模型得益于海量语料的训练，具备了出色的自然语言理解能力和基础的SQL生成技巧，无需针对特定NL2SQL任务进行额外调优。目前，基于LLM的NL2SQL转换方法致力于通过深入理解用户意图来优化翻译效果。然而，LLMs在构建复杂的逻辑运算组合时仍显不足，有时无法生成恰当的SQL语句。一种充满希望的策略是向LLMs提供示范性输入，这些输入包含了多个数据库中已知的NL2SQL翻译案例。LLMs能够通过这些示例学习如何组织适用于特定任务的运算符组合。本文提出了一种名为PURPLE（预训练模型用于检索逻辑增强的提示）的新方法，它通过检索包含必要逻辑运算符组合的示范性输入，提升了NL2SQL任务的翻译精确度，引导LLMs生成更准确的SQL语句。在广泛使用的NL2SQL基准测试Spider的验证集上，PURPLE实现了80.5%的精确匹配准确率和87.8%的执行匹配准确率，创造了新的最高记录。PURPLE在多样化的基准测试、预算限制和不同LLMs中均展现出高准确率，证明了其鲁棒性和经济高效性。

> Large Language Model (LLM) techniques play an increasingly important role in Natural Language to SQL (NL2SQL) translation. LLMs trained by extensive corpora have strong natural language understanding and basic SQL generation abilities without additional tuning specific to NL2SQL tasks. Existing LLMs-based NL2SQL approaches try to improve the translation by enhancing the LLMs with an emphasis on user intention understanding. However, LLMs sometimes fail to generate appropriate SQL due to their lack of knowledge in organizing complex logical operator composition. A promising method is to input the LLMs with demonstrations, which include known NL2SQL translations from various databases. LLMs can learn to organize operator compositions from the input demonstrations for the given task. In this paper, we propose PURPLE (Pre-trained models Utilized to Retrieve Prompts for Logical Enhancement), which improves accuracy by retrieving demonstrations containing the requisite logical operator composition for the NL2SQL task on hand, thereby guiding LLMs to produce better SQL translation. PURPLE achieves a new state-of-the-art performance of 80.5% exact-set match accuracy and 87.8% execution match accuracy on the validation set of the popular NL2SQL benchmark Spider. PURPLE maintains high accuracy across diverse benchmarks, budgetary constraints, and various LLMs, showing robustness and cost-effectiveness.

[Arxiv](https://arxiv.org/abs/2403.20014)