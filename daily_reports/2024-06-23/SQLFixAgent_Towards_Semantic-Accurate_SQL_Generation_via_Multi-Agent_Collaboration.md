# SQLFixAgent：借助多代理协作，精准生成语义准确的SQL语句
发布时间：2024年06月19日

`Agent应用`
> SQLFixAgent: Towards Semantic-Accurate SQL Generation via Multi-Agent Collaboration
>
> 尽管LLMs在文本到SQL任务中能生成语法正确的SQL，但它们在确保查询语义准确性方面仍显不足，常导致用户困惑和系统可用性降低。为此，我们开发了SQLFixAgent，一个创新的多代理协作框架，专门用于检测和修复错误的SQL。该框架由核心代理SQLRefiner和两个辅助代理SQLReviewer与QueryCrafter组成。SQLReviewer利用橡皮鸭调试技术识别语义不匹配，而QueryCrafter则生成多个候选修复方案。最终，SQLRefiner通过修复检索和记忆反射机制，选出最佳修复方案。在五个文本到SQL基准测试中，我们的方法不仅提升了基准模型的性能，尤其在Bird基准上执行准确性提高了超过3%，而且在令牌效率上也超越了其他先进方法，显示出更高的竞争力。
>
> https://arxiv.org/abs/2406.13408

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13408/x6.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13408](https://arxiv.org/abs/2406.13408)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2