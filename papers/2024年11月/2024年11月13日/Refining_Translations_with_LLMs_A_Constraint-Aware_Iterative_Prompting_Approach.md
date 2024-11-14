# 用大型语言模型改进翻译：一种约束感知的迭代提示方法

发布时间：2024年11月13日

`RAG` `机器翻译`

> Refining Translations with LLMs: A Constraint-Aware Iterative Prompting Approach

# 摘要

> 大型语言模型（LLM）在机器翻译（MT）方面已经表现出了显著的熟练程度，即使在没有对相关语言进行特定训练的情况下。然而，在低资源或特定领域的上下文中翻译罕见词汇对于 LLM 来说仍然具有挑战性。为了解决这个问题，我们提出了一个多步骤的提示链，通过优先考虑对语义准确性至关重要的关键术语来提高翻译的忠实度。我们的方法首先识别这些关键词，并从双语词典中检索它们的翻译，使用检索增强生成（RAG）将它们整合到 LLM 的上下文中。我们还通过一个迭代的自我检查机制进一步减轻了由长提示引起的潜在输出幻觉，其中 LLM 根据词汇和语义约束来完善其翻译。在 FLORES-200 和 WMT 数据集上使用 Llama 和 Qwen 作为基础模型的实验表明，与基线相比有显著的改进，突出了我们的方法在提高翻译忠实度和鲁棒性方面的有效性，特别是在低资源场景中。

> Large language models (LLMs) have demonstrated remarkable proficiency in machine translation (MT), even without specific training on the languages in question. However, translating rare words in low-resource or domain-specific contexts remains challenging for LLMs. To address this issue, we propose a multi-step prompt chain that enhances translation faithfulness by prioritizing key terms crucial for semantic accuracy. Our method first identifies these keywords and retrieves their translations from a bilingual dictionary, integrating them into the LLM's context using Retrieval-Augmented Generation (RAG). We further mitigate potential output hallucinations caused by long prompts through an iterative self-checking mechanism, where the LLM refines its translations based on lexical and semantic constraints. Experiments using Llama and Qwen as base models on the FLORES-200 and WMT datasets demonstrate significant improvements over baselines, highlighting the effectiveness of our approach in enhancing translation faithfulness and robustness, particularly in low-resource scenarios.

[Arxiv](https://arxiv.org/abs/2411.08348)