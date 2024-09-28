# 多语言长上下文检索与推理评估

发布时间：2024年09月26日

`LLM应用` `多语言处理`

> Multilingual Evaluation of Long Context Retrieval and Reasoning

# 摘要

> 最近的大型语言模型（LLM）在处理长文本方面表现出色，某些模型在合成检索任务中几乎达到完美。然而，这些评估大多局限于英文，且仅涉及长文本中的单一句子。我们研究了 LLM 在多语言环境中处理多个隐藏目标句子的能力。我们评估了多种长文本 LLM 在五种语言（英语、越南语、印度尼西亚语、斯瓦希里语和索马里语）的检索和推理任务中的表现。这些语言虽共享拉丁字母，但分属不同语言家族和资源水平。分析显示，语言间性能差距显著。最佳模型如 Gemini-1.5 和 GPT-4o 在英语中准确率约 96%，而在索马里语中仅约 36%。但当处理三个目标句子时，英语准确率降至 40%，索马里语则降至 0%。这表明，长文本 LLM 在处理更长文本、更多目标句子或低资源语言时面临挑战。

> Recent large language models (LLMs) demonstrate impressive capabilities in handling long contexts, some exhibiting near-perfect recall on synthetic retrieval tasks. However, these evaluations have mainly focused on English text and involved a single target sentence within lengthy contexts. Our work investigates how LLM performance generalizes to multilingual settings with multiple hidden target sentences. We comprehensively evaluate several long-context LLMs on retrieval and reasoning tasks across five languages: English, Vietnamese, Indonesian, Swahili, and Somali. These languages share the Latin script but belong to distinct language families and resource levels. Our analysis reveals a significant performance gap between languages. The best-performing models such as Gemini-1.5 and GPT-4o, achieve around 96% accuracy in English to around 36% in Somali with a single target sentence. However, this accuracy drops to 40% in English and 0% in Somali when dealing with three target sentences. Our findings highlight the challenges long-context LLMs face when processing longer contexts, an increase in the number of target sentences, or languages of lower resource levels.

[Arxiv](https://arxiv.org/abs/2409.18006)