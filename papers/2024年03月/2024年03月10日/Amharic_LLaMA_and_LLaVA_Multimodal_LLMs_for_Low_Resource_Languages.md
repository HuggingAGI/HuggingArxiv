# 针对低资源语言，我们推出了 Amharic LLaMA 和 LLaVA 多模态大型语言模型。这两个模型旨在为资源匮乏的语言提供强大的自然语言理解和生成能力，通过整合多种模态信息以提升性能表现。

发布时间：2024年03月10日

`LLM应用` `多模态` `低资源语言`

> Amharic LLaMA and LLaVA: Multimodal LLMs for Low Resource Languages

# 摘要

> GPT-4 和 LLaMA 等大型语言模型在处理各类自然语言任务时展现出了非凡实力，甚至在跨视觉、音频等领域也崭露头角。然而，在面对低资源语言时，受限于稀少的训练数据，即便是开源 LLMS 也常常显得力不从心。本次研究中，我们聚焦全球逾5000万人使用的阿姆哈拉语，尽管其可用数据量远低于英语等主流语言，但我们通过借鉴之前针对数据稀缺语言训练 LLMS 的策略，运用开源翻译模型进行数据扩充，成功将数据集由百万级别提升至十亿级别。此外，我们仿照 LLaVA 的方式连接了图像编码器，并在翻译后的视觉指令调整数据集上进行训练，打造出了能够同时理解图像与文本的多模态阿姆哈拉语文本理解模型。为了验证研究成果，我们还特别推出了阿姆哈拉语版的热门基准测试数据集。目前，我们的模型及数据集已在 GitHub 上开源共享。

> Large Language Models (LLMs) like GPT-4 and LLaMA have shown incredible proficiency at natural language processing tasks and have even begun to excel at tasks across other modalities such as vision and audio. Despite their success, LLMs often struggle to perform well on low-resource languages because there is so little training data available. This shortcoming is especially prevalent with open source models. In this work, we explore training LLaMA-2 to speak Amharic, a language which is spoken by over 50 million people world wide, but has orders of magnitude less data available than languages like English. We employ methods previously used for training LLMs on other languages with data scarcity, and use open source translation models to perform data augmentation and grow our dataset from millions of tokens to billions. We further enhance the capabilities of our model by connecting an image encoder and training on a translated visual instruction tuning dataset in the same manner as LLaVA, resulting in a multimodal Amharic LLM that can understand images along with text. We introduce an Amharic version of a popular benchmarking dataset to evaluate our work. Our models and dataset are open sourced and available on GitHub.

[Arxiv](https://arxiv.org/abs/2403.06354)