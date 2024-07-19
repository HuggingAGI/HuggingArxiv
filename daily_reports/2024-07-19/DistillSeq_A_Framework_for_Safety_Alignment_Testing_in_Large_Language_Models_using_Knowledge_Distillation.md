# DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架
发布时间：2024年07月14日

`模型安全`
> DistillSeq: A Framework for Safety Alignment Testing in Large Language Models using Knowledge Distillation
>
> 大型语言模型（LLM）在自然语言理解、翻译乃至代码生成等多个领域展现了非凡能力。然而，LLM 产生有害内容的风险不容忽视，这要求我们对其进行严格测试和全面评估，确保其安全且负责任地使用。但大规模测试 LLM 耗资巨大，因此，在测试阶段寻找节约成本的策略至关重要。我们的方法首先将审查知识从大型模型转移至小型模型，然后采用两种策略生成恶意查询：一是基于语法树的方法，二是利用 LLM 的方法。最后，我们设计了一个顺序过滤-测试流程，以识别易引发有毒反应的测试案例。研究显示，DistillSeq 在 GPT-3.5、GPT-4.0、Vicuna-13B 和 Llama-13B 上的应用，使得攻击成功率显著提升，平均增加了 93.0%。这表明 DistillSeq 在减少测试 LLM 所需时间和资源方面具有显著优势。
>
> https://arxiv.org/abs/2407.10106

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10106/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10106/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10106/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10106/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.10106](https://arxiv.org/abs/2407.10106)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1