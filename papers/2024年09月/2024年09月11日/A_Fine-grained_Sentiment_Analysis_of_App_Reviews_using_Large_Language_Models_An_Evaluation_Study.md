# 利用大型语言模型深入解析应用评论的情感：一项评估研究

发布时间：2024年09月11日

`LLM应用` `软件开发` `市场分析`

> A Fine-grained Sentiment Analysis of App Reviews using Large Language Models: An Evaluation Study

# 摘要

> 通过分析用户对应用功能的评论，我们可以深入了解用户的需求变化。面对海量的每日评论，自动生成情感摘要的机制显得尤为重要。尽管像ChatGPT这样的大型语言模型在无需更新参数的情况下已展现出卓越性能，但其在用户评论情感分析方面的潜力尚未被充分挖掘。本研究对比了GPT-4、ChatGPT及LLama-2-chat等模型在不同场景下的表现，发现GPT-4在零-shot特征提取中，其f1-score比传统方法高出23.6%，而5-shot场景下更提升了6%。此外，GPT-4在预测正面情感时，5-shot场景下的f1-score达到了74%，提升了7%。这些发现表明，LLM在生成用户评论情感摘要方面具有巨大潜力。

> Analyzing user reviews for sentiment towards app features can provide valuable insights into users' perceptions of app functionality and their evolving needs. Given the volume of user reviews received daily, an automated mechanism to generate feature-level sentiment summaries of user reviews is needed. Recent advances in Large Language Models (LLMs) such as ChatGPT have shown impressive performance on several new tasks without updating the model's parameters i.e. using zero or a few labeled examples. Despite these advancements, LLMs' capabilities to perform feature-specific sentiment analysis of user reviews remain unexplored. This study compares the performance of state-of-the-art LLMs, including GPT-4, ChatGPT, and LLama-2-chat variants, for extracting app features and associated sentiments under 0-shot, 1-shot, and 5-shot scenarios. Results indicate the best-performing GPT-4 model outperforms rule-based approaches by 23.6% in f1-score with zero-shot feature extraction; 5-shot further improving it by 6%. GPT-4 achieves a 74% f1-score for predicting positive sentiment towards correctly predicted app features, with 5-shot enhancing it by 7%. Our study suggests that LLM models are promising for generating feature-specific sentiment summaries of user reviews.

[Arxiv](https://arxiv.org/abs/2409.07162)