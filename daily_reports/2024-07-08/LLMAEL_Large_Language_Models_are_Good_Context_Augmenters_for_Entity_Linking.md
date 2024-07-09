# LLMAEL：大型语言模型在实体链接中扮演着优秀的上下文增强角色。
发布时间：2024年07月04日

`知识图谱`
> LLMAEL: Large Language Models are Good Context Augmenters for Entity Linking
>
> 实体链接模型虽擅长将提及与上下文中的实体对应，但在处理长尾实体时因数据有限而力不从心。大型语言模型虽能更好地解读罕见提及，却因缺乏针对性训练而在生成准确实体ID上表现欠佳。训练LLM进行实体链接成本高昂。为此，我们提出LLM增强型实体链接（LLMAEL），通过LLM数据增强实现即插即用，提升实体链接性能。我们利用LLM生成以提及为中心的描述作为补充输入，同时结合传统EL模型的任务特定处理。实验结果显示，LLMAEL在多数情况下超越了传统EL模型，而经过微调的版本更是在所有6个基准测试中刷新了记录。
>
> https://arxiv.org/abs/2407.04020

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04020/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.04020/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.04020](https://arxiv.org/abs/2407.04020)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1