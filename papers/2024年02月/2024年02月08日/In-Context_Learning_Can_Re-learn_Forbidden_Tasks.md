# 情境学习具备重新掌握禁令任务的能力

发布时间：2024年02月08日

`Agent

这篇论文主要探讨了情境学习（ICL）在大型语言模型（LLMs）中的应用，特别是在模型被设计为拒绝回答某些任务（“禁止任务”）后的重新激活能力。研究通过特定的实验和模型测试，分析了ICL是否能够逆转安全培训，并提出了利用聊天模板令牌的ICL攻击方法。这一研究关注的是如何通过特定的技术手段（如ICL）来影响或改变模型的行为，这更符合Agent类别的定义，即关注模型如何响应和适应外部环境或输入的变化。` `安全培训` `人工智能安全`

> In-Context Learning Can Re-learn Forbidden Tasks

# 摘要

> 尽管在安全培训上投入巨大，现实世界中的大型语言模型（LLMs）仍面临诸多安全漏洞。一种安全培训策略是通过算法禁止LLMs回应有害查询。本研究聚焦于这些被设计为拒绝回答的“禁止任务”，探讨情境学习（ICL）是否能在模型明确拒绝这些任务后，重新激活它们。我们通过拒绝情感分类的示例引入问题，并在拒绝虚构新闻摘要的模型上应用ICL。进一步，我们探究ICL是否能逆转安全培训，这可能构成重大安全威胁。我们测试了Vicuna-7B、Starling-7B和Llama2-7B，发现ICL攻击对前两者有效，而对后者无效。最后，我们提出一种利用聊天模板令牌的ICL攻击，类似于提示注入，以提高在Vicuna-7B和Starling-7B上的攻击成功率。触发警告：附录包含涉及暴力、自杀和错误信息的LLM生成文本。

> Despite significant investment into safety training, large language models (LLMs) deployed in the real world still suffer from numerous vulnerabilities. One perspective on LLM safety training is that it algorithmically forbids the model from answering toxic or harmful queries. To assess the effectiveness of safety training, in this work, we study forbidden tasks, i.e., tasks the model is designed to refuse to answer. Specifically, we investigate whether in-context learning (ICL) can be used to re-learn forbidden tasks despite the explicit fine-tuning of the model to refuse them. We first examine a toy example of refusing sentiment classification to demonstrate the problem. Then, we use ICL on a model fine-tuned to refuse to summarise made-up news articles. Finally, we investigate whether ICL can undo safety training, which could represent a major security risk. For the safety task, we look at Vicuna-7B, Starling-7B, and Llama2-7B. We show that the attack works out-of-the-box on Starling-7B and Vicuna-7B but fails on Llama2-7B. Finally, we propose an ICL attack that uses the chat template tokens like a prompt injection attack to achieve a better attack success rate on Vicuna-7B and Starling-7B.
  Trigger Warning: the appendix contains LLM-generated text with violence, suicide, and misinformation.

[Arxiv](https://arxiv.org/abs/2402.05723)