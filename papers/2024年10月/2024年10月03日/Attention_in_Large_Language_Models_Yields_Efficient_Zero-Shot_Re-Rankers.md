# 大型语言模型中的注意力机制，成就了高效的零-shot 重新排序器。

发布时间：2024年10月03日

`RAG` `信息检索` `人工智能`

> Attention in Large Language Models Yields Efficient Zero-Shot Re-Rankers

# 摘要

> 信息检索系统在现代数字生活中不可或缺，通过检索增强生成，它们在生成AI时代依然实用。大型语言模型（LLMs）凭借其强大的语言处理能力和多功能性，成为IR系统中零-shot重排序的首选。然而，现有的LLM重排序方法依赖于生成能力，限制了其应用范围。我们质疑：自回归生成对LLM重排序真的必要且最佳吗？我们推测，LLM中存在大量未充分利用的重排序信号。为此，我们提出上下文内重排序（ICR），利用搜索查询引起的注意力模式变化进行高效重排序。为减少LLM的固有偏见，我们引入无内容查询校准。ICR仅需两次前向传递，远超生成方法的效率。实验证明，ICR在开放权重LLM上表现优异，延迟显著降低。ICR在复杂重排序任务中尤为出色，呼吁进一步探索LLM的非生成应用。

> Information retrieval (IR) systems have played a vital role in modern digital life and have cemented their continued usefulness in this new era of generative AI via retrieval-augmented generation. With strong language processing capabilities and remarkable versatility, large language models (LLMs) have become popular choices for zero-shot re-ranking in IR systems. So far, LLM-based re-ranking methods rely on strong generative capabilities, which restricts their use to either specialized or powerful proprietary models. Given these restrictions, we ask: is autoregressive generation necessary and optimal for LLMs to perform re-ranking? We hypothesize that there are abundant signals relevant to re-ranking within LLMs that might not be used to their full potential via generation. To more directly leverage such signals, we propose in-context re-ranking (ICR), a novel method that leverages the change in attention pattern caused by the search query for accurate and efficient re-ranking. To mitigate the intrinsic biases in LLMs, we propose a calibration method using a content-free query. Due to the absence of generation, ICR only requires two ($O(1)$) forward passes to re-rank $N$ documents, making it substantially more efficient than generative re-ranking methods that require at least $O(N)$ forward passes. Our novel design also enables ICR to be applied to any LLM without specialized training while guaranteeing a well-formed ranking. Extensive experiments with two popular open-weight LLMs on standard single-hop and multi-hop information retrieval benchmarks show that ICR outperforms RankGPT while cutting the latency by more than 60% in practice. Through detailed analyses, we show that ICR's performance is specially strong on tasks that require more complex re-ranking signals. Our findings call for further exploration on novel ways of utilizing open-weight LLMs beyond text generation.

[Arxiv](https://arxiv.org/abs/2410.02642)