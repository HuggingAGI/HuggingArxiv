# Star-Agents：借助 LLM 代理实现指令调优的自动数据优化

发布时间：2024年11月20日

`Agent` `语言模型` `数据处理`

> Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning

# 摘要

> 大型语言模型（LLMs）在下游任务中的效果往往取决于指令调优，而这又极度依赖训练数据的质量。可惜的是，收集高质量且多样的数据既费钱又费时。为解决此难题，我们提出了全新的 Star-Agents 框架，它通过多智能体协作与评估，自动提升跨数据集的数据质量。该框架采取了三方面策略。首先，通过定制采样方法，利用多个 LLM 智能体生成多样的指令数据。接着，运用评估难度和质量的双模型方法对生成的数据进行严格评估。最后，上述过程在动态优化阶段不断演进，优先选择更有效的 LLM，从而提升整体数据质量。我们的实证研究，涵盖了对 Pythia 和 LLaMA 等模型的指令调优实验，证实了所提框架的有效性。优化后的数据集有了显著提升，平均提高 12%，在特定指标上表现出色，比如在 Fermi 上提升 40%，这在 MT-bench、Vicuna bench 和 WizardLM 测试集等基准测试中均有体现。

> The efficacy of large language models (LLMs) on downstream tasks usually hinges on instruction tuning, which relies critically on the quality of training data. Unfortunately, collecting high-quality and diverse data is both expensive and time-consuming. To mitigate this issue, we propose a novel Star-Agents framework, which automates the enhancement of data quality across datasets through multi-agent collaboration and assessment. The framework adopts a three-pronged strategy. It initially generates diverse instruction data with multiple LLM agents through a bespoke sampling method. Subsequently, the generated data undergo a rigorous evaluation using a dual-model method that assesses both difficulty and quality. Finaly, the above process evolves in a dynamic refinement phase, where more effective LLMs are prioritized, enhancing the overall data quality. Our empirical studies, including instruction tuning experiments with models such as Pythia and LLaMA, demonstrate the effectiveness of the proposed framework. Optimized datasets have achieved substantial improvements, with an average increase of 12% and notable gains in specific metrics, such as a 40% improvement in Fermi, as evidenced by benchmarks like MT-bench, Vicuna bench, and WizardLM testset.

[Arxiv](https://arxiv.org/abs/2411.14497)