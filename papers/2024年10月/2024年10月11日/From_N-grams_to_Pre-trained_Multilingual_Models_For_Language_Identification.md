# 从 N-grams 到预训练的多语言模型：语言识别的新篇章

发布时间：2024年10月11日

`LLM应用` `语言识别` `多语言处理`

> From N-grams to Pre-trained Multilingual Models For Language Identification

# 摘要

> 本文探讨了 N-gram 模型和大型预训练多语言模型在 11 种南非语言识别中的应用。研究发现，N-gram 模型的有效数据选择对语言频率分布和排名至关重要。对于多语言模型，我们测试了 mBERT、RemBERT、XLM-r 等，并与 CLD V3、AfroLID 等工具对比，发现 Serengeti 表现最佳。此外，我们提出的 za_BERT_lid 模型，基于 NHCLT + Vukzenzele 语料库，性能与顶级非洲中心模型相当。

> In this paper, we investigate the use of N-gram models and Large Pre-trained Multilingual models for Language Identification (LID) across 11 South African languages. For N-gram models, this study shows that effective data size selection remains crucial for establishing effective frequency distributions of the target languages, that efficiently model each language, thus, improving language ranking. For pre-trained multilingual models, we conduct extensive experiments covering a diverse set of massively pre-trained multilingual (PLM) models -- mBERT, RemBERT, XLM-r, and Afri-centric multilingual models -- AfriBERTa, Afro-XLMr, AfroLM, and Serengeti. We further compare these models with available large-scale Language Identification tools: Compact Language Detector v3 (CLD V3), AfroLID, GlotLID, and OpenLID to highlight the importance of focused-based LID. From these, we show that Serengeti is a superior model across models: N-grams to Transformers on average. Moreover, we propose a lightweight BERT-based LID model (za_BERT_lid) trained with NHCLT + Vukzenzele corpus, which performs on par with our best-performing Afri-centric models.

[Arxiv](https://arxiv.org/abs/2410.08728)