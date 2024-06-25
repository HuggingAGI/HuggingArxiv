# 引导大型语言模型辨识并排除无关条件

发布时间：2024年03月19日

`LLM应用

理由：这篇论文主要讨论了如何改进大型语言模型（LLMs）在解决数学文字问题（MWP）时的性能，特别是通过引入一种新的方法I$^3$C来识别和忽略无关条件，从而优化推理路径。这种方法直接应用于LLMs，以提高其在特定任务上的表现，因此属于LLM应用类别。论文中提到的实验结果和性能提升也进一步证实了这一点。` `人工智能`

> Instructing Large Language Models to Identify and Ignore Irrelevant Conditions

# 摘要

> 解决数学文字问题（MWP）时，需从包含无关条件的问题描述中构建推理路径。尽管现有的思维链（CoT）提示方法能激发大型语言模型（LLMs）的多步推理能力，但它们常因无关条件而陷入困境，准确性大打折扣。为此，我们提出了一种创新方法I$^3$C，它教会LLMs识别并忽略这些无关条件，通过筛选语义相关性弱的候选条件，并引导LLMs进行验证，从而清晰区分相关与无关条件，优化推理路径。我们还开发了I$^3$C-Select，通过精确测量语义相关性，挑选最具挑战性的问题进行演示，进一步提升少样本推理能力。在八个MWP数据集上的实验证明，I$^3$C能显著提升任何CoT提示方法的性能。特别地，结合GPT-3.5-Turbo和I$^3$C-Select，我们在GSM-IC2-1K和GSM-ICM-1K数据集上分别实现了96.0%和94.1%的准确率，大幅超越了Complex-CoT方法，分别提升了11.7%和11.1%。我们的研究成果已在https://wzy6642.github.io/I3C.github.io/公开。

> Math word problem (MWP) solving requires generating a reasoning path based on a given problem description that often contains irrelevant conditions. Existing chain-of-thought (CoT) prompting methods elicited multi-step reasoning abilities of large language models (LLMs) to solve MWPs. However, they were seriously confused by the irrelevant conditions, resulting in low accuracy. In this paper, we propose a novel approach named I$^3$C that instructs LLMs to identify and ignore irrelevant conditions. It identifies a set of irrelevant condition candidates that have a weak semantic relevance with the question. Then it prompts LLMs to verify the irrelevant conditions. Lastly it instructs the LLMs with the verification on relevant and irrelevant conditions to avoid confusion and improve reasoning paths. Moreover, we propose to select (problem, reasoning paths) pairs as demonstrations to enhance I$^3$C with few-shot reasoning. We develop I$^3$C-Select that selects the most confusing problems based on the semantic relevance measurement. We conduct extensive experiments on eight MWP datasets. I$^3$C can be combined with any CoT prompting methods to improve the performance of solving MWPs. Notably, with GPT-3.5-Turbo and I$^3$C-Select, we achieve an accuracy of 96.0 and 94.1 on GSM-IC2-1K and GSM-ICM-1K, respectively, significantly outperforming the state-of-the-art few-shot prompting method Complex-CoT by +11.7 and +11.1. Our implementation is made publicly available at https://wzy6642.github.io/I3C.github.io/.

[Arxiv](https://arxiv.org/abs/2403.12744)