# LLM-IE：一个可借助大型语言模型实现生成式信息提取的 Python 包

发布时间：2024年11月18日

`LLM应用` `生物医学`

> LLM-IE: A Python Package for Generative Information Extraction with Large Language Models

# 摘要

> 目标：虽然近来大型语言模型（LLMs）已用于生物医学信息提取，然而在提示工程和算法方面仍存在挑战，且尚无专用软件。为此，我们开发了 LLM-IE ：一个用于构建完整信息提取管道的 Python 包。其关键创新在于一个交互式 LLM 代理，用于支持模式定义和提示设计。
  材料与方法：LLM-IE 支持命名实体识别、实体属性提取和关系提取任务。我们在 i2b2 数据集上进行了基准测试，并开展了系统评估。
  结果：基于句子的提示算法表现最优，但推理时间较长。系统评估提供了直观的可视化效果。
  讨论：LLM-IE 依据医疗保健中的实际 NLP 经验设计，已在内部项目中得到应用。它对于生物医学 NLP 领域应具有重大价值。
  结论：我们开发了 Python 包 LLM-IE ，为构建强大的信息提取管道提供了基础模块。

> Objectives: Despite the recent adoption of large language models (LLMs) for biomedical information extraction, challenges in prompt engineering and algorithms persist, with no dedicated software available. To address this, we developed LLM-IE: a Python package for building complete information extraction pipelines. Our key innovation is an interactive LLM agent to support schema definition and prompt design.
  Materials and Methods: The LLM-IE supports named entity recognition, entity attribute extraction, and relation extraction tasks. We benchmarked on the i2b2 datasets and conducted a system evaluation.
  Results: The sentence-based prompting algorithm resulted in the best performance while requiring a longer inference time. System evaluation provided intuitive visualization.
  Discussion: LLM-IE was designed from practical NLP experience in healthcare and has been adopted in internal projects. It should hold great value to the biomedical NLP community.
  Conclusion: We developed a Python package, LLM-IE, that provides building blocks for robust information extraction pipeline construction.

[Arxiv](https://arxiv.org/abs/2411.11779)