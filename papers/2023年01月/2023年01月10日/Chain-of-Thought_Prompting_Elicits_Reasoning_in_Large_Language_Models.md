# 思维链提示法激发大型语言模型展现推理之光

发布时间：2023年01月10日

`LLM理论

这篇论文探讨了大型语言模型（LLM）的推理能力提升方法，通过引入思维链提示技术，展示了如何通过中间推理步骤增强模型的复杂推理能力。这种方法涉及理论层面的创新，即如何设计和利用思维链来优化模型的性能，因此属于LLM理论分类。论文中的实验和结果分析也是围绕这一理论创新展开的，进一步验证了思维链提示在提升LLM推理能力方面的有效性。` `人工智能`

> Chain-of-Thought Prompting Elicits Reasoning in Large Language Models

# 摘要

> 我们研究发现，通过构建思维链——一系列中间推理步骤，大型语言模型的复杂推理能力得到了显著提升。具体而言，我们采用了一种名为思维链提示的简单方法，在提示中提供几个思维链演示作为范例，从而使大型语言模型自然地展现出强大的推理能力。对三种大型语言模型的实验结果显示，思维链提示在算术、常识和符号推理任务上均取得了显著的性能提升。例如，仅用八个思维链示例提示一个540亿参数的语言模型，就在GSM8K数学问题基准上达到了最先进的准确性，甚至超过了经过验证的微调GPT-3。

> We explore how generating a chain of thought -- a series of intermediate reasoning steps -- significantly improves the ability of large language models to perform complex reasoning. In particular, we show how such reasoning abilities emerge naturally in sufficiently large language models via a simple method called chain of thought prompting, where a few chain of thought demonstrations are provided as exemplars in prompting. Experiments on three large language models show that chain of thought prompting improves performance on a range of arithmetic, commonsense, and symbolic reasoning tasks. The empirical gains can be striking. For instance, prompting a 540B-parameter language model with just eight chain of thought exemplars achieves state of the art accuracy on the GSM8K benchmark of math word problems, surpassing even finetuned GPT-3 with a verifier.

[Arxiv](https://arxiv.org/abs/2201.11903)