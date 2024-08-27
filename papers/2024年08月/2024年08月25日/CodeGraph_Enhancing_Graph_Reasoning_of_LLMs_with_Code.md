# CodeGraph：借助代码提升 LLMs 的图推理性能

发布时间：2024年08月25日

`LLM应用` `计算机科学` `人工智能`

> CodeGraph: Enhancing Graph Reasoning of LLMs with Code

# 摘要

> 随着大型语言模型 (LLM) 的普及，对基本图算法问题进行推理成为评估其复杂图推理能力的关键步骤。传统方法将图数据转为文本后利用 LLM 进行推理，但 LLM 在算术计算上常出错，且难以控制推理输出，引发对其猜测性的质疑。为此，我们提出 CodeGraph，一种将图问题解决方案编码为代码的方法，通过学习示例、生成并执行程序来解决新图问题。在少样本设置下，我们评估了 CodeGraph 在多个 LLM 上的表现，实验结果显示，CodeGraph 能显著提升图推理任务性能，最高达 58.6%，且在算术问题上表现优异，为推理过程提供了更可控和可解释的途径。

> With the increasing popularity of large language models (LLMs), reasoning on basic graph algorithm problems is an essential intermediate step in assessing their abilities to process and infer complex graph reasoning tasks. Existing methods usually convert graph-structured data to textual descriptions and then use LLMs for reasoning and computation. However, LLMs often produce computation errors on arithmetic parts in basic graph algorithm problems, such as counting number of edges. In addition, they struggle to control or understand the output of the reasoning process, raising concerns about whether LLMs are simply guessing. In this paper, we introduce CodeGraph, a method that encodes graph problem solutions as code. The methods solve new graph problems by learning from exemplars, generating programs, and executing them via a program interpreter. Using the few-shot setting, we evaluate CodeGraph with the base LLM being GPT-3.5 Turbo, Llama3-70B Instruct, Mixtral-8x22B Instruct, and Mixtral-8x7B Instruct. Experimental results on six tasks with six graph encoding methods in the GraphQA dataset demonstrate that CodeGraph can boost performance on graph reasoning tasks inside LLMs by 1.3% to 58.6%, depending on the task. Compared to the existing methods, CodeGraph demonstrates strong performance on arithmetic problems in graph tasks and offers a more controllable and interpretable approach to the reasoning process.

[Arxiv](https://arxiv.org/abs/2408.13863)