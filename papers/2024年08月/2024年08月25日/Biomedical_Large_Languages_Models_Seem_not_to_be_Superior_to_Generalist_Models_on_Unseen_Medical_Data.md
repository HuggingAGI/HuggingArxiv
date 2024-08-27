# 在处理未见过的医学数据时，生物医学大型语言模型并未展现出超越通用模型的优势。

发布时间：2024年08月25日

`LLM应用` `生物医学`

> Biomedical Large Languages Models Seem not to be Superior to Generalist Models on Unseen Medical Data

# 摘要

> 大型语言模型（LLM）在生物医学领域展现出潜力，但对其进行领域特定数据的微调效果尚不明确。本研究对比了生物医学微调的LLM与通用型LLM在临床任务上的表现，发现生物医学LLM在非医学知识任务上表现较差。尽管大型模型在案例任务上表现相近，小型生物医学模型则明显不足。在CLUE基准任务中，通用型模型在文本生成、问答和编码任务上表现更优。研究结果表明，生物医学微调可能无法带来预期益处，甚至可能降低性能，挑战了LLM领域特定适应的假设，并强调了医疗AI中更严格评估框架的必要性。替代方法，如检索增强生成，可能是提升LLM生物医学能力的更有效途径。

> Large language models (LLMs) have shown potential in biomedical applications, leading to efforts to fine-tune them on domain-specific data. However, the effectiveness of this approach remains unclear. This study evaluates the performance of biomedically fine-tuned LLMs against their general-purpose counterparts on a variety of clinical tasks. We evaluated their performance on clinical case challenges from the New England Journal of Medicine (NEJM) and the Journal of the American Medical Association (JAMA) and on several clinical tasks (e.g., information extraction, document summarization, and clinical coding). Using benchmarks specifically chosen to be likely outside the fine-tuning datasets of biomedical models, we found that biomedical LLMs mostly perform inferior to their general-purpose counterparts, especially on tasks not focused on medical knowledge. While larger models showed similar performance on case tasks (e.g., OpenBioLLM-70B: 66.4% vs. Llama-3-70B-Instruct: 65% on JAMA cases), smaller biomedical models showed more pronounced underperformance (e.g., OpenBioLLM-8B: 30% vs. Llama-3-8B-Instruct: 64.3% on NEJM cases). Similar trends were observed across the CLUE (Clinical Language Understanding Evaluation) benchmark tasks, with general-purpose models often performing better on text generation, question answering, and coding tasks. Our results suggest that fine-tuning LLMs to biomedical data may not provide the expected benefits and may potentially lead to reduced performance, challenging prevailing assumptions about domain-specific adaptation of LLMs and highlighting the need for more rigorous evaluation frameworks in healthcare AI. Alternative approaches, such as retrieval-augmented generation, may be more effective in enhancing the biomedical capabilities of LLMs without compromising their general knowledge.

[Arxiv](https://arxiv.org/abs/2408.13833)