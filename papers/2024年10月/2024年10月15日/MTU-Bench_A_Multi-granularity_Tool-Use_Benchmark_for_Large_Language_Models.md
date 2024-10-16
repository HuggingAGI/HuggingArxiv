# MTU-Bench：专为大型语言模型设计的多粒度工具使用基准

发布时间：2024年10月15日

`LLM应用` `人工智能` `软件开发`

> MTU-Bench: A Multi-granularity Tool-Use Benchmark for Large Language Models

# 摘要

> 大型语言模型 (LLM) 在推理和决策方面取得了显著进展，并能与用户进行自然对话。然而，现有的工具使用基准数据集存在评估场景不足和成本高昂的问题。为此，我们推出了 MTU-Bench，一个多粒度的工具使用基准，涵盖了五种工具使用场景。所有评估均基于预测结果和真实值，无需 GPT 或人工评估。MTU-Bench 通过转换高质量数据集来模拟真实场景，并引入 MTU-Instruct 数据集以提升 LLM 的工具使用能力。实验结果显示了 MTU-Bench 的有效性。代码和数据将发布在 https: //github.com/MTU-Bench-Team/MTU-Bench.git。

> Large Language Models (LLMs) have displayed massive improvements in reasoning and decision-making skills and can hold natural conversations with users. Recently, many tool-use benchmark datasets have been proposed. However, existing datasets have the following limitations: (1). Insufficient evaluation scenarios (e.g., only cover limited tool-use scenes). (2). Extensive evaluation costs (e.g., GPT API costs). To address these limitations, in this work, we propose a multi-granularity tool-use benchmark for large language models called MTU-Bench. For the "multi-granularity" property, our MTU-Bench covers five tool usage scenes (i.e., single-turn and single-tool, single-turn and multiple-tool, multiple-turn and single-tool, multiple-turn and multiple-tool, and out-of-distribution tasks). Besides, all evaluation metrics of our MTU-Bench are based on the prediction results and the ground truth without using any GPT or human evaluation metrics. Moreover, our MTU-Bench is collected by transforming existing high-quality datasets to simulate real-world tool usage scenarios, and we also propose an instruction dataset called MTU-Instruct data to enhance the tool-use abilities of existing LLMs. Comprehensive experimental results demonstrate the effectiveness of our MTU-Bench. Code and data will be released at https: //github.com/MTU-Bench-Team/MTU-Bench.git.

[Arxiv](https://arxiv.org/abs/2410.11710)