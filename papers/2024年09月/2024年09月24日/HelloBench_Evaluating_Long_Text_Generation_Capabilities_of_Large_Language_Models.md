# HelloBench：探索大型语言模型在长文本生成方面的表现

发布时间：2024年09月24日

`LLM应用` `人工智能`

> HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models

# 摘要

> 近年来，大型语言模型 (LLM) 在多项任务中表现出色，但长文本生成能力却鲜有研究。为此，我们推出了分层长文本生成基准 (HelloBench)，这是一个全面、真实且开放式的基准，专门用于评估 LLM 的长文本生成能力。HelloBench 基于布鲁姆的分类法，将长文本生成任务细分为五个子任务：开放式问答、摘要、聊天、文本补全和启发式文本生成。此外，我们还提出了分层长文本评估 (HelloEval)，这是一种高效且与人类评估高度一致的方法。我们在约 30 个主流 LLM 上进行了实验，发现当前的 LLM 在长文本生成方面存在明显不足。例如，大多数 LLM 无法生成超过 4000 字的文本，即使能生成更长文本的 LLM 也存在严重重复和质量下降的问题。通过与传统指标和 LLM-as-a-Judge 方法的比较，我们验证了 HelloEval 的高效性和准确性。代码已发布在 https://github.com/Quehry/HelloBench。

> In recent years, Large Language Models (LLMs) have demonstrated remarkable capabilities in various tasks (e.g., long-context understanding), and many benchmarks have been proposed. However, we observe that long text generation capabilities are not well investigated. Therefore, we introduce the Hierarchical Long Text Generation Benchmark (HelloBench), a comprehensive, in-the-wild, and open-ended benchmark to evaluate LLMs' performance in generating long text. Based on Bloom's Taxonomy, HelloBench categorizes long text generation tasks into five subtasks: open-ended QA, summarization, chat, text completion, and heuristic text generation. Besides, we propose Hierarchical Long Text Evaluation (HelloEval), a human-aligned evaluation method that significantly reduces the time and effort required for human evaluation while maintaining a high correlation with human evaluation. We have conducted extensive experiments across around 30 mainstream LLMs and observed that the current LLMs lack long text generation capabilities. Specifically, first, regardless of whether the instructions include explicit or implicit length constraints, we observe that most LLMs cannot generate text that is longer than 4000 words. Second, we observe that while some LLMs can generate longer text, many issues exist (e.g., severe repetition and quality degradation). Third, to demonstrate the effectiveness of HelloEval, we compare HelloEval with traditional metrics (e.g., ROUGE, BLEU, etc.) and LLM-as-a-Judge methods, which show that HelloEval has the highest correlation with human evaluation. We release our code in https://github.com/Quehry/HelloBench.

[Arxiv](https://arxiv.org/abs/2409.16191)