# 基于Transformer的智能调用自动代码补全方法
发布时间：2024年05月23日

`代码编写`
> A Transformer-Based Approach for Smart Invocation of Automatic Code Completion
>
> 基于Transformer的语言模型在代码补全上表现出色，但它们的高成本和潜在干扰性，尤其是在频繁打断开发者时，不容忽视。现有研究往往忽略了这些模型与开发者实际互动的细节，也未明确何时提供补全建议。为此，我们研发了一种机器学习模型，它能根据代码上下文和遥测数据精准判断调用代码补全工具的最佳时机。我们收集了200,000次开发者与跨IDE插件的互动数据，并训练了多个调用过滤模型。实验表明，我们的小型Transformer模型不仅超越了基准，而且延迟极低。我们还尝试将更多遥测数据直接融入预训练模型，取得了积极进展。为了验证其实际应用价值，我们在线上环境中部署了该模型，覆盖了34名开发者，并基于74,000次实际调用，提供了宝贵的实战洞察。
>
> https://arxiv.org/abs/2405.14753


<hr />

- 论文原文: [https://arxiv.org/abs/2405.14753](https://arxiv.org/abs/2405.14753)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886