# AdaptAgent：借助人类演示的少样本学习来适配多模态网络代理

发布时间：2024年11月20日

`Agent` `人工智能`

> AdaptAgent: Adapting Multimodal Web Agents with Few-Shot Learning from Human Demonstrations

# 摘要

> 最先进的多模态网络代理，由多模态大型语言模型（MLLMs）驱动，能够通过处理用户指令和与图形用户界面（GUIs）交互，自主执行众多网络任务。当下构建网络代理的策略，依赖于（一）底层 MLLMs 的泛化能力及其通过提示的可操控性，还有（二）针对网络相关任务对 MLLMs 进行大规模微调。然而，网络代理在未见过的网站和领域中执行任务时仍面临困难，这限制了它们在企业特定和专有平台上的应用。除了大规模预训练和微调所带来的泛化能力，我们提议借助人类示范来构建具备少样本适应能力的代理。我们引入了 AdaptAgent 框架，它能让专有和开放权重的多模态网络代理，利用少量人类示范（最多 2 个）适应新的网站和领域。我们在两个热门基准——Mind2Web 和 VisualWebArena 上开展的实验表明，使用上下文示范（针对专有模型）或元适应示范（针对元学习的开放权重模型），相比未适应的前沿模型，能将任务成功率提升 3.36%至 7.21%，相对提高 21.03%至 65.75%。此外，我们的额外分析（一）表明多模态示范比纯文本示范更有效，（二）揭示了元学习期间不同数据选择策略对代理泛化的影响，（三）展示了少样本数量对网络代理成功率的作用。总之，我们的成果为开发广泛适用的多模态网络代理开辟了新途径，超越了大规模预训练和微调，突出了少样本适应能力。

> State-of-the-art multimodal web agents, powered by Multimodal Large Language Models (MLLMs), can autonomously execute many web tasks by processing user instructions and interacting with graphical user interfaces (GUIs). Current strategies for building web agents rely on (i) the generalizability of underlying MLLMs and their steerability via prompting, and (ii) large-scale fine-tuning of MLLMs on web-related tasks. However, web agents still struggle to automate tasks on unseen websites and domains, limiting their applicability to enterprise-specific and proprietary platforms. Beyond generalization from large-scale pre-training and fine-tuning, we propose building agents for few-shot adaptability using human demonstrations. We introduce the AdaptAgent framework that enables both proprietary and open-weights multimodal web agents to adapt to new websites and domains using few human demonstrations (up to 2). Our experiments on two popular benchmarks -- Mind2Web & VisualWebArena -- show that using in-context demonstrations (for proprietary models) or meta-adaptation demonstrations (for meta-learned open-weights models) boosts task success rate by 3.36% to 7.21% over non-adapted state-of-the-art models, corresponding to a relative increase of 21.03% to 65.75%. Furthermore, our additional analyses (a) show the effectiveness of multimodal demonstrations over text-only ones, (b) shed light on the influence of different data selection strategies during meta-learning on the generalization of the agent, and (c) demonstrate the effect of number of few-shot examples on the web agent's success rate. Overall, our results unlock a complementary axis for developing widely applicable multimodal web agents beyond large-scale pre-training and fine-tuning, emphasizing few-shot adaptability.

[Arxiv](https://arxiv.org/abs/2411.13451)