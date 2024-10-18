# 记住、检索并生成：将无限视觉概念化为您的个性化助手

发布时间：2024年10月17日

`RAG` `人工智能` `个人助手`

> Remember, Retrieve and Generate: Understanding Infinite Visual Concepts as Your Personalized Assistant

# 摘要

> 大型语言模型（LLM）的进步大大提升了多模态LLM（MLLM）作为通用助手的能力。然而，缺乏用户特定知识仍限制了其在日常生活中的应用。本文提出Retrieval Augmented Personalization（RAP）框架，通过三步将通用MLLM转化为个性化助手：(a) 记忆：设计键值数据库存储用户信息，如姓名、头像等；(b) 检索：用户对话时，RAP从数据库中检索相关信息；(c) 生成：结合输入查询和检索信息，生成个性化、知识增强的响应。RAP允许实时概念编辑，通过更新外部数据库实现。为提升生成质量和与用户信息的匹配度，设计数据收集管道并创建个性化训练数据集。基于此，训练个性化多模态助手。RAP-MLLM通过大规模预训练，无需额外微调即可推广至无限视觉概念。模型在个性化图像描述、问答和视觉识别等任务中表现出色。代码、数据和模型详见 https://github.com/Hoar012/RAP-MLLM。

> The development of large language models (LLMs) has significantly enhanced the capabilities of multimodal LLMs (MLLMs) as general assistants. However, lack of user-specific knowledge still restricts their application in human's daily life. In this paper, we introduce the Retrieval Augmented Personalization (RAP) framework for MLLMs' personalization. Starting from a general MLLM, we turn it into a personalized assistant in three steps. (a) Remember: We design a key-value database to store user-related information, e.g., user's name, avatar and other attributes. (b) Retrieve: When the user initiates a conversation, RAP will retrieve relevant information from the database using a multimodal retriever. (c) Generate: The input query and retrieved concepts' information are fed into MLLMs to generate personalized, knowledge-augmented responses. Unlike previous methods, RAP allows real-time concept editing via updating the external database. To further improve generation quality and alignment with user-specific information, we design a pipeline for data collection and create a specialized dataset for personalized training of MLLMs. Based on the dataset, we train a series of MLLMs as personalized multimodal assistants. By pretraining on large-scale dataset, RAP-MLLMs can generalize to infinite visual concepts without additional finetuning. Our models demonstrate outstanding flexibility and generation quality across a variety of tasks, such as personalized image captioning, question answering and visual recognition. The code, data and models are available at https://github.com/Hoar012/RAP-MLLM.

[Arxiv](https://arxiv.org/abs/2410.13360)