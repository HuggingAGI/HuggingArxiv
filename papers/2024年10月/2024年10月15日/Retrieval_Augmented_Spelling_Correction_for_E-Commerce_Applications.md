# 电子商务应用中的增强检索拼写校正

发布时间：2024年10月15日

`RAG` `拼写纠正`

> Retrieval Augmented Spelling Correction for E-Commerce Applications

# 摘要

> 新品牌名称的快速涌现给电商拼写纠正服务带来了挑战，需区分真正的拼写错误和非常规拼写的新品牌。我们采用检索增强生成 (RAG) 来应对这一挑战。通过从目录中检索产品名称并融入微调后的 LLM 上下文，我们发现 RAG 框架在拼写纠正上的表现优于独立 LLM。此外，进一步微调 LLM 以整合检索内容，展现了显著的价值。

> The rapid introduction of new brand names into everyday language poses a unique challenge for e-commerce spelling correction services, which must distinguish genuine misspellings from novel brand names that use unconventional spelling. We seek to address this challenge via Retrieval Augmented Generation (RAG). On this approach, product names are retrieved from a catalog and incorporated into the context used by a large language model (LLM) that has been fine-tuned to do contextual spelling correction. Through quantitative evaluation and qualitative error analyses, we find improvements in spelling correction utilizing the RAG framework beyond a stand-alone LLM. We also demonstrate the value of additional finetuning of the LLM to incorporate retrieved context.

[Arxiv](https://arxiv.org/abs/2410.11655)