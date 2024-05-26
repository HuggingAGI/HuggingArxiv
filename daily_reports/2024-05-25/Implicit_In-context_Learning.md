# 隐式上下文学习探究
发布时间：2024年05月23日

`提示工程`
> Implicit In-context Learning
>
> In-context Learning (ICL) 通过在测试查询前添加演示示例，赋予大型语言模型 (LLMs) 在推理时适应新任务的能力。尽管ICL功能强大，但它相比零-shot学习带来了更多的计算和内存负担，且易受演示示例选择和顺序的影响。为此，我们提出了Implicit In-context Learning (I2CL)，一种创新方法，通过在模型激活空间内融入演示示例来克服传统ICL的局限。I2CL首先生成一个浓缩的上下文向量，然后在推理中通过将此向量与查询激活结合注入模型残差流来发挥作用。实证研究表明，I2CL在保持零-shot成本的同时达到了few-shot性能，并对演示示例的变化表现出鲁棒性。此外，I2CL引入了“任务-ids”的新概念，提升了任务相似性识别并促进了有效的迁移学习。我们深入分析了I2CL的机制及其对ICL领域的深远影响，并公开了源代码，详情请访问：https://github.com/LzVv123456/I2CL。
>
> https://arxiv.org/abs/2405.14660


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14660](https://arxiv.org/abs/2405.14660)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886