# 大型语言模型中的思维轨迹

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Lines of Thought in Large Language Models

# 摘要

> 大型语言模型通过将向量化文本（提示）在变换器层的连续作用下传输到嵌入空间，实现下一个标记的预测。这些高维轨迹反映了不同的“思考”步骤，并决定了输出概率分布。我们旨在研究这些“思维线”集合的统计特性。研究发现，独立轨迹沿低维非欧流形聚集，其路径可用数据提取的少量参数的随机方程近似。这表明，庞大模型的复杂性可简化为更简洁的形式，这一发现引人深思。

> Large Language Models achieve next-token prediction by transporting a vectorized piece of text (prompt) across an accompanying embedding space under the action of successive transformer layers. The resulting high-dimensional trajectories realize different contextualization, or 'thinking', steps, and fully determine the output probability distribution. We aim to characterize the statistical properties of ensembles of these 'lines of thought.' We observe that independent trajectories cluster along a low-dimensional, non-Euclidean manifold, and that their path can be well approximated by a stochastic equation with few parameters extracted from data. We find it remarkable that the vast complexity of such large models can be reduced to a much simpler form, and we reflect on implications.

[Arxiv](https://arxiv.org/abs/2410.01545)