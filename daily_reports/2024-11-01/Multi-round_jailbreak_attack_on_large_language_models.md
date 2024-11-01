# 大型语言模型面临多轮越狱攻击
发布时间：2024年10月15日


> Multi-round jailbreak attack on large language models
>
> 确保 LLM 与人类价值观的安全一致至关重要。尽管 LLM 能识别并避免有害查询，但仍易受“越狱”攻击，精心设计的提示可诱导生成有毒内容。传统单轮越狱攻击如 GCG 和 AutoDAN 不改变危险提示中的敏感词，虽能通过提示工程暂时绕过模型安全措施，但随着 LLM 进一步微调，成功率显著下降，且无法有效绕过删除危险词汇的静态规则过滤器。本研究引入多轮越狱方法，重写危险提示为危害较小的子问题，绕过 LLM 安全检查。首先使用 LLM 将自然语言问题分解为渐进子问题，微调 Llama3-8B 模型以分解危险提示。微调后模型分解问题提示，生成的子问题依次询问受害者模型。若受害者模型拒绝子问题，则生成新分解并重复，直至达成目标。实验结果显示，在 llama2-7B 上的成功率为 94%，证明该方法在绕过静态规则过滤器方面的有效性。
>
> https://arxiv.org/abs/2410.11533

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.11533](https://arxiv.org/abs/2410.11533)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)