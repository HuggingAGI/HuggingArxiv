# 并非所有投票都有效！通过程序验证，语言模型在数学推理中的自我一致性得以提升。

发布时间：2024年10月16日

`LLM应用` `软件开发`

> Not All Votes Count! Programs as Verifiers Improve Self-Consistency of Language Models for Math Reasoning

# 摘要

> 大型语言模型（LLM）在数学推理方面表现出色，但许多开源模型在推理过程中仍会犯计算和语义错误。为此，我们推出了 PROVE 框架，通过程序验证过滤潜在错误路径，而非简单多数投票。实验显示，PROVE 在多个模型和数据集上均优于传统方法，显著提升了准确率。例如，在 GSM8K 基准上，Qwen2-0.5B-Instruct 的准确率从 48.85% 提升至 53.83%，Llama-3.2-1B-Instruct 从 65.66% 提升至 73.01%，Gemma-2-2b-it 从 73.39% 提升至 79.61%，Llama-2-7B-chat 从 41.32% 提升至 59.51%。代码已开源，详见 https://github.com/declare-lab/prove。

> Large language models (LLMs) have shown increasing proficiency in solving mathematical reasoning problems. However, many current open-source LLMs often still make calculation and semantic understanding errors in their intermediate reasoning steps. In this work, we propose PROVE, a simple yet effective framework that uses program-based verification as a heuristic to filter out potentially incorrect reasoning paths before aggregating the final answers. Instead of relying on vanilla majority voting, our approach rejects solutions whose corresponding program outputs are inconsistent with the generated solution, aggregating only those validated by Python programs. We conducted extensive experiments on 13 open-source LLMs from various model families and sizes, ranging from 0.5B to 13B parameters, across seven math benchmarks. We demonstrate that PROVE consistently outperforms vanilla majority voting as a heuristic for solving mathematical reasoning tasks across all datasets and model sizes. Notably, PROVE increases accuracy on the GSM8K benchmark from 48.85% to 53.83% for Qwen2-0.5B-Instruct, from 65.66% to 73.01% for Llama-3.2-1B-Instruct, from 73.39% to 79.61% for Gemma-2-2b-it, and from 41.32% to 59.51% for Llama-2-7B-chat. Our codes are available at https://github.com/declare-lab/prove.

[Arxiv](https://arxiv.org/abs/2410.12608)