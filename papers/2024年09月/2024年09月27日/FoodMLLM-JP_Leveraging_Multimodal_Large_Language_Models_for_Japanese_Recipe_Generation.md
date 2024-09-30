# FoodMLLM-JP：借助多模态大型语言模型，探索日本食谱的生成艺术。

发布时间：2024年09月27日

`LLM应用` `人工智能`

> FoodMLLM-JP: Leveraging Multimodal Large Language Models for Japanese Recipe Generation

# 摘要

> 食品图像理解研究因其数据多样性和复杂性而备受关注，且食品与生活紧密相连，成为饮食管理等实际应用的重要领域。多模态大型语言模型（MLLM）不仅知识丰富，还能自然处理多种语言，包括日语。这预示着 MLLM 在食品图像理解任务中将有显著提升。我们微调了开放的 MLLM LLaVA-1.5 和 Phi-3 Vision，并在日式食谱数据集上进行基准测试，结果显示，在食材生成方面，我们的模型以 0.531 的 F1 分数超越了 GPT-4o 的 0.481，显示出更高的准确性。同时，在烹饪步骤生成方面，我们的模型与 GPT-4o 表现相当。

> Research on food image understanding using recipe data has been a long-standing focus due to the diversity and complexity of the data. Moreover, food is inextricably linked to people's lives, making it a vital research area for practical applications such as dietary management. Recent advancements in Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities, not only in their vast knowledge but also in their ability to handle languages naturally. While English is predominantly used, they can also support multiple languages including Japanese. This suggests that MLLMs are expected to significantly improve performance in food image understanding tasks. We fine-tuned open MLLMs LLaVA-1.5 and Phi-3 Vision on a Japanese recipe dataset and benchmarked their performance against the closed model GPT-4o. We then evaluated the content of generated recipes, including ingredients and cooking procedures, using 5,000 evaluation samples that comprehensively cover Japanese food culture. Our evaluation demonstrates that the open models trained on recipe data outperform GPT-4o, the current state-of-the-art model, in ingredient generation. Our model achieved F1 score of 0.531, surpassing GPT-4o's F1 score of 0.481, indicating a higher level of accuracy. Furthermore, our model exhibited comparable performance to GPT-4o in generating cooking procedure text.

[Arxiv](https://arxiv.org/abs/2409.18459)