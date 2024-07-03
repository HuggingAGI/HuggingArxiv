# PromptIntern：在大语言模型微调过程中，通过内部化循环提示，有效节省推理成本。

发布时间：2024年07月02日

`LLM应用` `软件开发`

> PromptIntern: Saving Inference Costs by Internalizing Recurrent Prompt during Large Language Model Fine-tuning

# 摘要

> 大型语言模型（LLM）凭借强大的提示技术，在多种自然语言处理任务中发挥着关键作用。然而，在实际应用中，重复查询的相似提示组件常导致推理时的计算负担加重。尽管现有方法如提示压缩和直接微调试图解决这一问题，但在成本与性能的平衡上，尤其是在复杂的 NL2Code 任务中，仍显不足。为此，我们提出了 PromptIntern 方法，通过渐进式微调将提示知识融入模型参数，模拟人类学习新任务的过程，逐步内化并淘汰提示中的模板和示例。实验结果显示，该方法不仅大幅减少了推理令牌，提升了推理速度，还显著降低了成本。

> Large language models (LLMs) have played a fundamental role in various natural language processing tasks with powerful prompt techniques. However, in real-world applications, there are often similar prompt components for repeated queries, which causes significant computational burdens during inference. Existing prompt compression and direct fine-tuning methods aim to tackle these challenges, yet they frequently struggle to strike an optimal balance between cost-efficiency and performance effectiveness, especially in complex tasks such as NL2Code. In this paper, we propose a novel method namely PromptIntern to internalize the prompt knowledge into model parameters via progressive fine-tuning. Our method enables LLMs to emulate the human learning process for a new task, where detailed templates and examples in a prompt are gradually internalized and phased out progressively as the model grows accustomed to the task. Extensive experiments demonstrate that our method reduces inference tokens over 90%, speedups inference by 4.2 times, and saves 88.3% monetary cost.

[Arxiv](https://arxiv.org/abs/2407.02211)