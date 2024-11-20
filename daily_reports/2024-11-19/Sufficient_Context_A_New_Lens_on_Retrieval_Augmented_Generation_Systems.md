# 足够的上下文：关于检索增强生成系统的新视角
发布时间：2024年11月08日

`RAG`
> Sufficient Context: A New Lens on Retrieval Augmented Generation Systems
>
> 在许多应用中，为大型语言模型（LLM）增加上下文会导致性能提升。尽管对检索增强生成（RAG）系统进行了大量研究，但一个悬而未决的问题是，错误是否是因为大型语言模型未能利用检索的上下文，还是因为上下文本身不足以回答查询。为了阐明这一点，我们提出了充分上下文的新概念，以及一种对有足够信息回答查询的实例进行分类的方法。然后，我们使用充分的上下文来分析几个模型和数据集。通过根据上下文的充分性对错误进行分层，我们发现专有大型语言模型（Gemini、GPT、Claude）在上下文充分时擅长回答查询，但当上下文不充分时，往往输出错误答案而不是弃权。另一方面，开源大型语言模型（Llama、Mistral、Gemma）即使在有足够上下文的情况下，也经常产生幻觉或弃权。我们进一步对上下文有用的情况进行分类，即使它不能完全回答查询并且模型在没有上下文时出错，也能提高准确性。基于我们的发现，我们探索了减少 RAG 系统中幻觉的方法，包括一种利用充分上下文信息进行引导弃权的新选择性生成方法。对于 Gemini、GPT 和 Gemma，我们的方法将模型回答正确的比例提高了 2 - 10%。
>
> https://arxiv.org/abs/2411.06037

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.06037](https://arxiv.org/abs/2411.06037)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)