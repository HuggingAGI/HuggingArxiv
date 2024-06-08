# 情境学习法能够突破限制，重新掌握被禁任务

发布时间：2024年02月08日

`Agent

理由：这篇论文主要探讨了情境学习（ICL）如何可能绕过大型语言模型（LLMs）的安全培训，特别是针对那些被设计为拒绝回答特定任务的模型。研究通过实验评估了ICL是否能解除安全培训，并提出了新的攻击方法。这种研究更偏向于Agent的行为和策略，即如何操作和影响LLMs以达到特定目的，而不是专注于LLM的理论研究或应用开发。因此，将其归类为Agent是合适的。` `安全培训` `人工智能安全`

> In-Context Learning Can Re-learn Forbidden Tasks

# 摘要

> 尽管在安全培训上投入巨大，现实世界中的大型语言模型（LLMs）仍面临诸多安全漏洞。一种安全培训策略是通过算法禁止LLMs回答有害查询。本研究聚焦于这些被设计为拒绝回答的“禁止任务”，并探讨了情境学习（ICL）是否能绕过模型的拒绝机制，重新学习这些任务。我们通过拒绝情感分类的简单示例引入问题，并在一个拒绝总结虚构新闻的模型上实施ICL。进一步，我们评估了ICL是否能解除安全培训，这可能构成重大安全威胁。我们测试了Vicuna-7B、Starling-7B和Llama2-7B，发现ICL攻击对前两者有效，而对Llama2-7B无效。最后，我们提出了一种利用聊天模板令牌的ICL攻击，类似于提示注入，以提高对Vicuna-7B和Starling-7B的攻击成功率。触发警告：附录包含涉及暴力、自杀和错误信息的LLM生成文本。

> Despite significant investment into safety training, large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training, in this work, we study forbidden tasks, i.e., tasks the model is designed to refuse to answer. Specifically, we investigate whether in-context learning (ICL) can be used to re-learn forbidden tasks despite the explicit fine-tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then, we use ICL on a model fine-tuned to refuse to summarise made-up news articles. Finally, we investigate whether ICL can undo safety training, which could represent a major security risk. For the safety task, we look at Vicuna-7B, Starling-7B, and Llama2-7B. We show that the attack works out-of-the-box on Starling-7B and Vicuna-7B but fails on Llama2-7B. Finally, we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna-7B and Starling-7B.
  Trigger Warning: the appendix contains LLM-generated text with violence, suicide, and misinformation.

[Arxiv](https://arxiv.org/abs/2402.05723)