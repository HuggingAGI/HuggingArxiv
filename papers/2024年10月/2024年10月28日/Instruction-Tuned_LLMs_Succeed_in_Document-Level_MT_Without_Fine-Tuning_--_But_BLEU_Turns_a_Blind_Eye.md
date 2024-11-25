# Instruction-Tuned LLMs 无需微调就能在文档级机器翻译中获得成功，然而 BLEU 却对此熟视无睹。

发布时间：2024年10月28日

`LLM应用` `机器翻译`

> Instruction-Tuned LLMs Succeed in Document-Level MT Without Fine-Tuning -- But BLEU Turns a Blind Eye

# 摘要

> 大型语言模型（LLMs）在诸如机器翻译（MT）等各类自然语言处理任务中表现卓越，然而多数研究聚焦于句子级翻译。本工作探究了经指令调整的LLMs在文档级翻译（docMT）方面的固有能力。有别于以往需要专门技术的方法，我们直接提示LLMs一次性翻译整篇文档来对其进行评估。结果显示，与逐句翻译相比，此方法提升了翻译质量，即便未进行文档级微调。但这一优势在BLEU分数中未得以体现，因为BLEU分数通常倾向于基于句子的翻译。我们提议采用LLM-as-a-judge范式进行评估，其中GPT-4能以比基于n-gram的指标更精细的方式评估文档的连贯性、准确性和流畅性。总之，我们的工作表明，经指令调整的LLMs能够有效借助文档上下文进行翻译。不过，我们提醒切勿使用BLEU分数评估docMT，因其常给出误导性结果，无法反映文档级翻译的质量。代码和数据可在https://github.com/EIT-NLP/BLEUless_DocMT获取。

> Large language models (LLMs) have excelled in various NLP tasks, including machine translation (MT), yet most studies focus on sentence-level translation. This work investigates the inherent capability of instruction-tuned LLMs for document-level translation (docMT). Unlike prior approaches that require specialized techniques, we evaluate LLMs by directly prompting them to translate entire documents in a single pass. Our results show that this method improves translation quality compared to translating sentences separately, even without document-level fine-tuning. However, this advantage is not reflected in BLEU scores, which often favor sentence-based translations. We propose using the LLM-as-a-judge paradigm for evaluation, where GPT-4 is used to assess document coherence, accuracy, and fluency in a more nuanced way than n-gram-based metrics. Overall, our work demonstrates that instruction-tuned LLMs can effectively leverage document context for translation. However, we caution against using BLEU scores for evaluating docMT, as they often provide misleading outcomes, failing to capture the quality of document-level translation. Code and data are available at https://github.com/EIT-NLP/BLEUless_DocMT

[Arxiv](https://arxiv.org/abs/2410.20941)