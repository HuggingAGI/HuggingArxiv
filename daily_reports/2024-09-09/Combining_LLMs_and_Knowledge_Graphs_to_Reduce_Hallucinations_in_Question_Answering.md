# 将 LLM 与知识图谱结合，旨在减少问答中的幻觉现象。
发布时间：2024年09月06日

`知识图谱`
> Combining LLMs and Knowledge Graphs to Reduce Hallucinations in Question Answering
>
> 自然语言处理的进步让数字信息系统（如数据库）变得更加亲民。但在生物医学等对准确性要求极高的领域，挑战依旧。幻觉问题尤为棘手，模型可能生成与数据不符的信息，带来误导风险。本文通过结合大型语言模型（LLM）和知识图谱（KG），提出了一种提升问答系统准确性的新方法，以生物医学KG为例。基于LangChain框架，我们的方法引入查询检查器，确保LLM生成的查询既合语法又合逻辑，从而减少错误。我们用50个生物医学问题的新数据集测试了多个LLM，发现GPT-4 Turbo在准确性上领先，而llama3:70b等开源模型在精心设计提示后也表现不俗。为方便用户，我们开发了友好的Web界面，用户可输入自然语言查询，查看并验证生成的Cypher查询。这种混合方法有效解决了数据缺口和幻觉问题，为问答系统提供了可靠且直观的解决方案。源代码已公开，详见：https://git.zib.de/lpusch/cyphergenkg-gui。
>
> https://arxiv.org/abs/2409.04181

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.04181](https://arxiv.org/abs/2409.04181)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)