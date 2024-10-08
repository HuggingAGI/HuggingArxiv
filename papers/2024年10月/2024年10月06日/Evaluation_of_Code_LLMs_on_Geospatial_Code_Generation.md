# 评估代码大型语言模型在地理空间代码生成中的表现

发布时间：2024年10月06日

`LLM应用` `软件开发` `地理空间数据科学`

> Evaluation of Code LLMs on Geospatial Code Generation

# 摘要

> 软件开发支持工具的研究历史悠久，近年来，大型语言模型（LLM）被用于代码生成，尤其擅长生成数据科学和机器学习应用的Python代码。LLM不仅提升了软件工程师的日常工作效率，还能作为新手开发者的“导师”，提供学习支持。在地理空间数据科学领域，高质量的代码生成同样具有潜力，但该领域带来了独特的挑战，现有的代码生成LLM通常未在此类任务上进行评估。为此，我们构建了一个基于地理空间任务的代码生成模型评估基准。我们根据任务的复杂性和所需工具对地理空间任务进行了分类，并创建了一个包含空间推理、数据处理和工具使用测试任务的数据集。每个问题都配有自动检查代码正确性的测试场景。此外，我们还测试了现有LLM在地理空间领域的代码生成能力。我们在GitHub上公开了数据集和评估代码，期待这些资源能成为未来LLM评估的基准，推动开发出更精准解决地理空间编码任务的新模型，进而打造专为地理空间应用定制的编码助手。

> Software development support tools have been studied for a long time, with recent approaches using Large Language Models (LLMs) for code generation. These models can generate Python code for data science and machine learning applications. LLMs are helpful for software engineers because they increase productivity in daily work. An LLM can also serve as a "mentor" for inexperienced software developers, and be a viable learning support. High-quality code generation with LLMs can also be beneficial in geospatial data science. However, this domain poses different challenges, and code generation LLMs are typically not evaluated on geospatial tasks. Here, we show how we constructed an evaluation benchmark for code generation models, based on a selection of geospatial tasks. We categorised geospatial tasks based on their complexity and required tools. Then, we created a dataset with tasks that test model capabilities in spatial reasoning, spatial data processing, and geospatial tools usage. The dataset consists of specific coding problems that were manually created for high quality. For every problem, we proposed a set of test scenarios that make it possible to automatically check the generated code for correctness. In addition, we tested a selection of existing code generation LLMs for code generation in the geospatial domain. We share our dataset and reproducible evaluation code on a public GitHub repository, arguing that this can serve as an evaluation benchmark for new LLMs in the future. Our dataset will hopefully contribute to the development new models capable of solving geospatial coding tasks with high accuracy. These models will enable the creation of coding assistants tailored for geospatial applications.

[Arxiv](https://arxiv.org/abs/2410.04617)