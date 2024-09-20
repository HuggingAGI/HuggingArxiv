# 利用检索增强生成和大型语言模型提升电商产品标题翻译效果

发布时间：2024年09月19日

`RAG` `电子商务` `机器翻译`

> Enhancing E-commerce Product Title Translation with Retrieval-Augmented Generation and Large Language Models

# 摘要

> 电子商务中的多语言产品发现需要精准的标题翻译。多语言大型语言模型 (LLM) 虽能胜任机器翻译，但在处理产品标题时，仅靠语言转换远远不够，因为标题简短、缺乏上下文且充满专业术语。为此，我们提出了一种检索增强生成 (RAG) 方法，通过利用现有双语产品信息，检索相似示例并将其作为少样本提示，以提升 LLM 的翻译效果。实验显示，该方法在 LLM 不擅长的语言对上，将翻译质量提升了高达 15.3%。

> E-commerce stores enable multilingual product discovery which require accurate product title translation. Multilingual large language models (LLMs) have shown promising capacity to perform machine translation tasks, and it can also enhance and translate product titles cross-lingually in one step. However, product title translation often requires more than just language conversion because titles are short, lack context, and contain specialized terminology. This study proposes a retrieval-augmented generation (RAG) approach that leverages existing bilingual product information in e-commerce by retrieving similar bilingual examples and incorporating them as few-shot prompts to enhance LLM-based product title translation. Experiment results show that our proposed RAG approach improve product title translation quality with chrF score gains of up to 15.3% for language pairs where the LLM has limited proficiency.

[Arxiv](https://arxiv.org/abs/2409.12880)