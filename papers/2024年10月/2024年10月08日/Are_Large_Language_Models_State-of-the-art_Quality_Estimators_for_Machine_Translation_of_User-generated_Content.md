# 大型语言模型能否成为用户生成内容机器翻译的顶尖质量评估工具？

发布时间：2024年10月08日

`LLM应用` `社交媒体`

> Are Large Language Models State-of-the-art Quality Estimators for Machine Translation of User-generated Content?

# 摘要

> 本文探讨了 LLM 是否能成为无需参考翻译的 UGC 机器翻译质量评估器，特别是针对包含情感表达的内容。我们利用一个带有情感标注错误的数据集，通过多维质量指标计算评估分数，并在 in-context learning 和 PEFT 场景下，对比了 LLM 与微调基线模型的准确性。结果显示，LLM 的 PEFT 在预测分数和提供可解释性方面表现更佳，但手动分析发现，LLM 在处理 UGC 机器翻译时仍存在拒绝回复和不稳定输出的问题。

> This paper investigates whether large language models (LLMs) are state-of-the-art quality estimators for machine translation of user-generated content (UGC) that contains emotional expressions, without the use of reference translations. To achieve this, we employ an existing emotion-related dataset with human-annotated errors and calculate quality evaluation scores based on the Multi-dimensional Quality Metrics. We compare the accuracy of several LLMs with that of our fine-tuned baseline models, under in-context learning and parameter-efficient fine-tuning (PEFT) scenarios. We find that PEFT of LLMs leads to better performance in score prediction with human interpretable explanations than fine-tuned models. However, a manual analysis of LLM outputs reveals that they still have problems such as refusal to reply to a prompt and unstable output while evaluating machine translation of UGC.

[Arxiv](https://arxiv.org/abs/2410.06338)