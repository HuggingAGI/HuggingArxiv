# 长上下文中，少量样本学习能否奏效？利用上下文循环生成演示，探索其可能性。
发布时间：2024年06月19日

`提示工程`
> Can Few-shot Work in Long-Context? Recycling the Context to Generate Demonstrations
>
> 尽管大型语言模型（LLMs）近期有所进步，但在处理长上下文任务时，其性能仍未尽如人意。使用少量示例的上下文学习（ICL）可能是在这种情况下提升LLM性能的一个吸引人的解决方案；然而，简单地添加具有长上下文的ICL示例会带来挑战，包括每个少量示例增加的大量令牌开销以及演示与目标查询之间的上下文不匹配。为此，我们提出了一种新方法：通过循环利用上下文来自动生成用于长上下文问答任务的少量示例。具体而言，我们从一个长输入上下文（1-3k令牌）和一个查询出发，从该上下文中生成额外的查询-输出对作为少量示例，同时只引入一次上下文。这样，演示与目标查询共享同一上下文，同时仅向提示中添加少量令牌。此外，我们指导模型在回答前明确识别相关段落，以增强每个演示，这不仅提升了性能，还为答案来源提供了细粒度的归属。我们在多个LLMs上应用此方法，并在具有长上下文的各种问答数据集上取得了显著改进，尤其是在答案位于上下文中间时。令人惊讶的是，尽管只引入了单跳ICL示例，LLMs也能成功地使用我们的方法推广到多跳长上下文问答。
>
> https://arxiv.org/abs/2406.13632

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13632/gemini_oracle_lost.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13632/traditional_vs_ours.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13632/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13632/lost_2_self.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13632](https://arxiv.org/abs/2406.13632)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2