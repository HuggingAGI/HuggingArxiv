# StablePrompt：利用强化学习为大型语言模型自动优化提示词
发布时间：2024年10月10日

`提示工程`
> StablePrompt: Automatic Prompt Tuning using Reinforcement Learning for Large Language Models
>
> 随着 LLM 的广泛应用，如何为特定任务找到合适的提示变得愈发关键。尽管强化学习 (RL) 常用于提示优化，但其不稳定性和环境依赖性限制了实际应用。为此，我们推出了 StablePrompt，该方法在训练稳定性和搜索空间之间找到了平衡，有效缓解了 RL 的不稳定性，并生成了高性能的提示。我们将提示调整视为代理与目标 LLM 之间的在线 RL 问题，并引入了自适应近端策略优化 (APPO)。APPO 通过引入 LLM 锚模型，自适应地调整策略更新速率，从而在保留预训练 LLM 语言能力的同时，实现灵活的提示搜索。实验证明，StablePrompt 在文本分类、问答和文本生成等多项任务中均优于以往方法。代码已开源，详见 github。
>
> https://arxiv.org/abs/2410.07652

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.07652](https://arxiv.org/abs/2410.07652)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)