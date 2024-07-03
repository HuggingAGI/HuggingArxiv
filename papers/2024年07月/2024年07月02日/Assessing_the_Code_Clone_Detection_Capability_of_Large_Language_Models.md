# 探究大型语言模型在代码克隆检测方面的能力

发布时间：2024年07月02日

`LLM应用` `软件工程` `人工智能`

> Assessing the Code Clone Detection Capability of Large Language Models

# 摘要

> 本研究评估了 GPT-3.5 和 GPT-4 在代码克隆检测中的表现，发现 GPT-4 在所有克隆类型上均优于 GPT-3.5。研究还揭示了 GPT 模型在识别复杂 Type-4 克隆时的不足，以及在处理 LLM 生成代码时相对较高的性能。尽管如此，GPT 模型的准确性仍有待提高。这些发现强调了 LLM 在代码克隆识别和避免自我生成克隆方面的持续改进需求，特别是在软件工程师广泛使用 LLM 辅助工具的背景下。

> This study aims to assess the performance of two advanced Large Language Models (LLMs), GPT-3.5 and GPT-4, in the task of code clone detection. The evaluation involves testing the models on a variety of code pairs of different clone types and levels of similarity, sourced from two datasets: BigCloneBench (human-made) and GPTCloneBench (LLM-generated). Findings from the study indicate that GPT-4 consistently surpasses GPT-3.5 across all clone types. A correlation was observed between the GPTs' accuracy at identifying code clones and code similarity, with both GPT models exhibiting low effectiveness in detecting the most complex Type-4 code clones. Additionally, GPT models demonstrate a higher performance identifying code clones in LLM-generated code compared to humans-generated code. However, they do not reach impressive accuracy. These results emphasize the imperative for ongoing enhancements in LLM capabilities, particularly in the recognition of code clones and in mitigating their predisposition towards self-generated code clones--which is likely to become an issue as software engineers are more numerous to leverage LLM-enabled code generation and code refactoring tools.

[Arxiv](https://arxiv.org/abs/2407.02402)