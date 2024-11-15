# MM-Eval：大型语言模型中现代蒙古语评估的分层式基准

发布时间：2024年11月14日

`LLM应用` `蒙古语`

> MM-Eval: A Hierarchical Benchmark for Modern Mongolian Evaluation in LLMs

# 摘要

> 大型语言模型（LLMs）在高资源语言领域表现优异，然而在诸如蒙古语这类低资源语言中却遭遇显著挑战。本文把能力划分为语言能力（语法和语义）与认知能力（知识和推理）来应对这些难题。为系统评估这些方面，我们开发了 MM-Eval，这是一个基于《现代蒙古语教材 I》，并融合了 WebQSP 和 MGSM 数据集的专门数据集。对 Qwen2-7B-Instruct、GLM4-9b-chat、Llama3.1-8B-Instruct、GPT-4 以及 DeepseekV2.5 等模型开展的初步实验显示：1）所有模型在语法任务上的表现均优于语义任务，凸显出在更深入语言理解方面存在差距；2）知识任务呈现出适度下滑，表明模型能够将一般知识从高资源情境转移至低资源情境。MM-Eval 发布了，涵盖 569 个语法、677 个语义、344 个知识和 250 个推理任务，为在像蒙古语这样的低资源语言中推动自然语言处理和大型语言模型发展提供了宝贵的思路。该数据集可在 https://github.com/joenahm/MM-Eval 获取。

> Large language models (LLMs) excel in high-resource languages but face notable challenges in low-resource languages like Mongolian. This paper addresses these challenges by categorizing capabilities into language abilities (syntax and semantics) and cognitive abilities (knowledge and reasoning). To systematically evaluate these areas, we developed MM-Eval, a specialized dataset based on Modern Mongolian Language Textbook I and enriched with WebQSP and MGSM datasets.
  Preliminary experiments on models including Qwen2-7B-Instruct, GLM4-9b-chat, Llama3.1-8B-Instruct, GPT-4, and DeepseekV2.5 revealed that: 1) all models performed better on syntactic tasks than semantic tasks, highlighting a gap in deeper language understanding; and 2) knowledge tasks showed a moderate decline, suggesting that models can transfer general knowledge from high-resource to low-resource contexts.
  The release of MM-Eval, comprising 569 syntax, 677 semantics, 344 knowledge, and 250 reasoning tasks, offers valuable insights for advancing NLP and LLMs in low-resource languages like Mongolian. The dataset is available at https://github.com/joenahm/MM-Eval.

[Arxiv](https://arxiv.org/abs/2411.09492)