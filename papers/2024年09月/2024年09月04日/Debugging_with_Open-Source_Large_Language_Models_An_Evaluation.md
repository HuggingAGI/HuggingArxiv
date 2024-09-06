# 开源大型语言模型调试评估

发布时间：2024年09月04日

`LLM应用` `软件开发` `人工智能`

> Debugging with Open-Source Large Language Models: An Evaluation

# 摘要

> 大型语言模型在软件开发中展现出巨大潜力，越来越多的开发者借助 LLMs（如 ChatGPT）来修复代码缺陷。尽管这能节省时间和精力，但严格的代码共享政策使得许多公司禁止使用。为解决这一问题，公司可在本地运行开源 LLMs。然而，目前关于开源 LLMs 在调试中的表现研究甚少。本研究首次评估了开源 LLMs 在修复代码缺陷方面的能力，涵盖五个模型，并采用包含 4000 多个 Python、Java 和 C++ 代码缺陷实例的 DebugBench 基准。结果显示，开源 LLMs 的修复成功率在 43.9% 至 66.6% 之间，其中 DeepSeek-Coder 在三种语言中均表现最佳。

> Large language models have shown good potential in supporting software development tasks. This is why more and more developers turn to LLMs (e.g. ChatGPT) to support them in fixing their buggy code. While this can save time and effort, many companies prohibit it due to strict code sharing policies. To address this, companies can run open-source LLMs locally. But until now there is not much research evaluating the performance of open-source large language models in debugging. This work is a preliminary evaluation of the capabilities of open-source LLMs in fixing buggy code. The evaluation covers five open-source large language models and uses the benchmark DebugBench which includes more than 4000 buggy code instances written in Python, Java and C++. Open-source LLMs achieved scores ranging from 43.9% to 66.6% with DeepSeek-Coder achieving the best score for all three programming languages.

[Arxiv](https://arxiv.org/abs/2409.03031)