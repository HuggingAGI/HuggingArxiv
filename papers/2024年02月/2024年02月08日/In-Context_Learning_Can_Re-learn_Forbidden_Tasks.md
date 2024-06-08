# 情境学习具备重新掌握禁令任务的能力

发布时间：2024年02月08日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在安全培训后仍可能存在的安全漏洞，特别是通过情境学习（ICL）是否能使模型重新学习被禁止的任务。研究通过具体的实验和案例分析，评估了不同模型的安全性能，并提出了一种新型的ICL攻击方法。这些内容主要关注于LLMs的实际应用中的安全问题，因此属于LLM应用分类。` `安全培训` `人工智能安全`

> In-Context Learning Can Re-learn Forbidden Tasks

# 摘要

> 尽管在安全培训上投入巨大，现实世界中的大型语言模型（LLMs）仍面临诸多安全漏洞。一种安全培训策略是通过算法禁止LLMs响应有害查询。本研究聚焦于这些“禁止任务”，探究即使模型经过微调以拒绝这些任务，情境学习（ICL）是否能使其重新学习。我们通过拒绝情感分类的简单示例引入问题，随后在一个拒绝总结虚构新闻的模型上应用ICL。最终，我们探讨ICL是否能颠覆安全培训，这可能构成重大安全威胁。我们测试了Vicuna-7B、Starling-7B和Llama2-7B，发现ICL攻击对前两者有效，但对Llama2-7B无效。我们还提出了一种利用聊天模板令牌的新型ICL攻击，提高了对Vicuna-7B和Starling-7B的攻击成功率。触发警告：附录包含涉及暴力、自杀和错误信息的LLM生成文本。

> Despite significant investment into safety training, large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training, in this work, we study forbidden tasks, i.e., tasks the model is designed to refuse to answer. Specifically, we investigate whether in-context learning (ICL) can be used to re-learn forbidden tasks despite the explicit fine-tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then, we use ICL on a model fine-tuned to refuse to summarise made-up news articles. Finally, we investigate whether ICL can undo safety training, which could represent a major security risk. For the safety task, we look at Vicuna-7B, Starling-7B, and Llama2-7B. We show that the attack works out-of-the-box on Starling-7B and Vicuna-7B but fails on Llama2-7B. Finally, we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna-7B and Starling-7B.
  Trigger Warning: the appendix contains LLM-generated text with violence, suicide, and misinformation.

[Arxiv](https://arxiv.org/abs/2402.05723)