# LLM-Neo：大型语言模型的参数高效知识蒸馏

发布时间：2024年11月11日

`LLM应用` `语言模型` `知识转移`

> LLM-Neo: Parameter Efficient Knowledge Distillation for Large Language Models

# 摘要

> 在本文中，我们提出了一种新颖的 LLM-Neo 框架，它能有效地将知识从大型语言模型（LLM）教师转移到紧凑的学生模型。最初，我们重新审视了知识蒸馏（KD）和低秩适应（LoRA），并认为它们具有相同的范式。受此观察的启发，我们探索了将 LoRA 和 KD 相结合的策略，以提高知识转移的效率。我们首先总结了这种设计的一些指导方针，并进一步开发了 LLM-Neo。在压缩 Llama 2 和 Llama 3 上的实验结果表明，LLM-Neo 优于各种基线。进一步的分析证明了所提出的 LLM-Neo 在 LoRA 变体上的稳健性。训练好的模型已在 \href{https://huggingface.co/collections/yang31210999/llm-neo-66e3c882f5579b829ff57eba}{此存储库} 中可用。

> In this paper, we propose a novel LLM-Neo framework that efficiently transfers knowledge from a large language model (LLM) teacher to a compact student. Initially, we revisit the knowledge distillation (KD) and low-rank adaption (LoRA), and argue that they share the same paradigm. Inspired by this observation, we explore the strategy that combines LoRA and KD to enhance the efficiency of knowledge transfer. We first summarize some guidelines for this design and further develop the LLM-Neo. Experimental results on compressing Llama 2 and Llama 3 show that LLM-Neo outperforms various baselines. Further analysis demonstrates the robustness of the proposed LLM-Neo on variants of LoRA. The trained models have been available at \href{https://huggingface.co/collections/yang31210999/llm-neo-66e3c882f5579b829ff57eba}{this repository}.

[Arxiv](https://arxiv.org/abs/2411.06839)