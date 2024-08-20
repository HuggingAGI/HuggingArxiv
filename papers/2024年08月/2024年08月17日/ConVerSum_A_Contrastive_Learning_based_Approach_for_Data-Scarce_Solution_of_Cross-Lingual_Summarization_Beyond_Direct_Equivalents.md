# ConVerSum：采用对比学习，解决跨语言摘要中数据稀缺问题，超越简单等价的新方法

发布时间：2024年08月17日

`LLM应用` `跨语言技术`

> ConVerSum: A Contrastive Learning based Approach for Data-Scarce Solution of Cross-Lingual Summarization Beyond Direct Equivalents

# 摘要

> 跨语言摘要（CLS）是自然语言处理的一个高难度领域，要求模型不仅能翻译，还能精准总结多语言文章。尽管研究有所进展，但高效数据利用和训练方法仍是挑战。本文中，我们创新性地提出了ConVerSum方法，借助对比学习的力量，生成多语言候选摘要，并通过对比参考摘要来优化。我们用对比排序损失训练模型，并严格对比了现有方法和大型语言模型如Gemini、GPT 3.5和GPT 4，结果显示我们的模型在处理低资源语言的CLS时表现更佳。这一突破为更高效、精准的跨语言摘要技术铺平了道路。

> Cross-Lingual summarization (CLS) is a sophisticated branch in Natural Language Processing that demands models to accurately translate and summarize articles from different source languages. Despite the improvement of the subsequent studies, This area still needs data-efficient solutions along with effective training methodologies. To the best of our knowledge, there is no feasible solution for CLS when there is no available high-quality CLS data. In this paper, we propose a novel data-efficient approach, ConVerSum, for CLS leveraging the power of contrastive learning, generating versatile candidate summaries in different languages based on the given source document and contrasting these summaries with reference summaries concerning the given documents. After that, we train the model with a contrastive ranking loss. Then, we rigorously evaluate the proposed approach against current methodologies and compare it to powerful Large Language Models (LLMs)- Gemini, GPT 3.5, and GPT 4 proving our model performs better for low-resource languages' CLS. These findings represent a substantial improvement in the area, opening the door to more efficient and accurate cross-lingual summarizing techniques.

[Arxiv](https://arxiv.org/abs/2408.09273)