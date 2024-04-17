# 评估代码生成中提示的质量

发布时间：2024年04月15日

`LLM应用` `软件工程` `编程语言`

> Quality Assessment of Prompts Used in Code Generation

# 摘要

> 大型语言模型（LLMs）正逐渐受到软件工程师的青睐。要构建高效的代码生成LLMs，关键在于通过严格的基准测试来评估这些模型。质量欠佳的评估基准可能会导致对性能的误判。在本项研究中，我们首次深入探讨了用于评估不同代码生成模型性能的基准测试中提示的质量问题。为此，我们对9个代码生成基准中的3,566个提示进行了分析，以识别存在的质量问题。我们还研究了修正这些基准提示中的质量问题是否会对模型性能产生影响。此外，我们还探讨了评估数据集的记忆问题，这可能会质疑基准测试的可信度。研究发现，代码生成评估基准主要集中在Python语言和编程练习上，且对模型的上下文依赖性挑战有限。这些数据集及开发者的提示存在诸如拼写和语法错误、表达意图不清晰、文档风格不当等质量问题。修正这些问题可以提升Python代码生成的性能，但对Java代码生成的提升并不显著。我们还发现了GPT-3.5-Turbo和CodeGen-2.5模型可能存在数据污染的迹象。

> Large Language Models (LLMs) are gaining popularity among software engineers. A crucial aspect of developing effective code-generation LLMs is to evaluate these models using a robust benchmark. Evaluation benchmarks with quality issues can provide a false sense of performance. In this work, we conduct the first-of-its-kind study of the quality of prompts within benchmarks used to compare the performance of different code generation models. To conduct this study, we analyzed 3,566 prompts from 9 code generation benchmarks to identify quality issues in them. We also investigated whether fixing the identified quality issues in the benchmarks' prompts affects a model's performance. We also studied memorization issues of the evaluation dataset, which can put into question a benchmark's trustworthiness. We found that code generation evaluation benchmarks mainly focused on Python and coding exercises and had very limited contextual dependencies to challenge the model. These datasets and the developers' prompts suffer from quality issues like spelling and grammatical errors, unclear sentences to express developers' intent, and not using proper documentation style. Fixing all these issues in the benchmarks can lead to a better performance for Python code generation, but not a significant improvement was observed for Java code generation. We also found evidence that GPT-3.5-Turbo and CodeGen-2.5 models possibly have data contamination issues.

[Arxiv](https://arxiv.org/abs/2404.10155)