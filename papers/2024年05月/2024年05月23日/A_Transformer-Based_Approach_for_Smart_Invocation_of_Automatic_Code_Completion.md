# 基于Transformer的智能调用自动代码补全方法

发布时间：2024年05月23日

`Agent

理由：这篇论文主要描述了一种机器学习模型，该模型能够根据代码上下文和遥测数据来判断何时调用代码补全工具。这种模型可以被视为一个智能代理（Agent），因为它能够自主地做出决策并执行任务（即在适当的时机提供代码补全建议）。此外，论文中提到的模型部署和实际应用验证也强调了其在实际环境中的代理功能。因此，这篇论文更适合归类为Agent。` `软件开发` `机器学习`

> A Transformer-Based Approach for Smart Invocation of Automatic Code Completion

# 摘要

> 基于Transformer的语言模型在代码补全上表现出色，但它们的高成本和潜在干扰性，尤其是在频繁打断开发者时，不容忽视。现有研究往往忽略了这些模型与开发者实际互动的细节，也未明确何时提供补全建议。为此，我们研发了一种机器学习模型，它能根据代码上下文和遥测数据精准判断调用代码补全工具的最佳时机。我们收集了200,000次开发者与跨IDE插件的互动数据，并训练了多个调用过滤模型。实验表明，我们的小型Transformer模型不仅超越了基准，而且延迟极低。我们还尝试将更多遥测数据直接融入预训练模型，取得了积极进展。为了验证其实际应用价值，我们在线上环境中部署了该模型，覆盖了34名开发者，并基于74,000次实际调用，提供了宝贵的实战洞察。

> Transformer-based language models are highly effective for code completion, with much research dedicated to enhancing the content of these completions. Despite their effectiveness, these models come with high operational costs and can be intrusive, especially when they suggest too often and interrupt developers who are concentrating on their work. Current research largely overlooks how these models interact with developers in practice and neglects to address when a developer should receive completion suggestions. To tackle this issue, we developed a machine learning model that can accurately predict when to invoke a code completion tool given the code context and available telemetry data.
  To do so, we collect a dataset of 200k developer interactions with our cross-IDE code completion plugin and train several invocation filtering models. Our results indicate that our small-scale transformer model significantly outperforms the baseline while maintaining low enough latency. We further explore the search space for integrating additional telemetry data into a pre-trained transformer directly and obtain promising results. To further demonstrate our approach's practical potential, we deployed the model in an online environment with 34 developers and provided real-world insights based on 74k actual invocations.

[Arxiv](https://arxiv.org/abs/2405.14753)