# Theseus 项目致力于为大型语言模型优化晶圆级芯片设计，提升探索效率。

发布时间：2024年07月02日

`LLM应用` `半导体` `人工智能`

> Theseus: Towards High-Efficiency Wafer-Scale Chip Design Space Exploration for Large Language Models

# 摘要

> 随着大型语言模型（LLM）的兴起，对计算能力、内存和通信带宽的需求激增，远超芯片设计的进步。为此，设计师们正致力于开发晶圆级芯片（WSCs），以突破单芯片的性能极限。现有研究表明，WSCs在支持LLM方面具有巨大潜力。然而，探索WSCs的早期设计空间充满挑战，涉及复杂的设计选项、耗时的评估过程和低效的探索策略。为此，我们推出了Theseus框架，旨在高效探索WSCs的设计空间。我们结合WSCs的特性，构建了多约束的设计空间，并采用多保真贝叶斯优化，以加速设计探索。评估显示，Theseus找到的最优设计在LLM训练中性能和能效分别提升高达62.8%/73.7%和38.6%/42.4%，在推理任务中性能和能效更是分别提升至23.2倍和15.7倍。此外，我们还通过案例研究，深入分析了WSCs的设计权衡，为未来LLM的WSC设计提供了宝贵见解。

> The emergence of the large language model~(LLM) poses an exponential growth of demand for computation throughput, memory capacity, and communication bandwidth. Such a demand growth has significantly surpassed the improvement of corresponding chip designs. With the advancement of fabrication and integration technologies, designers have been developing Wafer-Scale Chips(WSCs) to scale up and exploit the limits of computation density, memory capacity, and communication bandwidth at the level of a single chip. Existing solutions have demonstrated the significant advantages of WSCs over traditional designs, showing potential to effectively support LLM workloads.
  Despite the benefits, exploring the early-stage design space of WSCs for LLMs is a crucial yet challenging task due to the enormous and complicated design space, time-consuming evaluation methods, and inefficient exploration strategies. To address these challenges, we propose Theseus, an efficient WSC design space exploration framework for LLMs. We construct the design space of WSCs with various constraints considering the unique characteristics of WSCs. We propose efficient evaluation methodologies for large-scale NoC-based WSCs and introduce multi-fidelity Bayesian optimization to efficiently explore the design space. Evaluation results demonstrate the efficiency of Theseus that the searched Pareto optimal results outperform GPU cluster and existing WSC designs by up to 62.8%/73.7% in performance and 38.6%/42.4% in power consumption for LLM training, while improving up to 23.2$\times$ and 15.7$\times$ for the performance and power of inference tasks. Furthermore, we conduct case studies to address the design tradeoffs in WSCs and provide insights to facilitate WSC designs for LLMs.

[Arxiv](https://arxiv.org/abs/2407.02079)