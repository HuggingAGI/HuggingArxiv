# 长上下文推荐中，语言模型面临“注意力溢出”问题，导致输入信息模糊，影响缺失项的准确推荐。
发布时间：2024年07月18日


> Attention Overflow: Language Model Input Blur during Long-Context Missing Items Recommendation
>
> LLM 能从提示列表中推荐缺失项，适用于列表补全或基于用户历史的推荐。但当列表过长（约 100 项）时，模型会重复推荐已有的项目，这种现象我们称之为“注意力溢出”。我们在合成问题和真实电影推荐场景中测试了这一现象。虽然迭代方法能减轻问题，但其成本随重复率上升，影响模型从长输入中创新的能力。
>
> https://arxiv.org/abs/2407.13481


<hr />

- 论文原文: [https://arxiv.org/abs/2407.13481](https://arxiv.org/abs/2407.13481)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1