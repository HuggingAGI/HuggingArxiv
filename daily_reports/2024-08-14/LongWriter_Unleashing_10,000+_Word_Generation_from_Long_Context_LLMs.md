# LongWriter：激发长上下文 LLM 生成万字长文的能力
发布时间：2024年08月13日


> LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs
>
> 当前的长上下文大型语言模型 (LLM) 虽能处理多达 100,000 个令牌的输入，但在生成超过 2,000 字的输出时仍显吃力。我们通过实验发现，模型的生成能力受限于其在监督微调 (SFT) 期间所接触的样本长度。简言之，现有 SFT 数据集中长输出示例的匮乏限制了模型的输出能力。为此，我们推出了 AgentWrite，一个基于代理的流水线，它将超长生成任务分解为子任务，使 LLM 能够生成超过 20,000 字的连贯文本。借助 AgentWrite，我们创建了 LongWriter-6k 数据集，包含 6,000 个 SFT 数据，输出长度从 2k 到 32k 字不等。通过整合这一数据集进行模型训练，我们成功将模型的输出长度扩展至 10,000 字以上，且保持了输出质量。此外，我们还开发了 LongBench-Write 基准，用于评估超长生成能力。我们的 9B 参数模型，经 DPO 优化后，在该基准上表现卓越，甚至超越了更大规模的专有模型。我们的研究表明，现有的长上下文 LLM 已具备更大的输出潜力，只需在模型对齐过程中使用更长的输出数据，即可释放这一潜能。相关代码和模型已公开在：https://github.com/THUDM/LongWriter。
>
> https://arxiv.org/abs/2408.07055

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.07055](https://arxiv.org/abs/2408.07055)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)