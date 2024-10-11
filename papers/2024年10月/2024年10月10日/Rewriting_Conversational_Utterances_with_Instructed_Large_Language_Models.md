# 借助指导性大型语言模型，对话话语得以重塑。

发布时间：2024年10月10日

`LLM应用` `搜索引擎`

> Rewriting Conversational Utterances with Instructed Large Language Models

# 摘要

> 近期研究表明，LLM 在问答、文本摘要、编码和翻译等 NLP 任务中表现卓越，甚至媲美人类专家。其核心创新在于通过零-shot 或 few-shot 提示完成任务。本文探讨了指导性 LLM 如何通过重写对话中的用户问题来提升搜索效果。我们分析了哪些提示能生成最具信息量的重写话语，从而优化检索性能。实验结果显示，指导性 LLM 在 MRR、Precision@1、NDCG@3 和 Recall@500 等指标上分别提升了 25.2%、31.7%、27% 和 11.5%，显著超越现有技术。

> Many recent studies have shown the ability of large language models (LLMs) to achieve state-of-the-art performance on many NLP tasks, such as question answering, text summarization, coding, and translation. In some cases, the results provided by LLMs are on par with those of human experts. These models' most disruptive innovation is their ability to perform tasks via zero-shot or few-shot prompting. This capability has been successfully exploited to train instructed LLMs, where reinforcement learning with human feedback is used to guide the model to follow the user's requests directly. In this paper, we investigate the ability of instructed LLMs to improve conversational search effectiveness by rewriting user questions in a conversational setting. We study which prompts provide the most informative rewritten utterances that lead to the best retrieval performance. Reproducible experiments are conducted on publicly-available TREC CAST datasets. The results show that rewriting conversational utterances with instructed LLMs achieves significant improvements of up to 25.2% in MRR, 31.7% in Precision@1, 27% in NDCG@3, and 11.5% in Recall@500 over state-of-the-art techniques.

[Arxiv](https://arxiv.org/abs/2410.07797)