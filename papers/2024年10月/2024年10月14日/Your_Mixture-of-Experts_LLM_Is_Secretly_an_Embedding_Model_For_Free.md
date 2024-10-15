# 你的专家混合型大型语言模型，其实是个免费的嵌入模型哦！

发布时间：2024年10月14日

`LLM理论` `人工智能`

> Your Mixture-of-Experts LLM Is Secretly an Embedding Model For Free

# 摘要

> 尽管 LLM 在生成任务上表现优异，但其仅解码器架构若未经进一步微调，往往限制了其作为嵌入模型的潜力。这与其“多面手”的宣称是否矛盾？我们深入研究了 Mixture-of-Experts (MoE) LLM，发现其中的专家路由器无需微调，即可在多样化的嵌入任务中表现出色，成为现成的嵌入模型。此外，MoE 路由权重 (RW) 与 LLM 的隐藏状态 (HS) 互补，RW 对提示选择更为稳健，专注于高级语义。基于此，我们提出 MoEE，结合 RW 和 HS，性能超越单独使用。实验结果显示，MoEE 在不微调的情况下，显著提升了 LLM 的嵌入性能。

> While large language models (LLMs) excel on generation tasks, their decoder-only architecture often limits their potential as embedding models if no further representation finetuning is applied. Does this contradict their claim of generalists? To answer the question, we take a closer look at Mixture-of-Experts (MoE) LLMs. Our study shows that the expert routers in MoE LLMs can serve as an off-the-shelf embedding model with promising performance on a diverse class of embedding-focused tasks, without requiring any finetuning. Moreover, our extensive analysis shows that the MoE routing weights (RW) is complementary to the hidden state (HS) of LLMs, a widely-used embedding. Compared to HS, we find that RW is more robust to the choice of prompts and focuses on high-level semantics. Motivated by the analysis, we propose MoEE combining RW and HS, which achieves better performance than using either separately. Our exploration of their combination and prompting strategy shed several novel insights, e.g., a weighted sum of RW and HS similarities outperforms the similarity on their concatenation. Our experiments are conducted on 6 embedding tasks with 20 datasets from the Massive Text Embedding Benchmark (MTEB). The results demonstrate the significant improvement brought by MoEE to LLM-based embedding without further finetuning.

[Arxiv](https://arxiv.org/abs/2410.10814)