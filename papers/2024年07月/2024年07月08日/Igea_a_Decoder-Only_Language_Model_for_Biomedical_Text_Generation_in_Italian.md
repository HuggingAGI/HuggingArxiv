# Igea：专为意大利语生物医学文本生成设计的解码器语言模型

发布时间：2024年07月08日

`LLM应用` `生物医学`

> Igea: a Decoder-Only Language Model for Biomedical Text Generation in Italian

# 摘要

> 领域特定语言模型在生物医学等专业领域的自然语言处理应用中取得了显著进展，但多聚焦于英语模型，忽视了资源较少的语言如意大利语。本文引入了Igea，首个专为意大利语生物医学文本生成设计的仅解码器语言模型。基于Minerva模型，并在丰富的意大利医学文本上持续预训练，Igea提供三种规模：3.5亿、10亿和30亿参数，旨在兼顾计算效率与性能，应对意大利语医学术语的独特挑战。我们通过结合专业与通用评估基准，验证了Igea在特定训练后仍能有效保留通用知识。本文详细探讨了Igea的开发与评估，为意大利生物医学NLP的未来发展奠定了基础。

> The development of domain-specific language models has significantly advanced natural language processing applications in various specialized fields, particularly in biomedicine. However, the focus has largely been on English-language models, leaving a gap for less-resourced languages such as Italian. This paper introduces Igea, the first decoder-only language model designed explicitly for biomedical text generation in Italian. Built on the Minerva model and continually pretrained on a diverse corpus of Italian medical texts, Igea is available in three model sizes: 350 million, 1 billion, and 3 billion parameters. The models aim to balance computational efficiency and performance, addressing the challenges of managing the peculiarities of medical terminology in Italian. We evaluate Igea using a mix of in-domain biomedical corpora and general-purpose benchmarks, highlighting its efficacy and retention of general knowledge even after the domain-specific training. This paper discusses the model's development and evaluation, providing a foundation for future advancements in Italian biomedical NLP.

[Arxiv](https://arxiv.org/abs/2407.06011)