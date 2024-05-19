# 基于提示的多重检索增强生成实现代码补全
发布时间：2024年05月13日

`RAG`
> Prompt-based Code Completion via Multi-Retrieval Augmented Generation
>
> 自动代码补全技术得益于预训练大型语言模型（LLMs）的进步，但在处理复杂代码逻辑或超出训练数据范围时，常面临连贯性和幻觉问题。现有的检索增强生成（RAG）技术虽有所改善，但其检索视角单一，未能充分考虑代码语义的复杂多变。为此，我们推出了ProCC框架，它通过提示工程和上下文多臂老虎机算法，灵活融合多种代码视角。ProCC首先通过多检索器系统，利用提示模板激发LLM理解代码语义的多重视角。接着，采用自适应检索选择算法，结合代码相似性，为LLM选择最佳的补全视角。实验证明，ProCC在开源和私有领域基准测试中分别超越现有技术8.6%和10.1%，在精确匹配方面表现卓越。此外，ProCC还能无缝集成微调技术，提升性能达5.6%。
>
> https://arxiv.org/abs/2405.07530


<hr />

- 论文原文: [https://arxiv.org/abs/2405.07530](https://arxiv.org/abs/2405.07530)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 1522485551482552