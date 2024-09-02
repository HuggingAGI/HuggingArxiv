# LLaVA-Chef：一款专为美食食谱设计的多模态生成模型

发布时间：2024年08月29日

`LLM应用`

> LLaVA-Chef: A Multi-modal Generative Model for Food Recipes

# 摘要

> 在全球化背景下，随着在线食谱分享的迅速发展，对食谱理解和生成的研究日益增多。GPT-2和LLaVA等大型语言模型的进步，为自然语言处理深入食物相关任务（如食材识别和食谱生成）提供了新途径。尽管LLMs表现出色且适应性强，特定领域的训练仍是关键。本研究评估了现有LLMs在食谱生成上的应用，并提出LLaVA-Chef模型，该模型通过多阶段训练，使用多样化食谱数据集进行优化。首先，优化图像到语言的映射；其次，通过食谱数据微调LLaVA以适应食品领域；再次，利用多样提示增强食谱理解；最后，通过自定义损失函数提升食谱语言质量。LLaVA-Chef在性能上超越了预训练LLMs及以往研究，生成的食谱更为详尽且食材描述更精准。

> In the rapidly evolving landscape of online recipe sharing within a globalized context, there has been a notable surge in research towards comprehending and generating food recipes. Recent advancements in large language models (LLMs) like GPT-2 and LLaVA have paved the way for Natural Language Processing (NLP) approaches to delve deeper into various facets of food-related tasks, encompassing ingredient recognition and comprehensive recipe generation. Despite impressive performance and multi-modal adaptability of LLMs, domain-specific training remains paramount for their effective application. This work evaluates existing LLMs for recipe generation and proposes LLaVA-Chef, a novel model trained on a curated dataset of diverse recipe prompts in a multi-stage approach. First, we refine the mapping of visual food image embeddings to the language space. Second, we adapt LLaVA to the food domain by fine-tuning it on relevant recipe data. Third, we utilize diverse prompts to enhance the model's recipe comprehension. Finally, we improve the linguistic quality of generated recipes by penalizing the model with a custom loss function. LLaVA-Chef demonstrates impressive improvements over pretrained LLMs and prior works. A detailed qualitative analysis reveals that LLaVA-Chef generates more detailed recipes with precise ingredient mentions, compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2408.16889)