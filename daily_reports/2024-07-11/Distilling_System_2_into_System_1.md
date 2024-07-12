# 系统2向系统1的精炼转化
发布时间：2024年07月08日


> Distilling System 2 into System 1
>
> 大型语言模型在推理时通过额外计算生成中间思维，从而提升最终响应质量。自 Chain-of-Thought 提出后，多种 System 2 技术如 Rephrase and Respond、System 2 Attention 和 Branch-Solve-Merge 相继涌现。本研究探索自监督方法，将这些 System 2 技术的高质量输出提炼回 LLM，无需中间推理步骤，因为推理已融入 System 1。实验表明，这些技术提炼后不仅性能提升，且推理成本降低。我们预见，这种 System 2 提炼将成为未来 AI 系统持续学习的关键，使其能更高效地运用 System 2 能力于尚需改进的推理任务。
>
> https://arxiv.org/abs/2407.06023

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.06023/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.06023/MT_bench_wo_tie.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.06023/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.06023](https://arxiv.org/abs/2407.06023)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1