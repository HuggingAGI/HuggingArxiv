# 深入探究大型语言模型如何在孟加拉语自然语言推理任务中超越变换器模型：一项全面深入的研究。

发布时间：2024年05月05日

`LLM应用` `机器学习`

> Unraveling the Dominance of Large Language Models Over Transformer Models for Bangla Natural Language Inference: A Comprehensive Study

# 摘要

> 自然语言推理（NLI）乃自然语言处理（NLP）之核心，洞察文本对之间的蕴含联系。它在自然语言理解（NLU）中扮演关键角色，体现从言谈或书写交流中抽取信息的技巧。NLI着重于辨析两个命题——前提与假设——之间的逻辑蕴含。若前提逻辑上暗示了假设，该对则被标记为“蕴含”；若假设与前提相冲突，则被标记为“矛盾”；证据不足时，则称为“中立”。尽管大型语言模型（LLMs）在多项任务中表现卓越，其在NLI上的表现仍受限于资源稀缺领域的准确度、模型过度自信以及捕捉人类判断差异的难度。本研究着眼于在资源匮乏语言（如孟加拉语）中评估LLMs的未充分研究领域。通过深入评估，我们对孟加拉语NLP任务中的知名LLMs和尖端模型进行了性能分析，特别关注自然语言推理。利用XNLI数据集，我们进行了零样本和少样本的评估，将GPT-3.5 Turbo和Gemini 1.5 Pro等LLMs与BanglaBERT、Bangla BERT Base、DistilBERT、mBERT和sahajBERT等模型进行了比较。研究发现，LLMs在少样本情境下的表现可与经过微调的尖端模型相媲美或更优，但为了深化我们对资源适中语言（如孟加拉语）中LLMs的理解，仍需进一步研究。本研究凸显了在不同语言环境中持续探索LLMs潜力的重要性。

> Natural Language Inference (NLI) is a cornerstone of Natural Language Processing (NLP), providing insights into the entailment relationships between text pairings. It is a critical component of Natural Language Understanding (NLU), demonstrating the ability to extract information from spoken or written interactions. NLI is mainly concerned with determining the entailment relationship between two statements, known as the premise and hypothesis. When the premise logically implies the hypothesis, the pair is labeled ``entailment''. If the hypothesis contradicts the premise, the pair receives the ``contradiction'' label. When there is insufficient evidence to establish a connection, the pair is described as ``neutral''. Despite the success of Large Language Models (LLMs) in various tasks, their effectiveness in NLI remains constrained by issues like low-resource domain accuracy, model overconfidence, and difficulty in capturing human judgment disagreements. This study addresses the underexplored area of evaluating LLMs in low-resourced languages such as Bengali. Through a comprehensive evaluation, we assess the performance of prominent LLMs and state-of-the-art (SOTA) models in Bengali NLP tasks, focusing on natural language inference. Utilizing the XNLI dataset, we conduct zero-shot and few-shot evaluations, comparing LLMs like GPT-3.5 Turbo and Gemini 1.5 Pro with models such as BanglaBERT, Bangla BERT Base, DistilBERT, mBERT, and sahajBERT. Our findings reveal that while LLMs can achieve comparable or superior performance to fine-tuned SOTA models in few-shot scenarios, further research is necessary to enhance our understanding of LLMs in languages with modest resources like Bengali. This study underscores the importance of continued efforts in exploring LLM capabilities across diverse linguistic contexts.

[Arxiv](https://arxiv.org/abs/2405.02937)