# AgentGen：通过创造环境和任务，提升大型语言模型代理的规划能力
发布时间：2024年08月01日

`Agent应用`
> AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation
>
> 基于大型语言模型的智能体备受瞩目，日益流行。其中，规划能力是智能体的核心，涉及与环境互动并执行动作以达成目标。本文通过指令调优（代理训练）提升LLM的规划能力。最新研究表明，利用专家级轨迹进行调优能有效增强规划能力。然而，现有研究多依赖手动设计的任务和环境，这限制了轨迹的多样性和广泛性。为此，我们探索自动合成多样化环境和逐步难度递增的规划任务。我们提出AgentGen框架，首先生成环境，再基于环境生成任务。为提升环境多样性，我们采用多领域文本段作为合成环境的基础。同时，为确保任务难度多样性，我们设计了双向进化方法Bi-Evol，从易到难逐步合成任务集。评估显示，AgentGen显著提升了LLM的规划能力，如AgentGen调优的Llama-3 8B在性能上超越了GPT-3.5，甚至在某些任务中优于GPT-4。
>
> https://arxiv.org/abs/2408.00764

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.00764](https://arxiv.org/abs/2408.00764)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)