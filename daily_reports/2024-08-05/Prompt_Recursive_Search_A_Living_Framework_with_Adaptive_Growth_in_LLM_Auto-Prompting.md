# 提示递归搜索：在 LLM 自动提示领域，这是一个随需应变、不断成长的动态框架。
发布时间：2024年08月02日

`提示工程`
> Prompt Recursive Search: A Living Framework with Adaptive Growth in LLM Auto-Prompting
>
> 大型语言模型 (LLM) 在 NLP 领域内解决多样任务方面表现卓越，多种提示设计策略显著提升了其性能。然而，这些提示虽有益，也各有局限。主要提示设计方法包括：专家设计提示 (EDP)，如思维链 (CoT)，针对特定数据集手动设计，一旦确立便不可更改，其有效性受限于设计者的专业水平。应用于 LLM 时，EDP 的静态性质导致同一数据集中简单和复杂问题采用统一方法，造成直接问题的令牌使用效率低下。另一种方法是 LLM 衍生提示 (LDP)，为特定问题提供定制解决方案，缓解了 EDP 的限制，但在解决复杂问题时可能因错误累积而性能下降。为应对这些挑战，我们设计了提示递归搜索 (PRS) 框架，利用 LLM 生成特定问题的解决方案，节省令牌，并包含问题复杂性评估和可调整结构，降低错误风险。通过在不同领域的一系列数据集上使用不同参数数量的 LLM 进行广泛实验，我们证实了 PRS 框架的有效性。与 CoT 方法相比，PRS 方法在使用 Llama3-7B 模型时，在 BBH 数据集上的准确率提高了 8%，实现了 22% 的改进。
>
> https://arxiv.org/abs/2408.01423

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01423/eurai)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.01423](https://arxiv.org/abs/2408.01423)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)