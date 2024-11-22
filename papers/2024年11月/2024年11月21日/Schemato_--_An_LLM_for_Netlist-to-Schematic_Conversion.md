# Schemato —— 一款用于网表转原理图的 LLM

发布时间：2024年11月21日

`LLM应用` `电路设计` `机器学习`

> Schemato -- An LLM for Netlist-to-Schematic Conversion

# 摘要

> 机器学习模型正在助力电路设计，尤其是在模拟电路领域。它们生成的网表通常让人难以理解。这是个大问题，毕竟人类设计师很大程度上依靠电路图或原理图的可解释性来直观地理解、排查故障和开展设计工作。所以，要想有效地融合领域知识，迅速且精准地把机器学习生成的网表转化为可解释的原理图极为关键。我们推出了 Schemato，这是一个用于网表转原理图的大型语言模型（LLM）。具体来说，我们在将网表转换为 LTSpice 的.asc 文件和 CircuiTikz 原理图的 LATEX 文件这两种情形下考量了我们的方法。针对我们的电路数据集所做的实验显示，Schemato 在网表到 LaTeX 转换任务中的编译成功率高达 93％，远超最先进的 LLM 所取得的 26％。而且，我们的实验表明，Schemato 生成的原理图的平均结构相似性指数度量比表现最佳的 LLM 高出 3 倍，因而更接近人类的参考设计。

> Machine learning models are advancing circuit design, particularly in analog circuits. They typically generate netlists that lack human interpretability. This is a problem as human designers heavily rely on the interpretability of circuit diagrams or schematics to intuitively understand, troubleshoot, and develop designs. Hence, to integrate domain knowledge effectively, it is crucial to translate ML-generated netlists into interpretable schematics quickly and accurately. We propose Schemato, a large language model (LLM) for netlist-to-schematic conversion. In particular, we consider our approach in the two settings of converting netlists to .asc files for LTSpice and LATEX files for CircuiTikz schematics. Experiments on our circuit dataset show that Schemato achieves up to 93% compilation success rate for the netlist-to-LaTeX conversion task, surpassing the 26% rate scored by the state-of-the-art LLMs. Furthermore, our experiments show that Schemato generates schematics with a mean structural similarity index measure that is 3xhigher than the best performing LLMs, therefore closer to the reference human design.

[Arxiv](https://arxiv.org/abs/2411.13899)