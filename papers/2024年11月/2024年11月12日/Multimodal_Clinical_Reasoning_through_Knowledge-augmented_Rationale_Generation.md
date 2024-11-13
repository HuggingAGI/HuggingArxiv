# 通过知识增强的理由生成进行多模态临床推理

发布时间：2024年11月12日

`LLM应用` `疾病诊断`

> Multimodal Clinical Reasoning through Knowledge-augmented Rationale Generation

# 摘要

> 临床原理在准确的疾病诊断中起着关键作用；然而，许多模型主要使用判别方法，而忽视了生成支持性原理的重要性。原理提炼是一个将知识从大型语言模型（LLM）转移到小型语言模型（SLM）的过程，从而增强后者分解复杂任务的能力。尽管有其好处，但仅原理提炼不足以解决在需要专业知识的任务（如疾病诊断）中的领域知识限制。在 SLM 中有效地嵌入领域知识是一个重大挑战。虽然当前的 LLM 主要用于处理文本数据，但结合时间序列数据（特别是电子健康记录（EHR））的多模态 LLM 仍在发展中。为了解决这些限制，我们引入了 ClinRaGen，这是一种针对疾病诊断中的多模态原理生成进行优化的 SLM。ClinRaGen 结合了独特的知识增强注意力机制，将领域知识与时间序列 EHR 数据合并，利用逐步的原理提炼策略来生成基于文本和时间序列的临床原理。我们的评估表明，ClinRaGen 显著提高了 SLM 解释多模态 EHR 数据和生成准确临床原理的能力，支持更可靠的疾病诊断，推进了 LLM 在医疗保健中的应用，并缩小了 LLM 和 SLM 之间的性能差距。

> Clinical rationales play a pivotal role in accurate disease diagnosis; however, many models predominantly use discriminative methods and overlook the importance of generating supportive rationales. Rationale distillation is a process that transfers knowledge from large language models (LLMs) to smaller language models (SLMs), thereby enhancing the latter's ability to break down complex tasks. Despite its benefits, rationale distillation alone is inadequate for addressing domain knowledge limitations in tasks requiring specialized expertise, such as disease diagnosis. Effectively embedding domain knowledge in SLMs poses a significant challenge. While current LLMs are primarily geared toward processing textual data, multimodal LLMs that incorporate time series data, especially electronic health records (EHRs), are still evolving. To tackle these limitations, we introduce ClinRaGen, an SLM optimized for multimodal rationale generation in disease diagnosis. ClinRaGen incorporates a unique knowledge-augmented attention mechanism to merge domain knowledge with time series EHR data, utilizing a stepwise rationale distillation strategy to produce both textual and time series-based clinical rationales. Our evaluations show that ClinRaGen markedly improves the SLM's capability to interpret multimodal EHR data and generate accurate clinical rationales, supporting more reliable disease diagnosis, advancing LLM applications in healthcare, and narrowing the performance divide between LLMs and SLMs.

[Arxiv](https://arxiv.org/abs/2411.07611)