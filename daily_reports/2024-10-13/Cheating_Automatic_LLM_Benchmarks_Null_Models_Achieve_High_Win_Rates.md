# 空模型在自动 LLM 基准测试中“作弊”，胜率惊人。
发布时间：2024年10月09日


> Cheating Automatic LLM Benchmarks: Null Models Achieve High Win Rates
>
> 摘要：自动LLM基准测试如AlpacaEval 2.0、Arena-Hard-Auto和MT-Bench，因其成本效益和可扩展性，已成为评估语言模型的热门选择，远胜于人工评估。在这些基准测试中取得高胜率，能大幅提升新模型的推广效果。然而，这种利益可能诱使一些操纵手段，如调整输出长度或风格以提高胜率，尽管已有机制控制这些因素以减少操纵空间。我们发现，即使是一个“空模型”，即始终输出固定且与指令无关的响应，也能在这些基准测试中作弊，达到顶级胜率：AlpacaEval 2.0上86.5%的LC胜率，Arena-Hard-Auto上83.0分，MT-Bench上9.55分。更甚者，这些作弊输出可转移，因为我们假设基准测试的指令（如AlpacaEval 2.0的805个样本）是私密的，无法获取。虽然我们的实验仅为概念验证，但对手可能利用LLM生成更隐蔽的作弊响应，从中不道德地获益。这呼吁我们开发反作弊机制，以确保自动基准测试的可靠性。相关代码可在此链接获取。
>
> https://arxiv.org/pdf/2410.07137

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/pdf/2410.07137](https://arxiv.org/pdf/2410.07137)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)