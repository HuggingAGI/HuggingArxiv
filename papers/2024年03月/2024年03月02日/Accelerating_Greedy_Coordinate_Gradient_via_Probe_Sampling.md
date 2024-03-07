# [我们提出了一种利用探针采样技术来提升贪婪坐标梯度法的效率，即“加速贪婪坐标梯度探针采样方法”，尤其在处理大规模优化问题时，有效提高了算法的运行速度与性能。](https://arxiv.org/abs/2403.01251)

发布时间：2024年03月02日

`LLM应用`

> Accelerating Greedy Coordinate Gradient via Probe Sampling

> 随着 LLMs 快速发展并广泛应用，其安全性问题日益凸显。尽管 GCG 方法已被证实能有效地通过构建包含对抗后缀的提示来突破被认为安全的 LLMs，然而，该方法的优化过程耗时较长，限制了其实用价值。为了解决这一问题并深化对 LLM 安全性的探索，本研究提出一种名为“Probe sampling”的新型算法，用于加快 GCG 的运行速度。该算法的关键在于实时评估小型预览模型对提示候选的预测结果与目标模型的接近程度，若两者较为相似，则借助预览模型高效筛选大量提示候选，从而大幅缩减计算所需的时间。经验证，利用 Llama2-7b 模型的 Probe sampling 能实现最高 5.6 倍的速度提升，并在 AdvBench 测试中取得了相同甚至更优的攻击成功率（ASR）。

> Safety of Large Language Models (LLMs) has become a central issue given their rapid progress and wide applications. Greedy Coordinate Gradient (GCG) is shown to be effective in constructing prompts containing adversarial suffixes to break the presumingly safe LLMs, but the optimization of GCG is time-consuming and limits its practicality. To reduce the time cost of GCG and enable more comprehensive studies of LLM safety, in this work, we study a new algorithm called $\texttt{Probe sampling}$ to accelerate the GCG algorithm. At the core of the algorithm is a mechanism that dynamically determines how similar a smaller draft model's predictions are to the target model's predictions for prompt candidates. When the target model is similar to the draft model, we rely heavily on the draft model to filter out a large number of potential prompt candidates to reduce the computation time. Probe sampling achieves up to $5.6$ times speedup using Llama2-7b and leads to equal or improved attack success rate (ASR) on the AdvBench.