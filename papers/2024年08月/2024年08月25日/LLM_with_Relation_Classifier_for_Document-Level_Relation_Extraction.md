# 采用关系分类器的LLM，专为文档级关系抽取设计

发布时间：2024年08月25日

`LLM应用` `文档管理`

> LLM with Relation Classifier for Document-Level Relation Extraction

# 摘要

> 大型语言模型 (LLM) 为自然语言处理开辟了新天地。然而，在文档级关系抽取 (DocRE) 这一关键任务上，基于 LLM 的方法仍不及传统手段。本文深入剖析了这一差距的根源，指出无关系实体对导致的注意力分散是主要原因。为此，我们创新性地提出了一种分类器-LLM 结合的方法，该方法首先通过特制的分类器筛选出可能存在关系的实体对，再交由 LLM 进行精准的关系抽取。实验结果显示，我们的方法不仅大幅超越了同类 LLM 模型，更与顶尖的传统 DocRE 模型并驾齐驱。

> Large language models (LLMs) create a new paradigm for natural language processing. Despite their advancement, LLM-based methods still lag behind traditional approaches in document-level relation extraction (DocRE), a critical task for understanding complex entity relations. This paper investigates the causes of this performance gap, identifying the dispersion of attention by LLMs due to entity pairs without relations as a primary factor. We then introduce a novel classifier-LLM approach to DocRE. The proposed approach begins with a classifier specifically designed to select entity pair candidates exhibiting potential relations and thereby feeds them to LLM for the final relation extraction. This method ensures that during inference, the LLM's focus is directed primarily at entity pairs with relations. Experiments on DocRE benchmarks reveal that our method significantly outperforms recent LLM-based DocRE models and achieves competitive performance with several leading traditional DocRE models.

[Arxiv](https://arxiv.org/abs/2408.13889)