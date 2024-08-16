# I-SHEEP：借助迭代自我增强范式，从零开始逐步实现 LLM 的自我对齐

发布时间：2024年08月15日

`LLM理论` `人工智能` `软件开发`

> I-SHEEP: Self-Alignment of LLM from Scratch through an Iterative Self-Enhancement Paradigm

# 摘要

> 大型语言模型（LLM）虽有显著进步，但传统学习模式仅视其为被动信息库，忽略了其主动学习和自我对齐的潜能。本文提出**I-SHEEP**，一种迭代自我增强范式，使LLM能从零开始持续自我对齐，超越了一次性对齐方法Dromedary。在Qwen和Llama模型上，I-SHEEP在Alpaca Eval中提升78.2%，在MT Bench中提升24.0%，在Qwen-1.5 72B模型的IFEval准确性上提升8.88%。此外，I-SHEEP在代码生成任务中平均提升24.77%，在TrivialQA中提升12.04%，在SQuAD中提升20.29%。实验结果带来新见解，相关代码、数据集和模型已公开。

> Large Language Models (LLMs) have achieved significant advancements, however, the common learning paradigm treats LLMs as passive information repositories, neglecting their potential for active learning and alignment. Some approaches train LLMs using their own generated synthetic data, exploring the possibility of active alignment. However, there is still a huge gap between these one-time alignment methods and the continuous automatic alignment of humans. In this paper, we introduce \textbf{I-SHEEP}, an \textbf{I}terative \textbf{S}elf-En\textbf{H}anc\textbf{E}m\textbf{E}nt \textbf{P}aradigm.This human-like paradigm enables LLMs to \textbf{continuously self-align from scratch with nothing}. Compared to the one-time alignment method Dromedary \cite{sun2023principledriven}, which refers to the first iteration in this paper, I-SHEEP can significantly enhance capacities on both Qwen and Llama models. I-SHEEP achieves a maximum relative improvement of 78.2\% in the Alpaca Eval, 24.0\% in the MT Bench, and an absolute increase of 8.88\% in the IFEval accuracy over subsequent iterations in Qwen-1.5 72B model. Additionally, I-SHEEP surpasses the base model in various standard benchmark generation tasks, achieving an average improvement of 24.77\% in code generation tasks, 12.04\% in TrivialQA, and 20.29\% in SQuAD. We also provide new insights based on the experiment results. Our codes, datasets, and models are available at \textbf{https://anonymous.4open.science/r/I-SHEEP}.

[Arxiv](https://arxiv.org/abs/2408.08072)