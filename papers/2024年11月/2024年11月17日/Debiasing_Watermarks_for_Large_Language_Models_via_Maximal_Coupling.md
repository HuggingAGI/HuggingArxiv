# 借助最大耦合为大型语言模型去除偏差水印

发布时间：2024年11月17日

`LLM应用` `数字通信` `语言模型`

> Debiasing Watermarks for Large Language Models via Maximal Coupling

# 摘要

> 水印语言模型对于区分人类与机器生成的文本，进而维护数字通信的完整性与可信度，意义重大。我们推出了一种新颖的绿/红名单水印方式，将令牌集划分成“绿色”和“红色”列表，巧妙地提高绿色令牌的生成概率。为矫正令牌分布偏差，我们的方法运用最大耦合，通过均匀抛硬币来决定是否进行偏差校正，其结果作为伪随机水印信号嵌入。理论分析证实了该方法的无偏性和强大的检测能力。实验结果显示，它在维持高检测性的同时保证了文本质量，优于以往技术，并且能抵御旨在提升文本质量的针对性修改。此项研究为语言模型提供了一个前景可观的水印解决方案，在有效检测与对文本质量的最小影响之间实现了平衡。

> Watermarking language models is essential for distinguishing between human and machine-generated text and thus maintaining the integrity and trustworthiness of digital communication. We present a novel green/red list watermarking approach that partitions the token set into ``green'' and ``red'' lists, subtly increasing the generation probability for green tokens. To correct token distribution bias, our method employs maximal coupling, using a uniform coin flip to decide whether to apply bias correction, with the result embedded as a pseudorandom watermark signal. Theoretical analysis confirms this approach's unbiased nature and robust detection capabilities. Experimental results show that it outperforms prior techniques by preserving text quality while maintaining high detectability, and it demonstrates resilience to targeted modifications aimed at improving text quality. This research provides a promising watermarking solution for language models, balancing effective detection with minimal impact on text quality.

[Arxiv](https://arxiv.org/abs/2411.11203)