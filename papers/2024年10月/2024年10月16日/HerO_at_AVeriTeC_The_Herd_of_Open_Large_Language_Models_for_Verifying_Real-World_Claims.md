# HerO 在 AVeriTeC：一群用于验证现实声明的开源大型语言模型

发布时间：2024年10月16日

`LLM应用` `事实核查` `人工智能`

> HerO at AVeriTeC: The Herd of Open Large Language Models for Verifying Real-World Claims

# 摘要

> 我们为 FEVER-24 主办的 AVeriTeC 任务设计了一个仅使用公开 LLM 的自动化事实核查系统——HerO。HerO 在每一步都整合多个 LLM，通过生成假设文档增强查询，并利用上下文样本提示预训练和微调的 LLM 进行问题生成和真实性预测。HerO 以 0.57 的 AVeriTeC 得分位列排行榜第二，展示了开放 LLM 在验证现实声明中的潜力。未来研究代码已公开在 https://github.com/ssu-humane/HerO。

> To tackle the AVeriTeC shared task hosted by the FEVER-24, we introduce a system that only employs publicly available large language models (LLMs) for each step of automated fact-checking, dubbed the Herd of Open LLMs for verifying real-world claims (HerO). HerO employs multiple LLMs for each step of automated fact-checking. For evidence retrieval, a language model is used to enhance a query by generating hypothetical fact-checking documents. We prompt pretrained and fine-tuned LLMs for question generation and veracity prediction by crafting prompts with retrieved in-context samples. HerO achieved 2nd place on the leaderboard with the AVeriTeC score of 0.57, suggesting the potential of open LLMs for verifying real-world claims. For future research, we make our code publicly available at https://github.com/ssu-humane/HerO.

[Arxiv](https://arxiv.org/abs/2410.12377)