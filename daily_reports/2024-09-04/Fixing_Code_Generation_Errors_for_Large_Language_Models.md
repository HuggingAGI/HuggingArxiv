# 解决大型语言模型中的代码生成问题
发布时间：2024年09月01日

`代码编写`
> Fixing Code Generation Errors for Large Language Models
>
> 代码生成借助人工智能技术，尤其是大型语言模型（LLM），自动产出源代码，加速软件开发并减少重复劳动。但LLM生成的代码常因无法通过测试而需大量人力纠错。以往研究多聚焦于优化提示或提升LLM性能，却忽视了其失败根源。本文中，我们重现了包括GPT-3.5-turbo在内的14个LLM，在HumanEval数据集上，深入剖析了12,837个代码错误，识别出19种错误原因。实证显示，其中三种可直接修复。为此，我们提出LlmFix修复法，通过三步流程：调整代码缩进、删除冗余代码、补充缺失模块，有效解决了这些问题。实验证实，LlmFix大幅提升了14个LLM在HumanEval和MBPP数据集上的表现，平均提升分别为9.5%和5.4%。
>
> https://arxiv.org/abs/2409.00676

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.00676](https://arxiv.org/abs/2409.00676)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)