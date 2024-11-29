# Star-Agents：借助 LLM 代理实现指令调优的自动数据优化
发布时间：2024年11月20日

`Agent应用`
> Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning
>
> 大型语言模型（LLMs）在下游任务中的效果往往取决于指令调优，而这又极度依赖训练数据的质量。可惜的是，收集高质量且多样的数据既费钱又费时。为解决此难题，我们提出了全新的 Star-Agents 框架，它通过多智能体协作与评估，自动提升跨数据集的数据质量。该框架采取了三方面策略。首先，通过定制采样方法，利用多个 LLM 智能体生成多样的指令数据。接着，运用评估难度和质量的双模型方法对生成的数据进行严格评估。最后，上述过程在动态优化阶段不断演进，优先选择更有效的 LLM，从而提升整体数据质量。我们的实证研究，涵盖了对 Pythia 和 LLaMA 等模型的指令调优实验，证实了所提框架的有效性。优化后的数据集有了显著提升，平均提高 12%，在特定指标上表现出色，比如在 Fermi 上提升 40%，这在 MT-bench、Vicuna bench 和 WizardLM 测试集等基准测试中均有体现。
>
> https://arxiv.org/abs/2411.14497

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2411.14497](https://arxiv.org/abs/2411.14497)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)