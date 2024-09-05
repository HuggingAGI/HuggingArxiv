# 大型语言模型在日志解析中的比较研究

发布时间：2024年09月04日

`LLM应用` `软件工程` `人工智能`

> A Comparative Study on Large Language Models for Log Parsing

# 摘要

> 背景：日志消息是软件系统状态的关键信息源。这些信息通常以非结构化形式呈现，需要自动化方法提取相关参数。日志解析技术应运而生，将日志消息转化为结构化模板。近期，ChatGPT在日志解析任务中展现出潜力，但其他顶尖大型语言模型（LLM）在此任务上的表现尚不明朗。  目的：本研究旨在探究当前顶尖LLM在日志解析任务中的能力。  方法：我们选取了六种近期LLM，涵盖付费专有模型（如GPT-3.5、Claude 2.1）及四款免费开放模型，对比它们在多个成熟开源项目日志上的表现。我们设计了两种提示策略，并在16个项目的1,354个日志模板上测试了这些模型。评估指标包括正确识别的模板数量及生成模板与真实数据的句法相似度。  结果：研究发现，免费模型与付费模型不相上下，CodeLlama在正确提取日志模板方面甚至超越了GPT-3.5。此外，我们还探讨了这些模型的易用性。  结论：研究显示，某些小型免费LLM在日志解析方面能与付费模型匹敌，尤其是那些专注于代码处理的模型。

> Background: Log messages provide valuable information about the status of software systems. This information is provided in an unstructured fashion and automated approaches are applied to extract relevant parameters. To ease this process, log parsing can be applied, which transforms log messages into structured log templates. Recent advances in language models have led to several studies that apply ChatGPT to the task of log parsing with promising results. However, the performance of other state-of-the-art large language models (LLMs) on the log parsing task remains unclear.
  Aims: In this study, we investigate the current capability of state-of-the-art LLMs to perform log parsing.
  Method: We select six recent LLMs, including both paid proprietary (GPT-3.5, Claude 2.1) and four free-to-use open models, and compare their performance on system logs obtained from a selection of mature open-source projects. We design two different prompting approaches and apply the LLMs on 1, 354 log templates across 16 different projects. We evaluate their effectiveness, in the number of correctly identified templates, and the syntactic similarity between the generated templates and the ground truth.
  Results: We found that free-to-use models are able to compete with paid models, with CodeLlama extracting 10% more log templates correctly than GPT-3.5. Moreover, we provide qualitative insights into the usability of language models (e.g., how easy it is to use their responses).
  Conclusions: Our results reveal that some of the smaller, free-to-use LLMs can considerably assist log parsing compared to their paid proprietary competitors, especially code-specialized models.

[Arxiv](https://arxiv.org/abs/2409.02474)