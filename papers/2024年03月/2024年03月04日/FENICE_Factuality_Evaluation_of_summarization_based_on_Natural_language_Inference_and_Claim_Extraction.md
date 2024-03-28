# FENICE 是一种利用自然语言推理和论断抽取技术对摘要进行事实性评估的方法。

发布时间：2024年03月04日

`LLM应用`

> FENICE: Factuality Evaluation of summarization based on Natural language Inference and Claim Extraction

# 摘要

> 近年来，特别是在LLMs的推动下，文本摘要技术取得了显著进步，但生成摘要中存在的事实不一致（如虚构内容）问题仍然突出。对此，人们开发了多种评估一致性的方式，但新出现的评估指标普遍存在可解释性不足、偏重于较短文档（如新闻报道）及计算复杂度过高等限制，尤其体现在基于LLM的评估指标上。因此，我们提出了一种更易理解且高效的事实性评估方法——FENICE，它借助NLI技术对源文档信息与摘要抽取的关键事实（即claims）进行比对。FENICE在事实性评估基准AGGREFACT上刷新了最佳性能记录，并进一步挑战极限，通过人工标注对长篇摘要进行了深入评估。

> Recent advancements in text summarization, particularly with the advent of Large Language Models (LLMs), have shown remarkable performance. However, a notable challenge persists as a substantial number of automatically-generated summaries exhibit factual inconsistencies, such as hallucinations. In response to this issue, various approaches for the evaluation of consistency for summarization have emerged. Yet, these newly-introduced metrics face several limitations, including lack of interpretability, focus on short document summaries (e.g., news articles), and computational impracticality, especially for LLM-based metrics. To address these shortcomings, we propose Factuality Evaluation of summarization based on Natural language Inference and Claim Extraction (FENICE), a more interpretable and efficient factuality-oriented metric. FENICE leverages an NLI-based alignment between information in the source document and a set of atomic facts, referred to as claims, extracted from the summary. Our metric sets a new state of the art on AGGREFACT, the de-facto benchmark for factuality evaluation. Moreover, we extend our evaluation to a more challenging setting by conducting a human annotation process of long-form summarization.

[Arxiv](https://arxiv.org/abs/2403.02270)