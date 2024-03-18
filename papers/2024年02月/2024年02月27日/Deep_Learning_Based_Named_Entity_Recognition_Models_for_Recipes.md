# [本研究探讨了利用深度学习技术构建的食谱命名实体识别模型，以实现对食谱中各类实体信息的精准识别与提取。](https://arxiv.org/abs/2402.17447)

发布时间：2024年02月27日

`LLM应用`

> Deep Learning Based Named Entity Recognition Models for Recipes

> 食物以其多元魅力——风味、营养、健康及可持续性等融入生活，而食谱则以非结构化文本的形式成为世代相传的文化瑰宝。为了实现从信息抽取到创新食谱生成等多种应用，开发能识别食谱文本基本构成单元——命名实体的自动化方案至关重要。为此，我们首先对6,611个手标食材短语建立基础数据集，并逐步扩充至包含26,445个短语的增强数据集。同时，我们细致梳理并利用斯坦福NER工具对黄金标准食谱库RecipeDB中的食材短语进行了全面清洗与标注。通过深入分析，我们运用聚类方法确保多样性，从RecipeDB中精选出88,526个短语构建了机器标注数据集。接下来，在这三个数据集上对比探索了统计方法、深度学习语言模型微调策略以及大型语言模型（LLMs）上的少量示例提示技术在命名实体识别任务上的效果。研究结果显示，尽管LLMs在少量示例提示方面表现欠佳，但经过微调优化后的spaCy-transformer模型脱颖而出，其在手动注释、增强和机器注释的三类数据集上分别达到了95.9%、96.04%和95.71%的宏观F1得分，展现出卓越效能。

> Food touches our lives through various endeavors, including flavor, nourishment, health, and sustainability. Recipes are cultural capsules transmitted across generations via unstructured text. Automated protocols for recognizing named entities, the building blocks of recipe text, are of immense value for various applications ranging from information extraction to novel recipe generation. Named entity recognition is a technique for extracting information from unstructured or semi-structured data with known labels. Starting with manually-annotated data of 6,611 ingredient phrases, we created an augmented dataset of 26,445 phrases cumulatively. Simultaneously, we systematically cleaned and analyzed ingredient phrases from RecipeDB, the gold-standard recipe data repository, and annotated them using the Stanford NER. Based on the analysis, we sampled a subset of 88,526 phrases using a clustering-based approach while preserving the diversity to create the machine-annotated dataset. A thorough investigation of NER approaches on these three datasets involving statistical, fine-tuning of deep learning-based language models and few-shot prompting on large language models (LLMs) provides deep insights. We conclude that few-shot prompting on LLMs has abysmal performance, whereas the fine-tuned spaCy-transformer emerges as the best model with macro-F1 scores of 95.9%, 96.04%, and 95.71% for the manually-annotated, augmented, and machine-annotated datasets, respectively.

[Arxiv](https://arxiv.org/abs/2402.17447)