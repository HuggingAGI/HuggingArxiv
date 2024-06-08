# 情境学习具备重新掌握禁令任务的能力

发布时间：2024年02月08日

`Agent

理由：这篇论文主要探讨了情境学习（ICL）在大型语言模型（LLMs）中的应用，特别是在模型被设计为拒绝回答的“禁止任务”上的应用。研究关注的是ICL是否能够重新学习这些被拒绝的任务，并探讨了这种能力是否可能构成安全威胁。这种研究涉及到模型的行为和决策过程，更偏向于Agent的范畴，即研究模型如何作为智能体在特定情境下进行学习和决策。虽然涉及到LLM的应用，但其核心在于模型的行为和安全性，因此更适合归类为Agent。` `人工智能`

> In-Context Learning Can Re-learn Forbidden Tasks

# 摘要

> 尽管在安全培训上投入巨大，现实世界中的大型语言模型（LLMs）仍面临诸多安全漏洞。一种观点认为，LLM的安全培训通过算法禁止模型响应有害查询。本研究聚焦于模型被设计为拒绝回答的“禁止任务”，探讨情境学习（ICL）是否能在模型明确拒绝这些任务后，重新学习它们。我们通过拒绝情感分类的简单示例引入问题，随后在一个拒绝总结虚构新闻的模型上应用ICL。最后，我们探究ICL是否能逆转安全培训，这可能构成重大安全威胁。我们测试了Vicuna-7B、Starling-7B和Llama2-7B，发现ICL攻击对前两者有效，而对Llama2-7B无效。我们还提出了一种利用聊天模板令牌的新型ICL攻击，类似于提示注入，以提高在Vicuna-7B和Starling-7B上的攻击成功率。触发警告：附录包含涉及暴力、自杀和错误信息的LLM生成文本。

> Despite significant investment into safety training, large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training, in this work, we study forbidden tasks, i.e., tasks the model is designed to refuse to answer. Specifically, we investigate whether in-context learning (ICL) can be used to re-learn forbidden tasks despite the explicit fine-tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then, we use ICL on a model fine-tuned to refuse to summarise made-up news articles. Finally, we investigate whether ICL can undo safety training, which could represent a major security risk. For the safety task, we look at Vicuna-7B, Starling-7B, and Llama2-7B. We show that the attack works out-of-the-box on Starling-7B and Vicuna-7B but fails on Llama2-7B. Finally, we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna-7B and Starling-7B.
  Trigger Warning: the appendix contains LLM-generated text with violence, suicide, and misinformation.

[Arxiv](https://arxiv.org/abs/2402.05723)