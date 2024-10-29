# M2rc-Eval：大规模多语言存储库级代码完成评估

发布时间：2024年10月28日

`LLM应用` `软件工程` `编程语言`

> M2rc-Eval: Massively Multilingual Repository-level Code Completion Evaluation

# 摘要

> 仓库级代码补全在软件工程中引起了极大的关注，并且已经引入了几个基准数据集。然而，现有的仓库级代码补全基准通常只关注有限数量的语言（<5），这无法评估现有代码大型语言模型（LLM）在不同语言中的通用代码智能能力。此外，现有的基准通常报告不同语言的总体平均分数，其中不同补全场景中的细粒度能力被忽略了。因此，为了促进多语言场景中代码 LLM 的研究，我们提出了一个涵盖 18 种编程语言的大规模多语言仓库级代码补全基准（称为 M2RC-EVAL），并提供了两种不同补全场景的细粒度注释（即桶级和语义级），我们基于解析的抽象语法树获得这些注释。此外，我们还整理了一个大规模的多语言指令语料库 M2RC-INSTRUCT 数据集，以提高现有代码 LLM 的仓库级代码补全能力。综合实验结果证明了我们的 M2RC-EVAL 和 M2RC-INSTRUCT 的有效性。

> Repository-level code completion has drawn great attention in software engineering, and several benchmark datasets have been introduced. However, existing repository-level code completion benchmarks usually focus on a limited number of languages (<5), which cannot evaluate the general code intelligence abilities across different languages for existing code Large Language Models (LLMs). Besides, the existing benchmarks usually report overall average scores of different languages, where the fine-grained abilities in different completion scenarios are ignored. Therefore, to facilitate the research of code LLMs in multilingual scenarios, we propose a massively multilingual repository-level code completion benchmark covering 18 programming languages (called M2RC-EVAL), and two types of fine-grained annotations (i.e., bucket-level and semantic-level) on different completion scenarios are provided, where we obtain these annotations based on the parsed abstract syntax tree. Moreover, we also curate a massively multilingual instruction corpora M2RC- INSTRUCT dataset to improve the repository-level code completion abilities of existing code LLMs. Comprehensive experimental results demonstrate the effectiveness of our M2RC-EVAL and M2RC-INSTRUCT.

[Arxiv](https://arxiv.org/abs/2410.21157)