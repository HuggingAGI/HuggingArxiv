# TrajGPT：使用基于多任务 Transformer 的时空模型进行受控的合成轨迹生成

发布时间：2024年11月06日

`LLM应用` `城市规划` `流行病学`

> TrajGPT: Controlled Synthetic Trajectory Generation Using a Multitask Transformer-Based Spatiotemporal Model

# 摘要

> 从 GPS 轨迹进行人类移动建模和合成轨迹生成对于各种应用至关重要，例如城市规划、灾害管理和流行病学。这两项任务通常都需要填补部分指定的访问序列中的空白——这是一个我们称之为“受控”合成轨迹生成的新问题。现有的下一个位置预测或合成轨迹生成方法无法解决此问题，因为它们缺乏约束生成的访问序列所需的机制。此外，现有方法（1）经常将空间和时间视为独立因素，这一假设在现实场景中并不成立，并且（2）由于无法处理混合分布以及不同模式与潜在变量（例如，一周中的某天）的相互关系，在时间预测的准确性方面存在挑战。当任务涉及填补序列内的空白而不仅仅是预测下一次访问时，这些限制变得更加明显。
  我们引入 TrajGPT，这是一种基于 Transformer 的多任务联合时空生成模型，以解决这些问题。受大型语言模型的启发，TrajGPT 将受控轨迹生成的问题表述为自然语言中的文本填充问题。TrajGPT 通过贝叶斯概率模型将时空模型集成在 Transformer 架构中，确保访问序列中的空白以时空一致的方式被填补。我们在公共和私有数据集上的实验表明，TrajGPT 不仅在受控合成访问生成方面表现出色，而且在下一个位置预测任务中也优于竞争模型——相对而言，TrajGPT 在时间准确性上实现了 26 倍的提升，同时平均保持了超过 98％的空间准确性。

> Human mobility modeling from GPS-trajectories and synthetic trajectory generation are crucial for various applications, such as urban planning, disaster management and epidemiology. Both of these tasks often require filling gaps in a partially specified sequence of visits - a new problem that we call "controlled" synthetic trajectory generation. Existing methods for next-location prediction or synthetic trajectory generation cannot solve this problem as they lack the mechanisms needed to constrain the generated sequences of visits. Moreover, existing approaches (1) frequently treat space and time as independent factors, an assumption that fails to hold true in real-world scenarios, and (2) suffer from challenges in accuracy of temporal prediction as they fail to deal with mixed distributions and the inter-relationships of different modes with latent variables (e.g., day-of-the-week). These limitations become even more pronounced when the task involves filling gaps within sequences instead of solely predicting the next visit.
  We introduce TrajGPT, a transformer-based, multi-task, joint spatiotemporal generative model to address these issues. Taking inspiration from large language models, TrajGPT poses the problem of controlled trajectory generation as that of text infilling in natural language. TrajGPT integrates the spatial and temporal models in a transformer architecture through a Bayesian probability model that ensures that the gaps in a visit sequence are filled in a spatiotemporally consistent manner. Our experiments on public and private datasets demonstrate that TrajGPT not only excels in controlled synthetic visit generation but also outperforms competing models in next-location prediction tasks - Relatively, TrajGPT achieves a 26-fold improvement in temporal accuracy while retaining more than 98% of spatial accuracy on average.

[Arxiv](https://arxiv.org/abs/2411.04381)