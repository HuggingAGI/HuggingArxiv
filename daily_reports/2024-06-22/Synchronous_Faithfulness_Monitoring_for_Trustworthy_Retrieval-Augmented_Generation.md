# 实时忠实度监控，确保检索增强生成的可靠性
发布时间：2024年06月19日

`RAG`
> Synchronous Faithfulness Monitoring for Trustworthy Retrieval-Augmented Generation
>
> 检索增强型语言模型（RALMs）在处理知识密集型任务时表现出色，但其生成的内容可能包含无根据的信息或与检索上下文矛盾，引发信任危机。为此，我们提出了SynCheck，一种轻量级监控工具，它通过分析序列可能性、不确定性、上下文影响及语义对齐等解码动态，实时识别不忠实句子。SynCheck通过整合互补信号，实现了对忠实性错误的快速准确检测，AUROC提升至0.85，超越了现有最佳方法4%。在此基础上，我们开发了FOD，一种以忠实性为核心的解码策略，它利用束搜索优化长格式生成任务，实证显示，FOD在忠实性上较传统方法提升了超过10%。
>
> https://arxiv.org/abs/2406.13692

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13692/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13692](https://arxiv.org/abs/2406.13692)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2