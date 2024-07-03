# 大型语言模型文本标注中的提示稳定性评分

发布时间：2024年07月02日

`LLM应用` `文本标注` `软件开发`

> Prompt Stability Scoring for Text Annotation with Large Language Models

# 摘要

> 研究人员正越来越多地利用语言模型进行文本标注，这些方法仅依赖于一个提示来指导模型输出。然而，提示设计的微小变化可能影响输出的可重复性，从而引发对分类程序可复制性的质疑。为应对这一挑战，我们提出了一种通用框架，通过调整传统可靠性评分方法来评估提示稳定性，并命名为提示稳定性得分 (PSS)。我们开发的 Python 包 PromptStability 可用于此评估。通过分析六个数据集和十二个结果，我们对超过 15 万行数据进行了分类，旨在揭示提示稳定性的不足并展示该包的实用性。最后，我们为应用研究人员提供了最佳实践建议。

> Researchers are increasingly using language models (LMs) for text annotation. These approaches rely only on a prompt telling the model to return a given output according to a set of instructions. The reproducibility of LM outputs may nonetheless be vulnerable to small changes in the prompt design. This calls into question the replicability of classification routines. To tackle this problem, researchers have typically tested a variety of semantically similar prompts to determine what we call "prompt stability." These approaches remain ad-hoc and task specific. In this article, we propose a general framework for diagnosing prompt stability by adapting traditional approaches to intra- and inter-coder reliability scoring. We call the resulting metric the Prompt Stability Score (PSS) and provide a Python package PromptStability for its estimation. Using six different datasets and twelve outcomes, we classify >150k rows of data to: a) diagnose when prompt stability is low; and b) demonstrate the functionality of the package. We conclude by providing best practice recommendations for applied researchers.

[Arxiv](https://arxiv.org/abs/2407.02039)