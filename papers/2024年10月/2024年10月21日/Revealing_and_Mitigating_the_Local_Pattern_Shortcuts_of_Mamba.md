# 揭秘并缓解 Mamba 的局部模式捷径

发布时间：2024年10月21日

`LLM理论` `人工智能`

> Revealing and Mitigating the Local Pattern Shortcuts of Mamba

# 摘要

> 大型语言模型 (LLM) 因注意力机制而大幅进步，但其二次复杂性和线性内存需求限制了其在长上下文任务中的表现。最近推出的 Mamba 模型，基于状态空间模型 (SSM)，提供了线性复杂性和恒定内存。尽管 Mamba 在性能上能与或超越基于注意力的模型，但我们的分析发现，它在处理本地化关键信息任务时表现优异，而在处理分布式关键信息任务时则面临挑战。这主要是因为 Mamba 依赖于本地模式捷径，虽能有效记忆本地关键信息，却难以保留更分散的信息。为此，我们引入了全局选择模块，以解决这一问题。实验结果显示，通过仅增加 4M 额外参数，Mamba 模型在处理分布式信息的任务中性能显著提升，从 0 分跃升至 80.54 分。

> Large language models (LLMs) have advanced significantly due to the attention mechanism, but their quadratic complexity and linear memory demands limit their performance on long-context tasks. Recently, researchers introduced Mamba, an advanced model built upon State Space Models(SSMs) that offers linear complexity and constant memory. Although Mamba is reported to match or surpass the performance of attention-based models, our analysis reveals a performance gap: Mamba excels in tasks that involve localized key information but faces challenges with tasks that require handling distributed key information. Our controlled experiments suggest that this inconsistency arises from Mamba's reliance on local pattern shortcuts, which enable the model to remember local key information within its limited memory but hinder its ability to retain more dispersed information. Therefore, we introduce a global selection module into the Mamba model to address this issue. Experiments on both existing and proposed synthetic tasks, as well as real-world tasks, demonstrate the effectiveness of our method. Notably, with the introduction of only 4M extra parameters, our approach enables the Mamba model(130M) to achieve a significant improvement on tasks with distributed information, increasing its performance from 0 to 80.54 points.

[Arxiv](https://arxiv.org/abs/2410.15678)